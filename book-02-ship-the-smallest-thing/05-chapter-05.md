# Chapter 5 — Infrastructure You Can Explain

The Thursday Packet database lived under a forgotten personal account from a weekend experiment.

The first real file — a client markup with names the builder had promised to treat carefully — sat in a temporary object URL that expired. Images on the landing page were original-resolution PNGs, pulled from the app host on every visit. Analytics showed “sessions.” It could not say whether the depositor who converted had come from the Reddit thread or from a midnight direct entry.

None of this felt like a product decision. It felt like “we’ll tidy the plumbing later.”

Plumbing is where bills, deletions, and false learnings hide. A free database that sleeps itself into a dead production; a shared schema that lets one side project poison another; a bandwidth surprise from hero images; a first-touch that is overwritten on every refresh — these are not decorations. They are whether you can explain, in one paragraph, why the system is allowed to hold a stranger’s file and a stranger’s payment credit.

This chapter is not a cloud catalog. It is a set of choices you must be able to justify: data, files, images, language, and the first-touch bind that later books will want to trust.

---

## Databases: Dormancy, Isolation, and Official Quotas

The handbook contrasts two popular hosted Postgres stories — a Supabase-shaped free tier and a Neon-shaped free tier — not as a brand war, but as a risk war: how many projects one account can hold, what happens when a project sits idle, and whether Auth or Realtime is something you actually need.

Those product names and quota stories go stale. Official pages win. The *shape* travels.

**Risks**

1. A collage of free accounts you cannot operationally remember.  
2. A free store that pauses or deletes itself after quiet weeks, taking a “launched” product with it.  
3. Sharing one database across many projects to save a quota, then discovering that a migration in project B dropped a table project A still needed.

**Suggestions**

| Shape | Teaching signal (recheck official limits) | Fits when |
| --- | --- | --- |
| Platform with strong Auth/Realtime attached | Project caps and idle-pause stories show up often in builder lore | You truly need those attached features and you will log in often enough to keep the project alive |
| Platform with a friendlier idle and many-database narrative | The handbook preferred this for lots of small experiments — as a narrative, not as your contract | Many side projects and template trials, with isolation still respected |
| One database, many apps (optional, downgraded) | Schema prefixes or a `project_id` column can save a quota | You accept cross-data risk and coupled migrations. Production work you care about should be slow to enter this shape |

**Conclusion.** Choose by “number of projects × dormancy risk × isolation need.” Connection strings live in server environment variables, never in the browser bundle.

For Thursday Packet, week one wants a database you can still find in six weeks, with entitlements and first-touch fields named like they matter. It does not want a clever shared-box trick that saves four dollars and deletes a credit table on a Friday.

---

## Files and Images Are a Bill, Not a Beauty Pass

**Risks**

1. Large images leave through your application origin and take the bill with them.  
2. Temporary share links become “production storage” until they expire in front of a customer.  
3. You treat image work as a designer’s hobby, then wonder why the landing page feels heavy on a phone in another country.

**Suggestions.** The handbook’s teaching object store is Cloudflare R2: early free-tier narrative, a bucket bound to a custom hostname, planned with cache headers rather than hoped for. Recheck the current quota and pricing. The shape is: put bytes where egress will not surprise you, and give them a stable hostname.

On images, the same archive is blunt: images are often the real performance problem. Serve a modern format (WebP or whatever is now boring and supported), resize to the display size, compress, and lazy-load what is below the fold. This is not a cosmetic ritual. It is how a smallest ship stays explainable when a stranger is on a hotel connection.

**Conclusion.** Storage and image policy belong to performance and to the bill. They are not “we’ll ask a designer later.”

Thursday Packet should not host client markups on expiring tutorial URLs. Use a bucket, a prefix per workspace, and access rules you can state in one sentence. If a file must be temporary, say so in the product and in the terms — do not let expiry be a surprise.

---

## English First; Other Languages as a Staged Bet

**A staged sequence, not a Day-1 completeness compulsion:**

1. **Ship English first** when the validation market is overseas and the information density matters.  
2. Add a high-spend language only when you have a reason — traffic, conversion clues, or a buyer you can name — not because a blog list said “don’t forget German.”  
3. Let real use tell you which language is next. Translate after you know the words that already work. A whole-site machine translation is not a strategy.

**A quiet failure mode:** the default language does not match the people who actually arrive. The handbook records a shape: default English, audience Chinese, immediate bounce. Check the default against the actual visitor picture before you announce.

**Conclusion.** Internationalization is a staged investment. It is not a completeness fever for week one.

Thursday Packet’s first users, in the composite, complained in English in a design-ops thread. English is the honest first ship. A language toggle with empty translations is a costume.

---

## First Touch Is the Analytics You Are Actually Buying

Pageviews are a sedative.

