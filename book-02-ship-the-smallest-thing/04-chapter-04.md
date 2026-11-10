# Chapter 4 — The Address Has to Work

The Thursday Packet builder finally deployed — to the platform’s default `*.something.app` URL.

The page loaded. A friend posted the link in a private chat. One of the depositors tried to pay, then wrote: “Is this the real site? The typo in the URL looks like a phishing kit.” The payment reviewer, later, would not have liked the consumer Gmail in the business profile either. Search, had anyone bothered, would have found a JavaScript shell and a nearly empty first HTML response.

The builder said, “We’ll attach the domain this weekend, after the editor tokens are done.”

The domain is not a hat you put on a finished product. The domain is the product’s address, its review identity, and often the difference between “this looks like a business” and “this looks like a tab I should close.” DNS is mechanical. Mail is mechanical. Crawlable HTML is mechanical. Mechanical work is where serious teams get sloppy, because it does not photograph like a component tree.

This chapter is the unglamorous half of shipping small: Git to host, environment variables, DNS, a mailbox that can pass review, and a first response that actually contains the promise.

---

## Git Push Is the Ritual; Zip Upload Is a Detour

**Risks**

1. You stall because “we don’t know how to run a server.”  
2. Local works, production dies, because environment variables never left the laptop.  
3. After a failed deploy, you click Redeploy in a console until the same broken commit is blessed again.

**Suggestions**

1. Create the project by importing the Git host. The platform should see branches, not a mystery zip.  
2. Move environment variables as a set. Production and preview are not the same set. Secrets never commit, not even in a “temporary” dotenv you promise to un-track later.  
3. Deploy. When it fails, read the log. Paste the log into your assistant if that helps. Then **change the code and push**. The point of a host is that the next push is the next deploy.  
4. Attach the custom domain. Follow the platform’s A or CNAME instructions on both sides — platform *and* DNS — or you will debug a ghost.  
5. Make “commit means publish” the default rhythm. Manual zip uploads are a rescue, not a lifestyle.

**Conclusion.** For a tool site or a content site, the psychological threshold of going live is usually higher than the technical one. Once the path has worked once, write it as a short SOP and stop treating it as heroism.

Thursday Packet should be able to answer, in one sentence: “A merge to this branch updates the production URL.” If the answer is “I upload from my desktop when I remember,” the loop is already personal, which means it is already fragile.

---

## DNS Is a Checklist, Not a Myth

Subdomains have a reputation they do not deserve. A subdomain is a DNS record. A CNAME to a host, an A record to an IP, or a special record for object storage or a CDN is not a spiritual event.

**Risks**

1. Mythologizing subdomains into a week of research.  
2. “Cleaning up” DNS and deleting the production record because a tutorial said to start fresh.  
3. Changing DNS but never finishing the bind on the platform side — or the reverse.

**Suggestions**

- Write the record you intend (name, type, target, proxy on or off) before you touch the zone.  
- Complete **both** sides: DNS and platform. Test with a lookup and with a browser, and do not trust a single flushed cache.  
- If you move the domain’s nameservers to a CDN/DNS host (Cloudflare is the common teaching example in the handbook), inventory the scanned records *before* you flip. Do not blindly empty a live zone.  
- Propagation “in about ten minutes” appears as folk experience in the same archive. It is experience, not a guarantee. Some records are quick. Some resolvers are stubborn. Plan a buffer; do not schedule a launch announcement against a folk timer.  
- Crawler-friendly hints, email routing, and custom domains for object storage are useful once nameservers are in place. They are still checkboxes, not a new religion.

**Conclusion.** The domain is the product’s address and its review identity. The operations are mechanical. The discipline is a written checklist.

A reasonable smallest map for Thursday Packet:

- `thursdaypacket.example` — the site (canonical).  
- `www` — redirect to the canonical host.  
- `files` or similar — object storage if you need a public file hostname (Chapter 5).  
- Mail records as required by your routing setup.

Do not invent a zoo of marketing subdomains in week one.

---

## A Domain Mailbox Is an On-Ramp, Not a Hobby Mail Server

**Risks**

1. Using a personal Gmail, QQ, or similar as the only contact for payment review, ads review, or customer mail — then stalling in a queue you cannot see.  
2. Building a full mail stack “for professionalism,” and spending the sprint on spam fighting.

**Suggestions.** The handbook’s teaching path is a **forwarding** domain mailbox (Cloudflare Email Routing is the named example): `support@` and `contact@` (and the address the processor asked for) forward to a box you already read. That is usually enough to look like a business and to receive reviewer mail.

The boundary is honest: forwarding is not a full company mail suite. You may not have custom sending reputation, shared inboxes, or fancy signatures that survive every provider. You may later need a real mail product. Week one does not.

**Conclusion.** A domain mailbox is a go-live item, not an optional decoration. Chapter 6 will lean on it again when a processor asks who you are. This chapter only requires that the primary domain can receive mail.

If Thursday Packet’s deposits were confirmed from `thursday.packet.gmail.com`, fix that before you write more canvas code. The depositor already told you, in so many words, that identity is part of the product.

---