If you cannot say, after a payment, where that person first arrived, you will later argue about channels with a library of screenshots and no memory. Book 3 will care about this. Book 2’s job is to make the bind possible.

**Risks**

1. Measuring only pageviews.  
2. UTM parameters that never reach a database.  
3. Every refresh overwrites the first touch with the last.

**Suggestions.** Detect campaign parameters, a referral tag, or the document referrer. **Write the first source into durable storage** (the handbook’s teaching path uses local storage until login, then bind to the user). Payment events should still be able to see that first source. Later books will decide what to scale or cut. This book only insists that the pipe of attribution is not a leaky toy.

**Conclusion.** Analytics that cannot attribute a payment is a calming ritual.

Minimum event set for Thursday Packet:

- Landing viewed  
- Core task started  
- Core task succeeded or failed (with a short error class, not a novel)  
- Checkout started  
- Payment succeeded or failed  
- Entitlement granted (or grant failed)  
- First-touch source, frozen

If you cannot tick those, do not buy a heavier analytics product. Fix the bind.

---

## Abuse and Free Tiers Belong in the Architecture, Not in a Later Panic

Chapter 8 will go deeper on abuse as a failure mode. Architecture has to leave a hook now.

If the core action costs you money (a model call, a fat export, a stored file), a free credit without a behavior check is an invitation. The handbook’s teaching case is a site that lost roughly **$30–40** to free-tier grazing. The number is a shape, not your expected loss. The lesson is smaller: **make the expensive verb unprofitable to farm**, usually by shrinking gifts when the same IP, the same short window, or the same path appears too often. Account walls are necessary and not sufficient; bulk accounts exist. IP bans are crude and will hit paying people.

Do not pretend you will “add abuse later” if the core verb already costs you on day one. A small hook — a rate, a shrinking gift, a log — is part of explainable infra.

---

## A Paragraph You Should Be Able to Say Aloud

If you cannot say the following in under a minute, the infrastructure is not yet smallest. It is already folklore:

> “Customer files live in this bucket, under this prefix, with these credentials. Entitlements live in this table, with these names. Preview cannot touch production. If the database sleeps, we will know because this check fails. First touch is frozen at first meaningful visit and written to the user at login. Images come from this host, already sized. The expensive verb has this rate and this shrinking gift. I can find the invoices for all of the above in this one account list.”

Write it down. Put it next to the go-live card. When the paragraph needs a clause you are ashamed of, fix the clause, not the prose style.

---

## Where Explainable Infra Falsifies Itself

This chapter’s taste for boring, isolated, official-quota infrastructure fails when:

- You are already in a regime (healthcare, children’s data, certain financial records) that dictates vendors and regions. Then “pick the idle-friendly free tier” may be illegal or contractual nonsense. Follow the constraint; keep the observable task small.  
- The product *is* storage or data infrastructure. Then your smallest ship includes the guarantees you are selling. Do not use YAGNI to dodge a guarantee on your homepage.  
- A free tier’s acceptable-use policy forbids your category. Leaving is cheaper than a surprise shutdown mid-sprint.

---

## A Worked First-Touch Bind (Composite)

A tester opens `https://thursdaypacket.example.invalid/?utm_source=reddit&utm_campaign=export-thread`.

On first meaningful visit, the site writes a first-touch record: source `reddit`, campaign `export-thread`, captured at a timestamp, plus the raw referrer if present. A later visit from a bookmark must **not** overwrite that record. At login or at guest-checkout bind, the record is copied onto the user (or onto the workspace) and becomes the payment attribution.

If the same person later arrives from a mailing-list link, that is last-touch or a separate field if you need it. It is not allowed to erase the first honest arrival. Book 3 will argue about how to spend against these fields. Book 2 only requires that the fields exist and stay still.

**Fail Fast:** if the write of first-touch fails, log it. Do not silently proceed as if the person “just appeared.” A missing first-touch on a paying user is a defect, not a mysterious channel called Direct.

---

## What “Explainable” Looks Like When Something Breaks

When a customer says a file vanished, you should be able to answer, from the paragraph in this chapter, whether the file expired by policy, was in a preview bucket, or is a genuine loss. When a bill jumps, you should know whether images, exports, or a farmed verb did it. When a database is quiet for three weeks, you should know whether a free tier may have paused it, and what check would have told you.

If those answers require a founder’s memory, the infrastructure is still folklore. Folklore does not survive a second product, a second timezone, or a week of flu.


## Takeaway

**Rule:** Infrastructure must be explainable in one paragraph: where files live, what may sleep, what is isolated, how first touch is frozen, and how the expensive verb is bounded.

**This week:** Separate preview from production, put files in a stable bucket, freeze first touch, and put a shrinking gift or rate on any verb that costs you money.

**Not a promise:** Free-tier folklore, including a roughly $30–40 abuse bill and idle-pause stories, is a teaching shape. Official quotas and your own invoice win.