## If the First HTML Is Empty, You Did Not Ship a Page

Search and AI-answer systems are later books (Book 4). This book still has a hard engineering gate: **a direct request for the page should return the main promise in HTML.**

**Risks.** You finish every on-page ritual and still serve an empty shell. You bet that a crawler will “just run the JavaScript.” Sometimes it will. Betting the validation window on kindness is not a smallest-ship move.

**Suggestions.** Default a new site to a server-rendered or pre-rendered path so “view source” or `curl` shows the hero sentence and the core explanation. Deep keyword strategy, internal linking, and off-site trust are not this book’s job. This book’s job is to downgrade, during the validation window, any stack whose first trick is a blank document.

**Conclusion.** Content that can be fetched reliably beats a client-side spectacle with nothing in the first response.

A two-minute test anyone can run:

```text
curl -sL https://your-canonical-host/ | head
```

If a tired person cannot find the homepage promise in that output, you do not yet have an indexable promise. You have a demo that requires a browser.

This is also a Fail Fast test. Put it in the ship checklist. Do not argue with it.

---

## Environment Isolation Is Part of the Address

People treat environment variables as plumbing. They are also how you accidentally point a preview branch at production data, or print a secret into a client bundle.

Minimum discipline:

- Preview, production, and local are three files or three sets — not one file with a comment.  
- Database connection strings, login secrets, and storage keys stay on the server side.  
- A missing required variable should prevent boot (Fail Fast), not silently fall back to a hardcoded “temporary” key from a tutorial.  
- When a deploy fails because of a typo in a name, fix the name. Do not add a second alias “just in case.” Naming is design.

If Thursday Packet’s preview environment can decrement production export credits, you do not have a preview. You have a loaded gun with a friendly URL.

---

## A Worked Address Card (Composite)

```text
ADDRESS CARD — Thursday Packet  date: 2026-11-10

Git → host:
  Production branch deploys on push. Failed build is a red check, not a click ritual.

Domains:
  canonical apex + www redirect. No marketing subdomain zoo.

DNS / platform bind:
  Both sides done. Lookup matches the host docs. Proxy setting written down.

Mailbox:
  support@ and contact@ forward to a box that is actually read.
  Payment profile uses the domain address.

Crawl test:
  curl shows the hero sentence: “Get a Thursday-ready export whose client names stay readable.”

Env:
  Preview and production isolated. Boot fails if DB or login secrets are missing.

Risks (≥3):
  1) DNS “cleanup” deletes mail records.
  2) curl test is skipped because “it looks fine in Chrome.”
  3) Reviewer mail lands in a folder nobody opens.
  4) Preview shares the production bucket of customer files.

Suggestions:
  Screenshot the zone before edits.
  Add curl to the go-live card as a required tick.
  Page the support inbox on a phone for two weeks.
  Separate buckets or prefixes, with credentials that cannot cross.

Conclusion: Conditional pass when curl, mailbox, and isolation ticks are green.
```

---

## Where Address Work Falsifies Itself

Mechanical address work is not enough when:

- You are in a category that needs more than a forwarding mailbox and a template privacy page (regulated claims, children’s data, certain financial product shapes). The smallest ship then includes the slower compliance work. Do not use “mechanical DNS” as a way to skip it.  
- A host outage *is* your product (you sell uptime). Then a second path may belong in scope earlier. Most indie tool sites are not in this set. Write the exception if you are.  
- You cannot yet put the real brand on a domain you do not control. Parked good intentions are not a launch. Get the registrar account in order first.

---

## Common Breaks, Written as Recipes (Not a Curse Book)

These are mechanical. Write the one you hit in the go-live card so you do not mystify it next time.

**“I changed DNS and nothing happened.”**  
Check the nameserver set the registrar actually publishes, then the record in *that* zone, then the bind on the platform side. If any of the three is a different world, you have been editing a ghost. Folk “ten minute” timers do not apply to a ghost.

**“Mail to support@ vanishes.”**  
Send from a third-party address, not from the same domain you are testing, and look in spam. Confirm the forwarding destination still exists. If you later add sending, that is a different setup; this book’s week-one bar is receiving.

**“Local login works; production redirects into a hole.”**  
The allow-list and redirect URIs on the identity provider still name localhost. Add the canonical host. Do not “temporarily” disable HTTPS to make it easier.

**“Preview and production somehow share users.”**  
A connection string or a bucket prefix was copied. Rotate the leaked secret. Do not only “fix the variable” and leave the old key alive.

**“curl looks empty but Chrome looks fine.”**  
You shipped a client shell. That may be a deliberate later choice. During the validation window, it is a failed tick, not a taste debate.

Keep the recipes boring. Drama in this layer is almost always a missed checkbox.


## Takeaway

**Rule:** The address has to work. A launch without a domain, a mailbox, isolated secrets, and crawlable HTML is still a demo with better lighting.

**This week:** Import the repo to a host, attach the domain on both sides, stand up forwarding mail, and run `curl` until the promise is visible in the first HTML.

**Not a promise:** Folk timers like “DNS in ten minutes” are experience reports, not guarantees. Reviewers do not owe you a pass because the mailbox exists.
