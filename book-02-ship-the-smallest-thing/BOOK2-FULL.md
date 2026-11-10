# Ship the Smallest Thing

**Subtitle:** How to Deliver an Observable Product and Get Paid Without Mythology

**Series:** The Sea Playbook — Book 2 of 5

**Author:** Micheal (An Yaming)

**Edition note:** English Kindle manuscript for manual Amazon KDP upload. No auto-publish bots. Handbook case figures elsewhere are teaching shapes, not forecasts, launch timers, or payout guarantees.

---

## Promise

After you finish, you should be able to turn a Book 1 proceed verdict into **one observable delivery**: a homepage promise a stranger can read, a core task they can finish once, a live domain with analytics and a mailbox, and a test payment whose webhook grants the right entitlement.

You should also leave with a written **switch playbook** for the payment pipe—before that pipe is allowed to become the business.

That is a skill promise: artifacts, gates, and a dated ship / shrink / wait verdict. It is not a money promise.

## Not a Promise

Nothing in this book guarantees launch time, conversion, approval, settlement, unfreezing, or a revenue tier.

Handbook teaching cases you will meet—template “launch in an hour” stories, a site that lost roughly **$30–40** to free-tier abuse, fee-table impressions from around **October 2026**, a checkout-trust questionnaire, a payment-platform security incident that ended in permanent termination—are **illustrations of shape**. Study the shape. Do not tattoo the numbers, timelines, or brand dramas on your OKRs. Do not quote them as what *your* launch will cost or earn.

If a sentence ever sounds like certainty for sale, reread this page. Certainty is the cathedral’s favorite costume.

## The Rule You Can Say Out Loud

Launch is feedback, not a graduation gift.  
The homepage promise is the backlog.  
Pipes are not a business.

Keep the three layers separate. A deploy starts observation. A feature list that cannot be seen on the homepage is not the product yet. A checkout stub is plumbing. The verdict is an entitlement that actually lands—and a recovery plan if the pipe breaks.

Book 1’s rule still stands behind this one: inspiration is a seed, a complaint is evidence, a payment is a verdict. Book 2 refuses to treat “we shipped code” as that verdict.

---

## How to Use This Book

This is a field manual for the week after a demand verdict, not a framework beauty contest.

**Read once for the spine.** Chapter 1 fixes the launch myth. Chapters 2–3 choose a clock and bind scope to the homepage promise. Chapters 4–5 get the address, mailbox, data, and observability working. Chapters 6–7 treat payment as an asset with entitlements, not a plugin. Chapter 8 names failure modes. The Interlude puts open-source comparison and AI-coding discipline on the bench. Chapter 9 packs two weeks.

**Then run Chapter 9 with the templates.** Empty theory without a dated go-live card is cosplay. The templates in `templates/` are the product.

**Suggested paths**

| If you are… | Do this |
| --- | --- |
| Solo indie / overseas builder with a Book 1 proceed verdict | Front matter → Ch 1 → Ch 3 → Ch 4 → Ch 7 → Ch 9 sprint |
| Stuck rewriting architecture instead of deploying | Ch 1–2 aloud → Interlude → Ch 8 red lines on the wall → Ch 9 Week 1 only |
| Already live but unpaid or un-entitled | Ch 6–7 + webhook acceptance template; then Ch 8 on single-basket risk |
| Only here for PSP vs MoR language | Ch 6 + payment-channel card; still respect the perimeter |

**Artifacts beat highlights.** A highlighted Kindle paragraph that never becomes a go-live row did not count.

**Stop rules while reading:** if you catch yourself designing a multi-region mesh during Chapter 3, close the infrastructure tab. If you catch yourself hunting “the cheapest processor,” close the rate card and open the net-proceeds and trust questions. Return to the homepage promise.

### What “done” means for Book 2

You are done with Book 2’s job when you have:

1. A written homepage promise that matches the broom you already sold (or a dated decision that you will not ship yet).  
2. An MVP boundary card: in / out / later, with a living forbidden-scope list.  
3. A Git-to-host deploy that a teammate (or tomorrow-you) can repeat from a commit.  
4. A real domain, canonical basics, and a domain mailbox usable for review and support.  
5. Analytics that can bind a first touch, not just a vanity pageview.  
6. A sandbox (or otherwise repeatable) payment path: test pay → webhook → entitlement green.  
7. A chargeback / cancel / abuse minimum, and a switch playbook for the pipe.  
8. A two-week (or honest compress) verdict in writing: ship, shrink, or wait.

You are **not** done when you have a fashionable stack, a pixel-perfect design system, five payment logos on a pricing page, or a local demo that dies when the laptop lid closes.

### If you do not have a Book 1 verdict

If you do not yet have a fire-test PASS, a job one-liner, and a priced ask (or a dated reason you will not ask yet), this book will help you build a prettier trap.

Go back to *Complaints, Not Inspiration*. Sell air first. Book 2 is not a workaround for a missing demand verdict.

---

## Gatekeeper Rules (Use Before You Praise)

Every go / no-go call in this series follows the same order:

1. **Risks / holes first** — at least three, concrete.  
2. **Suggestions** — what would reduce those risks.  
3. **Conclusion** — pass / conditional pass / reject, with conditions named.

Praise before risks is how “we’ll polish then launch” survives. Risks before conclusions is how a smallest-ship meeting earns the right to spend calendar.

### Gate checklist (copy into reviews)

```text
【Risks / holes】(≥3, write first)
1. …
2. …
3. …

【Suggestions】
- …

【Conclusion】
- Pass / Conditional pass / Reject
- Conditions (if any): observable task, deploy path, mailbox, webhook test, switch playbook, CVE line
```

If someone refuses to write risks first, they are asking you to fund a cathedral. Decline politely. Decline in writing.

---

## Path Diagram (Text)

Book 2’s motion, in one strip:

```text
Book 1 verdict (proceed) + job one-liner + forbidden_scope + priced promise
        │
        ▼
Launch as feedback  ←── shell, deploy, landing, analytics, domain first
        │
        ▼
Clock-based selection  ←── template vs build; stack matches infra, not fashion
        │
        ▼
Homepage promise = backlog  ←── one core task visible; deep features last
        │
        ▼
Address works  ←── Git→host, env isolation, DNS, mailbox, crawlable HTML
        │
        ▼
Explainable infra  ←── data, files, first-touch attribution; i18n is staged
        │
        ▼
Payment as asset  ←── buyer × entity × shape × tax role × net + trust
        │
        ▼
Entitlement lands  ←── product / price / webhook tested; cancel visible
        │
        ▼
Verdict: ship | shrink + date | wait
        │
        ▼
Book 3 — Buy Time, Not PMF   (only after a loop you can observe)
```

**Hard boundary:** ad scaling, SEO systems, GEO, and link-building belong later in the series. Using them as substitutes for the strip above is how teams buy traffic for a product that cannot be finished once, or a pipe that cannot grant what was sold.

**Handbook early priority (teaching, not prophecy):** after a survivor and a broom, the emphasis shifts from “is this demand real?” to “can a stranger complete the promise and can money complete the loop?” Do not smuggle Book 3 or Book 4 into Day 2 of a ship sprint.

---

## Series Note — The Sea Playbook

| Book | Title | Job of the book |
| --- | --- | --- |
| 1 | Complaints, Not Inspiration | Find demand: complaints, fire, jobs, chain, air |
| **2 (this book)** | Ship the Smallest Thing | Smallest observable delivery + getting paid without mythology |
| 3 | Buy Time, Not PMF | 1–2 channels; ads buy time; CTR ≠ PMF |
| 4 | Earn the Click | SEO systems × GEO qualification × link trust |
| 5 | Numbers That Decide | Breakpoints, stop/scale rules, solo-company vetoes |

Read in order when you can. Skipping Book 2 to start at ads is a common way to fund a landing page that cannot fulfill.

Each book ends with a bridge and the same perimeter: **no income promises; cases are shapes; risks before conclusions.**

---

## Time Boxes (Honest)

| Pass | Duration | Outcome |
| --- | --- | --- |
| Spine read (Ch 1–9 + interlude) | one focused evening or two short ones | mental model + red lines |
| Template familiarization | 30–45 minutes | blank MVP / go-live / payment / webhook / switch cards opened |
| Full Chapter 9 sprint | 14 calendar days (or 7-day compress) | dated ship / shrink / wait verdict |
| Gatekeeper review of a card | 15–30 minutes | risks → suggestions → conclusion |

If you only have a lunch hour, do not “speed-run” a fake launch. Do a thirty-minute boundary pass (Chapter 3) and schedule the two weeks. Fake launches create fake confidence and real cleanup.

---

## Named Reader

I write for people who ship without a platform team:

- Indie developers  
- Overseas site builders  
- One-person product leads  
- Small teams that can still change direction in a week  

If you already have a staffed payments and SRE function, treat Chapters 6–8 as hygiene and skim the stack arguments. If you are still waiting to launch until the architecture “feels grown-up,” stay for the whole ride.

The desk this book was written from is an overseas-builder desk: English-first pages, hosted deploy, domain mail, open-source comparison before reinventing, payment rails that have to survive a Chinese founder serving foreign cards (and, separately, a domestic buyer line that must not be mixed into the same pot). The psychology travels. The vendor names lean that direction on purpose. They are not endorsements, and they go stale. Official docs and your own tests win.

---

## Voice Contract (English Craft)

Short sentences when the point is a gate. Concrete nouns and verbs. Case → definition → boundary. Named tools and templates over slogans.

You will not find filler that sounds like a model warming up. If a paragraph cannot survive a gatekeeper pass, it should not survive your ship week either.

**Verifiable quotes only.** When a public line appears (for example the XP community’s “You aren’t gonna need it,” or Steve Blank’s teaching that facts about customers live outside the building), it is attributed. Invented testimonials are forbidden.

---

## Materials You Will Need Before Chapter 9

- The Book 1 carry-forward pack: job one-liner, forbidden_scope, priced promise, risk list  
- Blank MVP boundary card (`templates/mvp-boundary.md`)  
- Go-live checklist (`templates/go-live-checklist.md`)  
- Payment-channel card (`templates/payment-channel-card.md`)  
- Webhook acceptance sheet (`templates/webhook-acceptance.md`)  
- Switch playbook (`templates/switch-playbook.md`)  
- A Git host and a hosted deploy target  
- A domain you control, and a way to receive mail at that domain  
- A sandbox or otherwise repeatable payment path  
- A timer  
- Chapter 8’s red lines visible  

If checkout is “we’ll figure it out after the UI sings,” start figuring in Week 1. Mid-sprint payment archaeology creates fake silence that you will misread as “no demand.”

---

## A Note on Handbook Numbers

Wherever this manuscript mentions approximate **$30–40** abuse losses, “one-hour” template launches, fee-table impressions from around **October 2026**, or platform dramas (trust questionnaires, account terminations, acquisition rumors), read them as **case shapes from the Sea handbook teaching archive**—paths and warnings someone else wrote down, summarized for judgment practice. They are not your targets, not your floor, and not a promise that the same bill, timeline, rate, or ban will happen twice.

Vendor fees, quotas, CVEs, and acceptable-use lists move. Recheck the official page and the contract you actually signed before you price, migrate, or upgrade.

The scarce skill is making a promise observable and a payment complete. Scoreboards are optional. Cathedrals are expensive.

---

*Begin Chapter 1 when the broom is already sold and the monorepo tab is already open. Keep this front matter nearby when someone says “we’ll launch when it’s ready.”*


---

# Chapter 1 — Launch Is Feedback, Not a Graduation Gift

The Thursday Packet pre-sale page had been live for nine days.

Three people had paid a deposit for a “clean Thursday export” — the broom already named in Book 1. The job one-liner was still taped above the monitor: *When Thursday handoff hits and exports corrupt non-ASCII names, I want a clean packet in one pass, so I can take the client call without panic edits.*

The builder was not packing packets.

The laptop showed a half-drawn component tree for a “real editor.” A typography token file. A discussion in a private note: *If we only ship the export path, we will look small. Clients will expect an Editor X killer. Let’s launch when the workspace feels complete.*

The deposits sat in a test product that had never granted an entitlement. The domain still pointed at a registrar parking page. Analytics was “we’ll add it when the UI is proud.”

In that room, the argument was about the wrong thing.

They were treating launch as a graduation gift — a ceremony you earn after the cathedral is beautiful — instead of the start of a feedback loop the deposits had already paid to join.

I have sat in that room, sometimes as the person drawing the component tree. Completeness feels responsible. It photographs well. It fits a slide titled “Quality.” A curl of a homepage that already states the promise does not. Neither does a webhook log that proves one test payment granted one export credit.

So teams optimize for the photogenic version of shipping.

This book is about the other version.

**A launch is not the end of building. It is the first day the promise can be observed from outside the building.** Features that cannot be finished once, on a real address, with a payment that grants what was sold, are still indoor hobbies — no matter how elegant the stack.

---

## Who This Book Is For (and Who Should Skim)

This is a short book for people who already did the demand work — or who are about to pretend they did — and now face the itch to overbuild: indie developers, overseas site builders, one-person product leads, small teams that can still change direction in a week.

If you already have a staffed payments team, a boring deploy pipeline, and a weekly habit of shrinking scope in public, you may only need Chapters 6–8 as hygiene. If you are still waiting to launch until the architecture “feels grown-up,” stay for the whole ride.

What you will not get: a guaranteed ship date, a conversion lift, a secret processor that always approves, or a personality makeover that turns you into a calm operations saint. What you will get is a portable discipline — promise in, observable task out, entitlement as the real launch — and the templates to practice it without waiting for a platform team.

I write from the overseas-builder desk: English-first pages, hosted deploys, domain mail, open-source comparison before reinventing, payment rails that have to survive foreign cards. The psychology travels. The vendor names lean that direction on purpose. They are not endorsements.

### Promise vs. perimeter

The front of this book makes a usable promise: after you finish, you should be able to define an observable MVP, get it on a real domain, and take a test payment whose webhook grants the right entitlement. The perimeter is just as important: nothing here promises a launch timer or a revenue tier. Handbook figures you will see — template “one-hour launch” stories, a roughly **$30–40** abuse bill, fee-table impressions from around **October 2026** — are teaching cases. Study the shape. Do not tattoo the numbers on your OKRs.

If a chapter ever sounds like it is selling certainty, reread the perimeter. Certainty is the cathedral’s favorite costume.

---

## The Graduation Tax

“We’ll launch when it’s ready” feels free.

No invoice arrives when you postpone DNS. No alert fires when a pre-sale is left unfulfilled while you redesign navigation. The tax shows up later as calendar debt: weeks of polite indoor work, a quiet chart because no stranger could use the thing, a payment account you still have not tested, and a new workshop to invent the next architecture. Teams rarely connect the tax to the postponement. They connect it to “market timing,” or “we needed more polish,” or “the framework wasn’t mature.”

A smallest-ship discipline is a way to front-load a cheaper tax. Putting a crawlable landing page on a real domain costs an afternoon after the template is honest. Testing one payment through a webhook costs pride, because the first failure is usually your mapping, not the universe. Both are cheaper than a quarter of components nobody hired.

You do not need to become sloppy about craft. You need to become strict about when craft is allowed to delay observation — including your future self’s observation.

---

## Two Quiet Sequences (Cases, Not Promises)

Before we turn the rule into a method, hold two honest sequences from the same handbook I keep on my desk when shipping for overseas markets. Both are *cases*, not forecasts. Neither guarantees you a ship date or a clean bill.

**Sequence one — the shell before the shrine.**

In indie-builder circles, a familiar launch SOP shows up around template stacks (the handbook discusses one commercial Next-based kit as a teaching path). The order is almost boring: clone the shell, move environment variables, deploy from Git, put a landing page on a keyword, hook analytics, attach a domain, then build the one capability the homepage already promised, and only then connect payment and prove the callback.

Read that path for the order, not the marketing clock. Some write-ups around templates boast that a site can be “up in an hour.” That hour is a sales costume. Your hour will include a typo in a callback URL, a DNS lag, and a privacy page you forgot. The discipline is: **deploy and observe before you invent the rest of the product.** The advertised hour is someone else’s brochure. It is not a promise that your Thursday Packet will be live before lunch.

### A note on “I already have it running locally”

Solo builders often skip the parking-page shame and still never launch. The app runs on `localhost`. Screenshots look real. A friend clicked through on a video call. That feels like shipping.

It is not. Local success cannot be crawled, cannot pass a processor review, cannot collect first-touch data from a stranger, and cannot teach you what breaks when the environment variables are the production ones. Use the local build as a generator of the next commit. Use a public URL as the filter.

If the only person who can finish the core task is you, on your laptop, you may have a demo, not a product. Demos can still become products — after the address works and one entitlement lands.

**Sequence two — sold before the factory.**

Another pattern looks reckless from far away and like measured sequencing up close: a service already being sold (the handbook uses a well-known generative-video company as a shape: demand visible in a service marketplace, then a product built on top of proven willingness to pay). The lesson is not “copy that company.” The lesson is narrower and harder: **write code to fulfill a promise that already had a buyer shape**, not to discover whether a cathedral might someday need a door.

Put the two sequences next to each other and the room gets quieter:

**What shipping work actually lacks is not framework knowledge. It is the judgment to start the loop while the promise is still small enough to see.**

The cathedral plan is loud and flattering. The shell-deploy-observe loop is loud in your logs and ugly in a meeting deck. The second one looks more like a business entrance.

---

## What a Launch Is Doing (That a Demo Is Not)

A demo answers: can *I* make it work in a friendly room?

A launch, in this book’s narrow sense, answers four ruder questions:

1. Can a stranger **read the promise** at a stable address?  
2. Can they **finish the core task once**, without a guided tour from you?  
3. Can you **see** that they tried — page, event, first touch, error?  
4. If they paid (or you ran a test payment), did the **entitlement actually land**?

Those four questions are the difference between a graduation gift and a feedback mechanism.

The mechanism is allowed to be ugly. Placeholder images are allowed. A design system is not required. A multi-region failover is not required. What is required is that the loop can run without you sitting in the middle as a human API.

### Definition, then boundary

**Definition.** In this book, the smallest ship is an **observable delivery**: indexable promise + one complete core task + instrumentation + a payment path you can test. “Minimum” does not mean “fewest screens for bragging rights.” It means “enough to start learning from the outside without lying about what was sold.”

**Boundary.** This definition fails when the demand verdict is missing (go back to Book 1), when the core task is hidden three menus deep, when “analytics” is a pageview with no first-touch bind, or when “payments” is a badge on the footer and a webhook nobody has replayed. It also fails if you use “we launched” as a moral license to stop shrinking scope.

---

## The Indoor Veto List

Here are behaviors this book downgrades or rejects on sight. They are not sins against taste. They are ways the graduation myth eats the loop.

| Behavior | Why it is downgraded |
| --- | --- |
| Unvalidated demand, perfect architecture first | Violates “You aren’t gonna need it” (the XP community’s YAGNI). Sunk cost then kidnaps the topic. |
| Microservices reserved for a hypothetical million daily users | Violates KISS. MVP-stage theater. |
| Inventing an interaction a comparable site already solved | Compare open source and competitors first; implement the difference. |
| Features finished before GA, domain, or crawlable HTML | You miss the starting gun and the indexable window. |
| Consumer Gmail or QQ as the only identity for payment and ads review | A domain mailbox is infrastructure, not decoration. |
| Promising “we ship in X days” or “this will convert” | Forbidden in outward speech; do not use it as an inward KPI hallucination either. |
| Five processors on the pricing page, zero webhook tests | Pipes displayed as mythology; entitlements ignored. |

YAGNI, here, is not an aesthetic of ugliness. It is a scheduling rule. Ron Jeffries and the Extreme Programming community popularized “You aren’t gonna need it” as a warning against building for an imaginary future. The imaginary future is exactly what the component tree for a “real editor” is doing to Thursday Packet.

---

## If You Catch Yourself Building Editor X

Return to the composite. The wedge was never “a new editor.” The wedge was a Thursday-ready export path with sane name-encoding defaults. Libs for parse and fill already existed. The hosted shell was the gap.

Every hour spent on a competing canvas is an hour the deposits go unfulfilled. It is also an hour you teach yourself the wrong lesson: that looking complete is safer than being observable.

If a feature does not help a design-ops lead walk out of Thursday with a clean packet, it goes on the later list. If it contradicts the forbidden_scope you carried from Book 1, it is not “later.” It is no.

This is not a personality lecture about humility. It is a fiduciary duty to the sentence you already sold.

---

## Where This Framing Falsifies Itself

A honest method names the conditions under which it should be paused.

**Stop treating “launch early” as a virtue when:**

- The product can harm someone if a half-done path runs (health, money movement you do not legally control, irreversible generation). Ship a narrower safe loop, or wait.  
- You have no demand verdict, only a pretty template. Early launch then becomes public inspiration.  
- Compliance requires a review you have not started (payments, regulated categories). “We will hide the button” is not a plan.  
- The core task cannot be finished at all yet — not even once, not even ugly. Launching a brochure that lies about the button is not feedback. It is advertising fiction.

Early is not the same as false. Feedback requires a true, small promise.

---

## The Rule You Can Say Out Loud

You will not finish this chapter with a perfect stack. You will finish with a rule you can say in the next meeting without sounding mystical:

> Launch is feedback, not a graduation gift.  
> The homepage promise is the backlog.  
> Pipes are not a business.

Everything else in this book — clock-based selection, crawlable addresses, explainable infrastructure, payment as an asset, entitlements that land — is how to keep that rule from rotting into another slogan on the wall next to “We value craft.”

Clear the cathedral plan for two weeks. Open a go-live card instead. If the card stays empty, you do not have a talent problem. You have a sequencing problem — or a courage problem about showing an ugly honest loop.

Either way, the component tree can wait.

Before you approve the next “real editor” milestone, ask three questions that fit in the same minutes the builder used to sketch tokens:

- **Which promise are we making observable this week?** Write it down. “The workspace should feel complete” does not count.  
- **Can a stranger finish the core task once, at a real address, and can we see it?** If not, deploy and instrument before you schedule the shrine.  
- **If a test payment already happened, did the entitlement land — or did we get busy?** Only the first answer turns shipping into an engineering practice. The second trains everyone to hide an unfulfilled sale under polish.

The cathedral will still call. Token files can still be created.

If this week buys you one public URL, one finished core task, and one webhook you can replay, that week was not a loss.

What shipping work should collect was never the feeling of readiness. It was the honesty that keeps you from inventing indoors when the promise is already speaking outside.

---

## Takeaway

**Rule:** Launch is feedback, not a graduation gift.

**This week:** Freeze cathedral work that does not serve the sold promise. Put a crawlable page on a real domain. Name the one task a stranger must finish.

**Not a promise:** Handbook cases (template “one-hour” launches; a roughly $30–40 abuse bill; fee-table impressions) are paths to study, not timers or cost forecasts for your project.


---

# Chapter 2 — Selection Is a Clock, Not a Personality

Two notebooks lay open next to the Thursday Packet deposits.

Notebook A was a template README: clone, environment variables, one Git host, one hosted deploy, a login hook already sketched. The builder had written in the margin, *Looks like every other indie site. Clients will know.*

Notebook B was a fresh architecture: a “real” rendering stack, an edge runtime the team had never shipped, a queue, a custom auth from first principles, and a migration plan off the platform the template already used. The margin said, *If we are serious, we should own the stack.*

Neither notebook asked the only question that matters in week one: **what must be observable, and how many days of clock do we still have before the sold Thursday arrives?**

Selection, at the smallest-ship stage, is not a personality test. It is not “am I a real engineer?” It is a clock. The clock started when the promise left your mouth. Framework fashion does not pause it.

---

## The First Question Is the Validation Clock

**Risks**

1. Refusing a template to “understand the metal,” then spending three weeks wiring login.  
2. The opposite: a template so sealed you cannot change the homepage promise.  
3. Treating “I want to learn this framework” as if it were the overseas validation window.

**Suggestions**

| Situation | Lean toward | Because |
| --- | --- | --- |
| You need to test a keyword, a landing promise, and a login funnel in days | A template or a boring hosted shell (handbook teaching names include commercial Next kits; use whatever you can actually edit) | Shell, auth hooks, payment hooks, and SEO bones often come pre-placed. You pay in license cost and in learning someone else’s conventions. |
| The difference is the core path, and the template cannot be bent without lying | Build, or deeply fork the template | Still start from an open-source scaffold. Do not invent auth or billing from a blank folder. |
| You mainly want to learn a framework | Downgrade it to a practice project | Do not spend the validation window on homework. |

**Conclusion.** The first selection question is the validation clock, not technical self-esteem. A template is an accelerator, not a substitute for skill. A self-build needs a written difference — a reason the template would falsify the promise.

For Thursday Packet, the difference is not “we wrote our own editor.” The difference is an opinionated Thursday path with encoding defaults. That difference can live inside a boring shell. It does not require a new metal.

---

## Template Honesty, Not Template Worship

A template fails this book when you cannot:

- Change the homepage sentence without fighting a vendor lock in the layout.  
- Keep secrets out of the repository.  
- Run a production environment that is not the preview environment.  
- See, in one afternoon, how a payment webhook would reach your entitlement code.

If those four are blocked, you do not have an accelerator. You have a sealed box with a nice README.

A self-build fails this book when the written difference is aesthetic (“cleaner components”) or speculative (“we might need ten products”). Aesthetic differences belong in a later polish pass. Speculative products belong in the souvenir lot from Book 1.

### Open source before you invent

Micheal’s hard rule for this desk — and a series rule from Book 1 — is simple: **compare open-source and comparable sites before you close the door and invent.** Login, payment hooks, internationalization, and server-rendered pages are solved problems with scars already documented.

The comparison is not a scavenger hunt for something to copy blindly. It is an honesty field: if a library already parses and fills the markup, Thursday Packet should host a workflow, not re-litigate a parser. If a mature starter already does session cookies safely, you should have a reason before writing your own.

License caution still applies. Prefer clear, commercially usable licenses when the code will sit in a product you sell. Treat stricter copyleft as study unless counsel says otherwise. Reading a popular repository is not the same as pasting it into a closed product and hoping.

---

## Stack Debates Are Usually Infrastructure Debates in Costume

The handbook keeps a migration narrative that is easy to misread as a fashion verdict: a move from a mature Next.js plus Vercel default toward a TanStack plus Cloudflare “family” (Workers, object storage, a database product, a key-value store). Some write-ups in that archive even say global visits *felt* faster after the move.

Treat that sentence as a **case**, not a standing order. Feelings are not benchmarks. Benchmarks are not bills. Bills are not your bills.

**Risks**

1. Framework debate becomes a substitute for shipping.  
2. The real variables — multi-project cost, storage, egress, deploy friction — hide under taste.  
3. A migration interrupts a main site that is still in its validation window.

**Suggestions (teaching contrast, not a permanent ruling)**

| Dimension | Mature hosted Next-style default | Edge-family narrative in the handbook |
| --- | --- | --- |
| Getting started and ecosystem | Strong; lots of SSR and SEO writing | You must learn a different project shape; AI tools have lowered that cost for some people, which is not the same as “easy for you” |
| Deploy ritual | Git push, preview, production | A unified story across compute, storage, and DNS is the appeal |
| Multi-project cost | Hosting plus third-party database plus storage can stack | The narrative is “one bill to explain” — verify on official pricing, not on a blog |
| Speed “feel” | Can be tuned | Handbook writers reported a global feel-good (case) |
| Risks | Platform pricing and function usage; framework CVE surface (Chapter 8) | Ecosystem maturity, team habit, and the schedule cost of the move itself |

**Gates**

- **One site, need stability, template already in the mature default** — do not migrate for the story.  
- **Several sites in parallel, and the combined storage/CDN/compute bill is starting to hurt** — evaluate a unified family; pilot on a *non-critical* site.  
- **Any migration that would pause the main validation loop** — rejected until the loop is observable.

**Conclusion.** Stack selection is infrastructure matching for the current stage. “Most advanced” is not a goal. “Can go live, can be replaced, and the bill can be explained” is.

Thursday Packet, in week one, almost certainly stays on whatever shell already deploys. The encoding path is the product. The runtime brand is not.

---

## When to Touch Your Own Server

Some builders treat Nginx and SSH as a coming-of-age ritual. Others treat them as a permanent allergy.

Both extremes waste clock.

**Risks:** avoiding servers forever as a personality; or, in week one, burning days on process managers when a hosted platform would have served the promise.

**Suggestions.** The handbook’s later note is modest: with current AI assistance, a self-hosted path can be broken into unromantic steps — rent a machine, SSH, install a runtime and Git, pull, run the service, put a reverse proxy in front. That is useful **reserve capacity**. It is not the default for a content site, a tool site, or a SaaS prototype.

Self-hosting earns its week when you have a special runtime, long-lived connections the host forbids, a cost model that has actually flipped, or a platform limit you have hit and documented. “I want to feel close to the metal” is a practice project.

**Conclusion.** Default to a host. Self-hosting is a reserve skill and a special case, not a rite of passage for overseas week one.

---

## Naming Is Design (Even at Selection Time)

A clock-based selection still needs names you can search later.

If your environment variables are called `KEY`, `DATA`, and `TOKEN2`, you will ship a mystery. If your entitlement is called `flag` in one table and `quota` in another, the webhook will “succeed” and the user will still be locked out. If the project repository is named `final-v3-real`, you are already arguing with yourself.

Micheal’s rule on this desk is blunt: **naming is design**. First-touch fields, entitlement names, and product codes should be retrievable by a tired person at 1 a.m. Ban empty names: `data`, `temp`, `util`, `handle`, `stuff`.

Fail Fast belongs here too. If a required environment variable is missing, the boot should die loudly. Silent `except: pass` is how localhost success becomes production folklore.

These rules are not bureaucracy. They are how a two-person team — or a one-person team with a future hangover — can still change a pipe at 48 hours’ notice (Chapter 6).

---

## A Worked Selection Card (Composite, Not a Verdict on Your Stack)

```text
SELECTION CARD — Thursday Packet  date: 2026-11-10

What must be observable in 14 days?
  Stranger reads “clean Thursday export for messy client names,”
  finishes one encoding-safe packet, we see the event,
  a test payment grants one export credit.

Template or build?
  Template shell for auth, deploy, and page bones.
  Difference we will actually write: opinionated export path + encoding defaults.
  Difference we will not write: a new editor, a comment engine, a design system.

Stack match?
  Stay on the template’s hosted default.
  Revisit unified edge family only if three more sites share the bill
  and this loop is already green.

Self-host?
  No. No documented platform limit. No special runtime.

Open-source honesty?
  Parser/fill libs A/B already run on our fixture (Book 1 card).
  We host the Thursday workflow; we do not reinvent the engine.

Risks (≥3):
  1) Template theme fights the promise sentence.
  2) Encoding edge cases become support load.
  3) Migration daydream pauses DNS and webhook work.
  4) License / lock-in if we outgrow the kit.

Suggestions:
  Time-box theme surgery to one afternoon.
  Keep a fixture folder of nasty names; make it a boot test.
  Write “no migration in sprint” on the wall.
  Read the template license once, in daylight.

Conclusion: Conditional pass — template shell + hosted default.
Conditions: homepage sentence editable; webhook path visible; no editor work in the two-week window.
```

This card is a teaching sketch. It is not a recommendation that you buy any named kit, nor a promise that a template will fit your promise.

---

## Where Selection Falsifies Itself

Clock-based selection fails when:

- The template’s acceptable-use or license fights your category (especially generative or high-risk tools). Switching costs should be paid *before* you decorate the theme.  
- Your difference *is* the platform (you are selling hosting, or a runtime). Then “use a generic shell” may be the wrong smallest ship. Write that exception down; do not use it as a loophole for taste.  
- Security or data-residency constraints forbid the default host. Compliance is a clock too. It is a different clock. Ignoring it is not YAGNI; it is negligence.

If you are in one of those exceptions, the method still holds: write the constraint, choose the boring legal option, and keep the observable task small. The exception is not an invitation to build a mesh.

---

## “But We Might Need Multi-Tenancy”

This is the most common clock-killer after “real editor.”

You might. You also might not. Multi-tenancy, custom roles, audit logs, and a plugin system are how a Thursday export path becomes a platform company in a slide. If a second workspace is required *this week* for a named tester who already paid, add the thinnest possible isolation (a `workspace_id` on the relevant rows, a prefix in the bucket) and no more. If the need is hypothetical, write it on the later list.

YAGNI is uncomfortable here because “everyone knows” serious products have teams. Serious products also have a promise they can finish on Thursday. The team features can be added when a second paying workspace exists, not when a notebook is lonely.

The same cut applies to “we might need to be on every cloud.” You need one host that deploys from Git and a bill you can explain. A multi-cloud diagram is a later book, and usually a later company.


## Takeaway

**Rule:** Selection is a clock, not a personality. Match infrastructure to the current stage; do not interrupt a live validation to feel advanced.

**This week:** Write a selection card with a difference sentence, a host decision, and three risks. Compare one open-source path before you invent.

**Not a promise:** Migration “feel” stories and template launch clocks in the handbook are cases, not orders or timers for your site.


---

# Chapter 3 — The Homepage Promise Is the Backlog

The first paid tester for Thursday Packet opened the site on a Wednesday night.

She did not want a tour. She wanted to know, in one screen, whether Thursday would hurt less. The homepage hero said “All-in-one workspace for modern design teams.” A second fold listed eight features, two of which did not exist. The export path — the only sentence she had paid for — lived behind a menu labeled **Tools**, then **Workspace**, then **Advanced**, then a muted link: *Legacy export (beta).*

She wrote to the domain’s consumer Gmail, which bounced because there was no domain mailbox. She left.

The builder, looking at a heat map that did not exist yet, said the usual sentence: “People will find it once we add onboarding.”

They will not. Not in the way you think. A stranger believes the first honest sentence they can read. If the first sentence is a costume, the product is a costume. The backlog is not a ticket list in a side panel. The backlog is the promise on the homepage, and only the work that makes that promise completable once.

---

## What Must Be There (and What May Wait)

The handbook compresses a launch SOP into a table that is more useful than most roadmaps. I will translate it into the language of this book. It is a teaching sequence, not a certification.

| Stage | Must have | May wait |
| --- | --- | --- |
| Shell | A running template or repo; theme can be ugly | A perfect design system |
| Environment | Database, login (Google-first is a common overseas default), secrets in the host — not in Git | A complete permission matrix |
| Deploy | Git host → hosted platform, repeatable from a commit | Multi-region, blue-green, a private mesh |
| Landing page | One primary promise; enough indexable text; placeholder images allowed | A polished demo reel of features you have not shipped |
| Policy pages | Working links for terms, privacy, and basic identity | Law-firm custom prose on day one (regulated categories may require more — ask a lawyer, not a template README) |
| Analytics | A page tool plus a behavior tool you will actually open (handbook teaching stacks often mention a GA-class tool plus a session tool) | A perfect warehouse |
| Domain | Canonical basics, a sitemap that can start with the important URLs, a Search Console property | A flood of thin URLs |
| Capability | **The homepage promise, finishable once** | “We might need this later” neighbors |
| Payment | Price visible when you are ready to charge; callback and entitlement tested | The globally optimal mix of processors (Chapter 6) |

Read the table as a fence, not as a shopping list you must buy in full before Monday. The fence says: if a row in the left column is empty, you are not waiting on taste. You are waiting on the loop.

---

## Definition: Observable, Not Merely Small

**Definition.** An MVP in this book is three things at once:

1. An **indexable promise** — a stranger and a crawler can both see what you claim.  
2. **One core task** that can be completed once without you on a video call.  
3. **Observability** — you can tell that the task was tried, failed, or finished, and (once money is in play) whether the entitlement landed.

**Boundary.** “Minimum” is not a contest to delete buttons until the screenshot looks brutalist. A three-button app that cannot finish the Thursday packet is not small. It is incomplete. A twenty-page app whose only working path is the packet *can* be a smallest ship if the other pages are honestly marked later — or, better, not shipped.

YAGNI applies to the later list. KISS applies to the path. Neither rule is a license to ship a lie.

---

## The Feature Gate

**Risks**

1. The homepage promises “one-click clean packet,” but the capability is a deep-link Easter egg.  
2. Features expand sideways until the keyword and the promise drift apart.  
3. “Just one more adjacent tool” quietly becomes Editor X.

**Suggestions**

1. Find the thinnest API or library that performs the core verb (for Thursday Packet: parse, fix names, fill, export). Wire the **basic** capability first.  
2. Walk a comparable site’s mainstream path before you invent a clever one. Open-source and competitor honesty is still in force.  
3. Put the capability on the homepage. A boutique tool site often lives or dies by that visibility. A buried beta link is a way to avoid being judged.  
4. Replace placeholder images with real output samples when you have them. Samples serve trust. They still do not guarantee conversion. Never caption a sample as “typical results.”

**Conclusion.** MVP equals indexable promise plus one complete core task plus observability. Everything else is YAGNI until the loop is green.

For Thursday Packet, the core task is: upload or connect the messy markup, get a packet whose client names survive, download it, and (if they paid) have the credit decremented exactly once. Comments, version history, an AI rewrite assistant, and a collaborative canvas are souvenir-lot items. They can be written on a later list. They cannot sit in front of the packet.

---

## Login and Chat Are Friction Sensors, Not Costumes

A common overseas default is “sign in with Google first.” The handbook also discusses a one-tap prompt that reduces the redirect bounce, and a lightweight chat widget (one teaching name is a common European chat box) so early users can report a fatal bug without writing an essay.

**Risks.** Dropping authentication “to move fast.” Promising reply times you cannot keep. Blaming the widget when the one-tap prompt never shows, when the real issue is a domain allow-list.

**Suggestions**

| Capability | Teaching point | Gate |
| --- | --- | --- |
| Google sign-in | Get the boring path working | Domain and redirect URIs complete; test on the real host, not only localhost |
| One-tap style prompt | Less redirect theater | If it does not appear, check origin allow-lists first, not the component library |
| Small chat or mail entry | Lowers the cost of a fatal-bug report | Early on, this often beats “just leave an email.” Do not advertise a support SLA you do not run |

**Conclusion.** You may reduce friction. You may not blur authentication or privacy baselines. A chat box is a sensor. It is not a marketing slogan, and it is not a substitute for a domain mailbox (Chapter 4).

If Thursday Packet can run a first export without an account, that can be legitimate — Chapter 7 will talk about guest checkout — but the backend still has to bind the work and the payment to an entitlement. “No login” is not “no memory.”

---

## Forbidden Scope Is a Living Document

Book 1 asked you to keep a forbidden_scope list next to the job one-liner. Book 2 is where that list gets tempted.

Every request from a friendly tester will sound reasonable. “Could it also comment?” “Could it also be a light editor?” “Could it also store our whole design system?” Reasonable requests are how Editor X re-enters through the side door.

The rule is mechanical:

- If the request does not help the job one-liner complete once, it is **later** or **no**.  
- If it contradicts forbidden_scope, it is **no**, even if a tester will pay a little more for it. Price is not a hall pass to blow the wedge.  
- If you accept it, you rewrite the homepage promise the same day. A promise that is not allowed to change while the backlog changes is how teams learn to lie.

Write the decision down. Public later/no lists are cultural hygiene, the same as public kills in Book 1.

---

## A Worked Boundary Card (Composite)

```text
MVP BOUNDARY — Thursday Packet  date: 2026-11-10

Homepage promise (one sentence):
  Get a Thursday-ready export whose client names stay readable.

Core task (once, no video call):
  User submits a messy markup file → sees a preview of repaired names
  → downloads a packet → (if paid) one credit is used and shown.

In for the two-week window:
  - Promise sentence and short how-it-works
  - Fixture-tested encoding path
  - Google login + optional guest start
  - Domain, mailbox, analytics with first-touch bind
  - Test payment → webhook → export credit
  - Visible cancel / refund contact
  - Terms and privacy links

Out (forbidden or later):
  - New editor canvas
  - Comment threads
  - AI rewrite of client comments
  - Team permissions beyond “one owner, one workspace”
  - Multi-language UI (English first; Chapter 5)
  - Second processor logo “for trust”

Risks (≥3):
  1) Preview lies (looks fixed, download is not).
  2) Credit decrements twice, or never.
  3) Support load from encodings not in the fixture.
  4) Homepage still talks like a workspace suite.

Suggestions:
  Preview must be generated from the same bytes as the download.
  Webhook acceptance sheet before any real charge (Chapter 7).
  Expand fixtures weekly; do not pretend completeness.
  Rewrite the hero until a tired person can repeat the broom.

Conclusion: Conditional pass.
Conditions: preview/download parity test; entitlement test; hero rewrite before traffic.
```

This is a teaching sketch. It is not a claim that a product named Thursday Packet exists or earns.

---

## Where Promise-Driven Scope Falsifies Itself

The homepage-as-backlog rule fails when:

- The real job is a bundle that cannot be demonstrated in one task (a marketplace with two sides, for example). Then the smallest ship is still *one* completable side of the loop, honestly labeled. Do not use the bundle as an excuse to ship two half-sides.  
- Safety requires friction the homepage would rather hide (age gates, generation moderation, irreversible payments). Put the friction in the path. A smooth lie is not a smallest ship.  
- You keep rewriting the hero to match whatever you built this afternoon. That is the Inspiration Wall in a new font. Change the promise only when the job one-liner changed, and treat that as a demand event, not a copy tweak.

---

## Promise Drift: A Fifteen-Minute Diagnostic

Once a week, even inside the sprint, read the homepage aloud and then complete the core task as if you were unpaid and slightly impatient.

Ask:

1. Does the first sentence still match the job one-liner from Book 1?  
2. Can you finish the task without opening a “docs” tab the team wrote for themselves?  
3. Does any nav item or screenshot advertise a later/no item as if it were present?  
4. If a depositor forwarded only the hero sentence to a colleague, would that colleague be surprised by what actually runs?

If you fail two of the four, you do not have a copy problem. You have drift. Fix it the same day: rewrite the hero, hide the lie, or formally change the job (which is a demand event, not a polish task).

A screenshot folder of “what the homepage looked like on Day 4, Day 7, and Day 14” is a cheap honesty device. If the sentence got vaguer as the days passed, the cathedral is leaking in through adjectives.

---

## FAQ (Homepage as Backlog)

**Is a waitlist page a homepage promise?**  
Only if the waitlist states a priced broom you already sold or are honestly pre-selling, and does not imply a working button. A waitlist that talks like a shipping product is advertising fiction (Chapter 1’s boundary).

**Can the core task live in an authenticated app if the homepage is marketing?**  
Yes, if the homepage says so, and if a signed-in tester can still finish once without a tour. “Marketing site plus hidden app” fails when the app’s first screen is a suite and the broom is again under Advanced.

**What if legal needs a longer disclaimer than the hero?**  
Put the hero first and the disclaimer adjacent and readable. Do not hide the broom under a paragraph of fear, and do not hide the risk under a peppy slogan.

**What if testers keep asking for a tour anyway?**  
Record the sticking point as an event class. Improve the one path. A tour video is a later tool, not a substitute for a path that cannot be finished silently.


## Takeaway

**Rule:** The homepage promise is the backlog. MVP means an indexable promise, one complete core task, and the ability to see what happened.

**This week:** Write the hero in one sentence. Put the capability on that page. Move everything else to later/no. Make a boundary card with three risks.

**Not a promise:** A visible promise does not guarantee conversion. Samples and chat boxes are instruments, not revenue spells.


---

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


---

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


---

# Chapter 6 — Pipes Are Not a Business

The Thursday Packet pricing page earned a small cheer in the group chat: four processor logos, a toggle for monthly and yearly, and a footnote that said “industry-standard rates.”

No one could answer, without opening six tabs, who the legal seller was. No one had estimated net proceeds on a typical order after tax, international-card add-ons, and a pessimistic dispute. The backup processor was a logo. Its application form was blank. All four marks pointed, in practice, at a single account the builder also intended to use for a later product that had nothing to do with Thursday exports.

They had confused a pipe gallery with a business.

A pipe moves money. A business can still fulfill, still recover, and still explain who the seller was if the pipe clogs. This chapter is the mental model and the selection gate. Chapter 7 is the entitlement and the ugly operational work. Do not skip ahead to webhook folklore until you can say which role you are playing and what happens on a Tuesday if that role is cancelled.

---

## Two Roles That Are Constantly Mixed

**Risks**

1. Treating every “we can take a card” product as the same kind of thing.  
2. Assuming that connecting a famous processor automatically handles global VAT and invoices.  
3. Assuming a merchant-of-record fee that looks “one or two points higher” is always a waste.

**Suggestions.** The handbook’s consensus compresses into a table you should be able to redraw from memory:

| Role | Teaching examples | Who is the legal seller? | Who carries a large share of tax / invoicing / some compliance? | Typical trade |
| --- | --- | --- | --- | --- |
| **PSP (payment service provider)** | Stripe is the usual name in builder talk | Still you | Mainly you | Often lower headline rates; you own tax, a larger share of fraud strategy, and category risk |
| **MoR (merchant of record)** | Paddle, Lemon Squeezy, and several newer names in the same archive (Creem, some lines of WAFFO, Dodo, Polar, Gumroad — a list that will rot; recheck) | The platform sells in its own name | The platform carries a large block | You pay more. You are buying compliance bandwidth for a small team — not a papal indulgence |

For a person without a company and without a finance staff, the extra MoR points often buy time and paperwork you would do badly. The same archive is equally blunt the other way: **a merchant of record is not a shield of immortality.** A data incident, a banned category, or a card-network decision can still end the relationship for good.

**Conclusion.** First decide whether you can be the seller and whether you will carry tax. Then choose PSP or MoR. The rate is the second question.

Thursday Packet, in the composite, is a small overseas tool with a solo builder. Either role can be honest. What cannot be honest is “we picked four logos and will figure out the seller later.”

---

## Payment Is an Asset; Assets Get Isolated and Backed Up

**Risks**

1. One account runs every product you will ever ship.  
2. One merchant of record holds all of the revenue you cannot afford to pause.  
3. You discover you have zero backup on the day a queue email arrives.

**Suggestions.** A teaching incident in the handbook — a merchant-of-record account permanently terminated after a security event — sits next to a chorus of “there is no best processor, only backups.” Read it as a shape, not as a true-crime serial:

- **One product, one account**, as far as the platform allows, so that one mess does not automatically sit on everything else. Platforms can still correlate. Isolation reduces blast radius; it does not make you invisible.  
- **No permanent “winner.”** Builder lore will tell you that one brand is strict, another got stricter after an acquisition, a third has a trust or conversion problem, a fourth is new and bleeds checkout abandonment, a fifth rejects some generative categories, a sixth “takes the whole pot” when it bans. Those are weather reports. Weather changes. The structural lesson does not: **do not put the only key under one mat.**  
- **The skill that matters in a failure is time-to-restore charging**, not a post-mortem about who had the lowest rate. The archive’s teaching mindset is “be able to restore the business on the order of 48 hours.” That is a mindset, not a promised recovery SLA.

**Conclusion.** Payment selection is a primary pipe plus a switchable backup plus account isolation. The cheapest rate that cannot be replaced is a high-interest loan.

Write the 48-hour idea into the switch playbook *before* revenue dependency exists. After dependency exists, you will “not have time.”

---

## Five Filters Before You Compare a Rate Card

| Filter | Ask | Failure symptom |
| --- | --- | --- |
| **Where the buyer is** | Mostly overseas cards? Do you also need a WeChat or Alipay buyer-side path? | Wrong local method, or a checkout brand the buyer will not trust → abandonment |
| **Who you are legally** | Mainland individual / Hong Kong personal settlement / a company in HK, US, UK / licensed entity | KYC stall, or a path you should not have taken |
| **Product shape** | Subscription, one-time, usage, file download, sensitive generation | The pipe cannot renew; the category is refused |
| **Who is the seller** | You carry tax (PSP) or the platform does (MoR) | A tax surprise, or a rate you misunderstood |
| **Trust and conversion** | Will the buyer recognize the checkout brand? | You save a fee and lose the sale (the handbook’s teaching questionnaire around a less-familiar MoR is this shape) |

If you cannot fill the five filters on a card, you are not ready to argue about two-tenths of a point.

---

## A Teaching Map of Overseas Pipes (Structure Only)

The following impressions are from the handbook’s comparison context around **October 2026**. They are **structural contrast, not a quote of what you will be charged**, and not a recommendation to open any particular account. Fees, ownership, and review posture move. Official pages and the contract you sign win.

| Pipe (teaching name) | Role | Entity hurdle (archive’s wording) | Rate impression (stale by default) | Often fits | Risk signals in the same archive |
| --- | --- | --- | --- | --- | --- |
| Stripe | PSP | A standard account as a Mainland individual is hard; common paths run through a Hong Kong or US company, or a compliant Hong Kong personal route | Relatively lower, with add-ons for international cards, conversion, and billing products | You have an entity and want documentation plus buyer recognition | Strict risk systems, correlated bans, opaque reasons; you will need a fraud tool |
| Paddle | MoR | Individuals and small teams: depends on review | A “about 5% + a fixed cent” impression in the archive | You want steadiness and will pay a compliance premium | Some generative categories may be refused; the rate sits a step higher |
| Lemon Squeezy | MoR | Feature-complete stories (subscriptions, license keys, downloads) | A similar 5% + fixed impression, plus add-ons | Digital goods that need those features | Acquisition-by-Stripe lore and a tighter review narrative; know your exit |
| WAFFO / Pancake (as named in the archive) | Mixed | Pancake line described as more individual-friendly | Card/wallet impressions around the mid-3%s plus a fixed fee; some WeChat-buyer stories | You truly need a China-buyer scan path | New-pipe trust; abandonment must be measured; payouts are a separate math |
| Creem | MoR | Archive noted Mainland ID KYC friendliness | Lower MoR impression (mid-3%s plus a fixed fee) | Personal overseas start, if you accept the rest of the story | Trust/conversion questions; risk and ban cases; a security event can end the relationship permanently |
| Dodo Payments | MoR | Mid-pack in the archive | About 4% + fixed, plus add-ons | Often one-time charges | Subscription plus WeChat limits in the archive; “whole pot” ban lore |
| Polar | MoR | Depends on when you joined | Spreads between early members and new tiers can be large | Early users sitting on an old rate | Upgrading a paid tier may retire the early rate |
| Gumroad | MoR | Fast shop setup | Direct fees high; “discover” higher | Creator traffic and simple shops | Expensive; may lack the buyer-side wallets you want |
| PayPal (including a paypal.cn personal-seller path in the archive) | Wallet / acquiring world | The cn personal-seller path has real-name and shop review | Official pages only | Buyers who insist; a domestic supplement | Risk systems and caps; do not make it your only pipe |

**Domestic buyers (China), a shorter mindset:**

1. If you have the license, official WeChat / Alipay merchant paths come first.  
2. If you do not, use a formal onboarding agent — and **confirm that settlement lands in a same-name official account** (the archive’s warning against illegal second-clearing).  
3. Personal collection QR codes, “hanging” codes, and no-sign shortcuts as a way to run a business are **rejected** in this book.

Overseas and domestic lines are two systems. Do not stir them into one pot because it photographs as “we take everything.”

---

## Four Questions, Then a Combination (Not a Promise)

**Risks:** looking only at the base rate; mixing domestic and overseas money in one flow; saving a point on a path that may not return the money.

**Four questions**

1. **Where is the buyer?** Overseas-first → a PSP if you have an entity, or an MoR if you are a person. Need a WeChat buyer-side path → check what the pipe can actually do after configuration, not what a landing page implied.  
2. **Do you have a Hong Kong or US (or other) company, or a compliant Hong Kong personal settlement path — and will you carry tax?** If yes, a PSP can be honest. If no, use an MoR. Do not invent an identity to force a PSP.  
3. **Subscription or one-time?** Subscriptions need billing, renewal, and (if required) local methods that actually support recurring charges. One-time sales can use a shorter list.  
4. **Have you estimated net proceeds?** International-card add-ons, subscription add-ons, wallet add-ons, payout fees, sales tax or VAT, dispute fees — run one typical order through a napkin or a “proceeds calculator” like the teaching sheet in the handbook. Pricing and pipe choice belong in the same table.

**Combinations as structure, not as a blessing:**

- **Overseas primary + domestic secondary:** one primary overseas pipe (PSP or MoR) plus one already-applied backup; domestic official or formal agent on a separate line.  
- **Cold start as a person:** one lower-hurdle MoR to take the first honest charges while you validate, then consider a recognized PSP when the entity is real and you need the trust.  
- **Sensitive categories (generative and similar):** read each acceptable-use list before you apply; keep two pipes in mind from the start.

**Conclusion.** Selection order is **buyer → entity → product shape → tax role → net proceeds and trust**. “Who is cheapest?” comes last.

---

## Sticker Price Is Not What You Keep

**Risks:** putting **$19** or **$29** on a page and ignoring tax, fees, and disputes; a unit price so low that the fixed fee eats it.

The handbook is candid: some low prices, after deductions, “look like charity.” That is a teaching alarm, not a law about your number. The structural point is the floor: **the fee shape determines the lowest honest price you can offer.** If the fixed fee plus tax plus a pessimistic dispute reserve leaves you with a token, you do not have a pricing disagreement. You have a pipe / price mismatch.

**Conclusion.** Estimate what you keep before you freeze the sticker. Payment work and pricing work are one table.

Thursday Packet should price the Thursday credit on net, not on a competitor’s homepage, and not on a desire to look “impulse cheap.”

---

## Entity, Bank, and PayPal: Compliance Work, Not a Speedrun

This book will not give you a travel itinerary or a promise that a bank will open.

**Stripe-shaped paths in the archive** (again: no approval promise):

- A Hong Kong personal path: region set correctly, a Hong Kong account for settlement, individual type, names identical across ID and bank, two-factor, a business description that matches the live site, and **settlement currency aligned with the currency you actually charge** (a USD default when you charge USD, rather than a quiet conversion into local currency).  
- A US / UK company path: register in the entity’s region; study local rates and conversion; sometimes a USD settlement account lowers conversion tax; optional climate or charity add-ons should be a conscious choice, not a leftover toggle.  
- Isolation still: one line of business per account, knowing the platform may still connect dots.

**Hong Kong cards and numbers**, in the same archive, are treated as **infrastructure, not a game**. Preparation beats “it went smoothly for someone on a blog”: documents, roaming that can receive codes, the bank’s app with a non-wrong-region store ID, a charger that will pass a security check, a list of what the branch wants. A cheap eSIM can hold a number; it is a poor primary lifeline. Traditional and digital banks as a pair have backup value. None of this guarantees an account.

**PayPal**, including a personal-seller path on the cn site, is a wrench in the box. Registration is not global charging. Shop and site review may be required before cross-border collection. If you migrate an existing overseas login into a China personal-seller shape, read the official capability map *before* you move, because limits change. Useful as a supplement. Dangerous as a sole pipe.

**Conclusion.** Opening an account is compliance work, not a walkthrough you “win.” Real documents and currency alignment beat folklore about “how fast they approved me.”

If you cannot tell the truth on the form, this book has nothing for you. Fake identity is a veto, not a tactic.

---

## A Worked Channel Card (Composite)

```text
PAYMENT CHANNEL CARD — Thursday Packet  date: 2026-11-10

Buyer: overseas design-ops leads, cards, English checkout.
Entity: none yet; no invented identity.
Shape: one-time credit packs now; subscription only if renewal and entitlement are testable.
Seller role: MoR for first honest charges (we will not carry global tax this month).
Trust: buyers may not recognize the MoR; we will keep a recognized PSP application in motion once the entity is real.
Net proceeds: one typical credit-pack order run through a napkin (fees + tax reserve + dispute reserve). Sticker set after, not before.
Primary: one MoR, applied, sandbox live.
Backup: second MoR or a PSP path, application at least started; SKU map drafted.
Isolation: this product gets its own account; no sharing with a later idea.
Domestic line: off. No QR-code “just for friends.”
Mailbox / site: domain mail and live URL match the application.

Risks (≥3):
  1) Unfamiliar checkout brand increases abandonment.
  2) Category review delays the primary.
  3) Backup is a logo, not an applied account.
  4) We underprice after fees and a pessimistic dispute.

Suggestions:
  Small traffic first; abandonment reason asked in a short form.
  Read AUP before decorating the pricing page.
  Finish the backup KYC in week one, not after a freeze.
  Raise the sticker or cut a pipe that cannot support the floor.

Conclusion: Conditional pass — one applied MoR + a started backup + a napkin net.
Conditions: no real traffic until webhook acceptance is green (Chapter 7).
```

This card is a teaching sketch. It is not advice to choose any named vendor, and not a forecast of approval or conversion.

---

## Where Pipe Thinking Falsifies Itself

The “pipes are not a business” rule fails when:

- You are already a licensed seller with a finance team, and an MoR would duplicate what you must do anyway. Then a PSP may be the honest primary. The rest of the chapter — isolation, backups, net proceeds, trust — still applies.  
- The product cannot legally be sold on the pipes you can actually open. Then the smallest ship is not a clever processor. It is a pause.  
- You use “backup culture” to avoid fixing a dirty dispute rate. Two pipes with the same messy product will both choke.

---

## Takeaway

**Rule:** Pipes are not a business. Choose by buyer, entity, product shape, tax role, net proceeds, and trust. Isolate accounts. Keep a switchable backup. Never invent an identity.

**This week:** Fill a five-filter channel card. Estimate net proceeds on one typical order. Start (or finish) a backup application. Separate overseas and domestic lines.

**Not a promise:** Fee-table impressions from around October 2026, “hours to approval” stories, and platform dramas in the handbook are weather reports. Official rates, contracts, and your own review outcomes win. Nothing here guarantees approval, payout, or an unfrozen balance.


---

# Interlude — Open Source Before You Invent, and Less Lottery in the Editor

This interlude is a bench, not a second book.

Book 1 had an interlude on GitHub and search as *demand lenses*. This one is about the two disciplines that keep a smallest ship from turning into a private science fair: **compare a working implementation before you invent**, and **treat AI coding as an engineering practice rather than a slot machine**.

If you are in a hurry, steal the two checklists, then return to Chapter 7 or 9. Do not steal them as slogans and skip the webhook test.

---

## Open Source Is an Honesty Field, Not a Mood

Book 1 already asked you to fill an open-source gap on the opportunity card. Book 2 is where people “meaning to check later” write a parser anyway.

The hard rule on this desk is the one Micheal set for the whole team: **before you improve or iterate, go to GitHub (or the equivalent public record), find a comparable open project by what it actually does — not by vibes — and read it.** Stars can help you sort. They are not a blessing. Forks are a way to study a scar. They are not a command to paste.

For Thursday Packet, this field was already half-filled: libraries A and B parsed and filled the fixture; no hosted Thursday workflow shell was found. That is the only kind of “we built it” this book respects — a written difference on top of a checked field.

**What to record, in boring prose:**

- What you searched (verbs, not brand poetry).  
- What you found (repo, license, last commit recency, whether it actually runs on *your* fixture).  
- What you will reuse.  
- What you will not reuse, and why (license, mismatch, abandonware, quality).  
- The remaining gap in one sentence.

If the gap is empty, your smallest ship may be a guide, a hosted wrapper you have permission to run, or a kill. Empty gaps are a success of honesty, not a failure of creativity.

### License, again, in daylight

Prefer licenses you and counsel can live with in a product you sell. Study-only is the default for licenses that would force you into obligations you have not accepted. Reading is always allowed. Copying into a closed product “for speed” is how you buy a later problem that no webhook can fix.

Comparable commercial sites are part of the same honesty field. You are allowed to walk their mainstream path. You are not allowed to pretend you invented it, and you are not allowed to copy assets you do not own.

---

## Why AI Coding Feels Like a Lottery

A builder will say “the model is random this week.” Sometimes the model is worse than last week. More often the task was a fog.

The handbook compresses four principles that lower the lottery feeling. They are communication rules, not magic prompts.

**1. Unambiguous demand.**  
Two teammates should read the request and picture the same Thursday packet. If you want exploration, say so on purpose. Accidental fog is not “creative latitude.” It is a way to spend tokens on a cathedral.

**2. Concrete implementation details.**  
Name the API, the docs, a sample request and response, the expected behavior on a nasty client name. For interface work, give structure or a screenshot. “Make it nice” is a slot machine.

**3. One thing at a time.**  
Module-sized changes. Control the blast radius. A single session that “also just rewrites auth” is how preview credentials leak into a client bundle.

**4. Align on understanding before code.**  
Ask the model to restate the task and list the checkboxes. Correct the prose first. Code is a late instrument.

**Conclusion.** Most lottery tickets are sliced work and unclear requests. Changing models is a second-best move.

These four are also how you stay the owner. If you cannot tell whether the output is right, you did not specify a test. Fail Fast: a fixture of nasty names should fail the build when the encoding path regresses. A model that “usually works” is not a test.

---

## Commands, Skills, and UI Scaffolds Are Assets When They Are Boring

Talking to a model in a fresh chat, every time, is how teams forget what they learned on Tuesday.

| Instrument | Use | Gate |
| --- | --- | --- |
| Saved commands (a markdown recipe plus arguments, in the teaching example of a coding agent) | Repeated checks: a go-live lint, a typo pass, a sitemap peek | Version the text. Stop pasting a page-long prompt from memory. |
| Skills (multi-step flows that may call your own APIs) | Work you already did twice | Write inputs, outputs, and failure behavior. Secrets never live in a plaintext skill committed to a public repo. |
| UI generators (the handbook names a design-to-layout tool as a teaching example) | Theme experiments, a section, exported markup or notes that a local assistant then implements | The output is a prototype accelerator. It does not replace accessibility, performance, or the `curl` test. |

**Conclusion.** If you have said the same prompt three times, it wants to become an asset. “Vibe coding” becomes a practice when the practice has files.

For Thursday Packet, a saved command that runs the fixture, the `curl` promise test, and a webhook signature check will save more Thursdays than a new theme.

---

## Four Hard Rules, Applied to This Book

Micheal’s coding rules are not decoration. Here is where they land in a smallest ship:

| Rule | Landing in Book 2 |
| --- | --- |
| **YAGNI** | Do not build a future factory. Do not rewrite what the template already does. |
| **KISS** | Prefer a host to a private cluster. Prefer one obvious query to a distributed tale. |
| **Naming is design** | First-touch fields, entitlements, and credits must be searchable. Ban `data`, `temp`, `util`, `handle` as empty names. |
| **Fail Fast** | Missing secrets, bad webhook signatures, and quota edges should fail visibly. Silent `except: pass` is a bug. |
| **Open source before you invent** | Login, payment hooks, i18n, and SSR: read a mature path and a comparable site first. |

If a pull request (or your lonely commit message) cannot survive this scan, it is not “scrappy.” It is future folklore.

---

## A Ninety-Minute Bench Session (When You Are Stuck Inventing)

You do not need a full research week. You need a timed honesty pass.

**Minutes 0–15.** Write the verb you think you must invent. Search public code and two comparable sites for that verb. Save the queries.

**Minutes 15–40.** Run the best candidate on your fixture, or honestly record that you could not. Read the license.

**Minutes 40–60.** Write the gap sentence and the reuse sentence. If the gap is empty, stop the invention.

**Minutes 60–90.** If a gap remains, write a request for the next coding session using the four principles: unambiguous, concrete, one thing, a restated plan. Add one Fail Fast test to the request.

That is enough to keep Thursday Packet from becoming a third parser.

---

## Where This Interlude Falsifies Itself

Open-source honesty fails when the comparable work is in a category you must not copy (stolen data, clearly pirated assets, or a license you will not honor). Walk away.

AI-discipline fails when you use “write a precise prompt” as a way to avoid talking to a user, or when Fail Fast tests are generated by the same model and never read by a human. A test you do not understand is a costume.

The bench session fails when you extend it into a three-day framework tour (Failure Mode 2). Ninety minutes, then back to the promise.

---

## A Request You Can Reuse (Thursday-Shaped)

Here is a request that follows the four principles. Steal the shape, not the product.

```text
Task (one thing): Make the export path preserve non-ASCII client names in the
downloaded packet, using library A already in the repo.

Context: Fixture files are in fixtures/names/. Expected outputs are in
fixtures/names/expected/. Do not add an editor. Do not change auth.

Docs: link to library A’s encode API (paste a sample request/response).

Please restate: the input, the output, the files you will change, and the
test you will add. Wait for a yes before writing code.

Fail Fast: add a test that fails the build if any fixture name is corrupted.
If a required env var is missing, the command should exit non-zero.
```

If your real requests are longer than this and also vaguer, the lottery will return. If they are shorter and still vague (“fix export”), the lottery will return faster.


## Takeaway

**Rule:** Compare a working implementation before you invent. Treat AI coding as specified, sliced, tested work — not as a lottery you could win by switching models.

**This week:** Fill the honesty field for the core verb. Save one command you have already typed three times. Add one Fail Fast fixture.

**Not a promise:** A popular repository, a high star count, or a fluent assistant does not guarantee a correct entitlement or a safe license. Official docs, licenses, and your fixture win.


---

# Chapter 7 — The Entitlement Has to Land

A Thursday Packet depositor received a receipt and a cheerful “you’re in” email.

On Thursday morning she still had zero export credits. The dashboard showed a loading state that never resolved. The webhook endpoint had been pasted from a tutorial, pointed at a laptop that was closed, and subscribed to the wrong event names. In the processor’s dashboard, the payment was marked paid. In the product, nothing had happened.

The builder said, “It’s probably just a delay. We’ll hook it up properly after we restyle Checkout.”

A receipt without an entitlement is a broken product. It is also how disputes begin: the cardholder has a bank statement, you have a story, and the platform has a clock. This chapter is the operational half of payment — the triangle of product, price, and webhook; the tests that prove a renewal would work; the legal ways to reduce friction; the boring work of disputes, cancels, and trust. It is not a bag of “growth hacks.” If Chapter 6 was who the seller is, this chapter is whether you actually delivered what you sold.

---

## The Iron Triangle: Product, Price, Webhook

**Risks**

1. Products and prices exist in the dashboard, but the events that matter are not subscribed.  
2. A renewal succeeds in the pipe and never grants the next month of credits.  
3. A production failure cannot be reproduced in a sandbox, so it becomes folklore.

**Suggestions**

- **Configuration order:** keys and environment isolation first; then the event list you actually handle; then Product and Price objects (one-time versus recurring, clearly named); then Checkout or Billing in the app; then a full-path test in a sandbox.  
- **When renewals are hard to wait for:** a teaching trick in the handbook is to set a billing period to a day, buy a one-day subscription, and watch “renewal → webhook → grant” on the next calendar day. Failed events can often be replayed in the dashboard. Use official tools, not a homemade “mark paid” button that skips the pipe.  
- **Billing add-ons:** some PSP billing products charge an extra percentage. Put it in the napkin from Chapter 6 before you sell “simple monthly.”

**Conclusion.** A subscription product is not launched when the first checkout looks pretty. It is launched when **renewal day still grants the entitlement**. If you cannot test that, you have not launched. You have a button.

Thursday Packet, even if it starts with one-time credit packs, should still treat “payment succeeded → credit lands exactly once → receipt and dashboard agree” as a release test, not as a hope.

### A minimum event list (adapt names to your pipe)

Write the actual event names from your vendor next to each row. This is a job list, not a spec from any one company:

| Job | You must see it land |
| --- | --- |
| One-time payment succeeded | Credit or file access granted once; idempotent if retried |
| Payment failed | No grant; user-visible reason that does not leak internals |
| Recurring renewal succeeded (if you sell it) | Next period granted |
| Recurring failed / past due | Access policy you can state (grace or lock), plus a message |
| Refund or dispute opened | Entitlement policy you can state; evidence pack started |
| Subscription cancelled | Access ends when you said it would; no surprise charge after |

Idempotency is not optional. Webhooks retry. A retried “paid” event that grants a second credit is a bug you will only enjoy once.

Fail Fast here means: if the signature is wrong, if the environment mismatches, if the user cannot be bound, the handler should fail loudly and be replayable. Swallowing the error to “keep checkout smooth” is how the depositor ends up with a receipt and no credit.

---

## Reduce Friction Without Reducing Evidence

**Risks**

1. Removing authentication so thoroughly that stolen cards have a playground.  
2. Treating a “gray path” as the only growth plan.  
3. Copying a domestic platform’s rules onto an overseas independent site as if they were physics.

**Suggestions (legal, in-product, and bounded)**

| Move | What it can do | Boundary |
| --- | --- | --- |
| Guest checkout (price click goes to pay) | Removes a registration wall at the worst moment | The backend must still bind the session to fulfillment; abuse hooks still run |
| Auto-applied discounts | Fewer codes to mistype | Be explicit: either you attach the discount in the session, or you allow user codes — a muddy mix confuses support |
| Upsell (monthly to yearly, or a larger credit pack) | Lets a willing buyer straighten out a plan | Do not nag. Show the math honestly. |
| Cancel-retention offers in a customer portal | Keeps some people who were leaving because of a bump | Cheap coupons can pollute the quality of remaining revenue; watch that |
| “Let the platform take payment, keep delivery tiny” | A shape that shows up in some low-price virtual-goods stories on domestic platforms | Those platform rules do not travel. An overseas independent site still needs its own honest pipe |

**Conclusion.** Friction work serves conversion. It must not weaken risk controls or the evidence that you fulfilled. When you borrow a platform story, borrow the *split* (payment here, delivery there), not the numbers and not the rules.

For Thursday Packet, a guest checkout that still emails a receipt and attaches the credit to an email-verified workspace can be honest. A guest checkout that “just emails a file” with no record is a future dispute you are writing in advance.

---

## Recurring Versus One-Time Is a Shortlist, Not a Mood

**Risks:** choosing a pipe because a page said “WeChat supported,” then discovering that WeChat is one-time only; or selling a generative subscription a given MoR will not touch.

**Tick these before you decorate the pricing toggle:**

- [ ] Do we actually need recurring charges?  
- [ ] If we need a local method (WeChat, Alipay, and the like), does it support *recurring* on this pipe, after configuration, in a real test?  
- [ ] Who displays tax, and who issues the invoice — us (PSP) or the platform (MoR)?  
- [ ] Is the cancel entry visible inside the product? Hidden cancels raise disputes.  
- [ ] For high-risk recurring charges, do we have a human cancel path when the pipe flags the sale?

**Conclusion.** The billing model writes the shortlist of pipes. The shortlist then compares rates. The other way around is how you fall in love with a fee and discover a missing renewal.

---

## Disputes Are Insurance, Not an Insult

**Risks**

1. A rising dispute or “odd payment” rate leads to limits or a closed account.  
2. You lose the dispute *and* pay a fixed fee.  
3. You have no delivery evidence: no logs, no login trail, no mail, no use.

**Suggestions** (a blend of the handbook’s payment-series notes and fraud-tool notes):

1. **Show cancel, refund policy, and a contact path in the product** — the cheapest dispute is the one that becomes a cancel.  
2. **Turn on the processor’s fraud tool** (Radar is Stripe’s name; others have cousins). Use it to slow card testing and obvious theft. High-risk scores can mean a challenge (3-D Secure), a block, or a human look. Tune against false kills; a copied rule list from a blog will age and will sometimes punish good customers.  
3. **When the platform marks a recurring charge as high risk, canceling it is often cheaper than “giving the customer a chance.”**  
4. **Evidence packs:** delivery logs, login records, email, and use. Repeat offenders can go on an internal block list.  
5. **Notifications:** many dashboards default to quiet. A dispute with no alert is a dispute you will answer late.

**Conclusion.** Risk tools are the insurance premium you pay to keep the account. Not configuring them is how you run uninsured.

Thursday Packet should assume a small number of “I didn’t do it” emails even when the product is honest. The response is evidence plus a visible cancel path, not a moral essay in a ticket.

---

## Data Security Is Payment Compliance

The teaching incident in the handbook — a merchant-of-record relationship ending for good after a leak — generalizes further than one brand:

- Card numbers should stay with the processor. You should not store raw card data.  
- That is not enough. **Leaking emails, subscription IDs, and transaction metadata can still be a serious event** in a card-network’s eyes.  
- Fast repair does not guarantee a restored relationship. **A switchable pipe** is the continuity plan.  
- Architectures that “automatically expose the database as an API” and then forget the policy are a single point of failure with a pretty logo.

**Conclusion.** In a security event, the payment platform will protect itself first. Your bargaining room is usually small. Isolation and a backup, built beforehand, beat a later apology.

This is also why Thursday Packet’s preview environment cannot share production customer tables (Chapter 5). A leak in a “throwaway” branch is still a leak.

---

## Trust at Checkout Is Part of the Price

**Risks:** moving from a widely recognized checkout brand to a less familiar merchant of record, watching conversion fall, and blaming the button color.

The handbook records a questionnaire shape: among people who abandoned payment, **distrust of the payment method** showed up as a major reason. There is no honest percentage I can tattoo on your dashboard from that archive, and I will not invent one. The structural meaning is enough:

- Overseas buyers often recognize a brand like Stripe more readily. That is a hypothesis you should test, not a law of nature.  
- Fees you save can be smaller than sales you lose.  
- A new pipe should enter as a **small slice**, with a short abandonment question, and with a way to switch back.

**Conclusion.** Trust is part of conversion cost. Beside the rate card, keep an abandonment reason, not a vibe.

If Thursday Packet’s first ten honest attempts die at an unfamiliar checkout, the next move is not “add three more logos.” It is to read the reasons and, if needed, return to a recognized pipe — or stay and earn trust slowly, on purpose, with the backup already live.

---

## Do Not Replace Missing Demand With a New Pipe

Payment sits at the end of a funnel. It cannot invent a willing buyer.

| Topic | Other book | This book only says |
| --- | --- | --- |
| Channels, cold start, mail, community | Book 3’s neighborhood (traffic) | The payment page is the last mile, not the acquisition plan |
| Bids, ads, account structure | Book 3’s ads half | Forbidden or fraudulent traffic will lift disputes; risk work is shared |
| Charging, KYC, disputes, fulfillment, payout | This book | — |
| Traffic but no conversion | Journey, trust, and friction first | Do not open a fifth processor as a superstition |

**Conclusion.** Payment work serves people who already wanted to pay. It will not fix a job that never stood (Book 1) or a promise that cannot be finished once (Chapter 3).

---

## A Worked Webhook Acceptance (Composite)

```text
WEBHOOK ACCEPTANCE — Thursday Packet  date: 2026-11-10

Environment: sandbox keys only; production keys in the production host; never in Git.

Events subscribed (vendor names filled on the real card):
  payment_succeeded, payment_failed, refunded, dispute_opened.

Tests run:
  [x] Pay $X test pack → credit +1, dashboard and email match, first-touch still frozen.
  [x] Replay the same event → credit does not go +2.
  [x] Failed payment → no credit, visible message.
  [x] Refund → credit removed or marked void per the written policy.
  [ ] Recurring (deferred: we do not sell it this sprint).

Fail Fast:
  Bad signature → 4xx, alert, no grant.
  Unknown user bind → 5xx, replayable, no silent create.

Evidence:
  Delivery log line includes payment id, user id, credit delta, timestamp.

Risks (≥3):
  1) Staging webhook still pointed at a laptop.
  2) Clock skew / retry grants a double credit.
  3) Email send fails and we treat it as grant failure (or the reverse).
  4) We skip refund tests because “we would never refund.”

Suggestions:
  Host the endpoint; no laptop listeners for acceptance.
  Idempotency key = vendor event id.
  Split “grant” and “notify” so a mail outage does not roll back a correct credit without a policy.
  Refund path tested once, in daylight.

Conclusion: Conditional pass for one-time packs only.
Conditions: no live traffic until replay and refund tests are ticked; recurring stays off the page.
```

This is a teaching sketch, not a log from a real company.

---

## Where Entitlement Thinking Falsifies Itself

“The entitlement has to land” fails when:

- You sell a service that cannot be provisioned automatically (a human workshop, a custom install). Then the entitlement may be a scheduled human task with a visible status. The rule becomes “the status has to be true,” not “a script must do it.” Still test the path. Still keep evidence.  
- A legal cooling-off rule or a platform rule forces a delay before access. Then say so on the page. Instant access marketing against a required delay is a dispute factory.  
- You use perfect webhook hygiene to postpone the first test charge for months. Hygiene that never runs is another cathedral.

---

## Takeaway

**Rule:** A payment has not landed until the entitlement has landed, the dashboard agrees, and a replay cannot double-grant. Cancel paths and fraud tools are part of the product.

**This week:** Write a webhook acceptance sheet. Run pay, replay, fail, and refund tests in a sandbox. Put cancel and contact where a tired buyer can see them. If you change checkout brands, start with a slice and a question, not a full cutover.

**Not a promise:** Sandbox green does not guarantee production review, dispute outcomes, or conversion. Questionnaire shapes about checkout distrust are teaching weather, not a forecast of your abandonment rate.


---

# Chapter 8 — Where Shipping Small Breaks

Every useful method dies in characteristic ways. If you do not name those ways, “ship the smallest thing” becomes a costume for the same old cathedral — only now with a public URL.

This chapter is self-falsification on purpose. Observable delivery, clock-based selection, homepage backlogs, boring addresses, explainable infrastructure, payment assets, and entitlements can each rot. Rotten tools still look like tools. That is why they are dangerous.

Read this as red lines: conditions under which you should **stop using this method as currently practiced** — not as poetic humility at the end of a blog post.

---

## Failure Mode 1 — The Cathedral Before the Loop

**What it looks like:** a component tree for a “real editor,” a design system, a second product line, all while the sold promise is still a muted link. “We’ll launch when it’s ready.”

**Why it breaks:** the loop never starts. Deposits go stale. You learn about your taste, not about Thursday.

**Brake:** freeze work that does not make the homepage promise completable once. Put a date on the first public URL.

**Stop using the method when:** you catch yourself calling an internal demo “launched,” or when “smallest” has come to mean “we will add everything, just in a tighter font.”

---

## Failure Mode 2 — Stack Debate as Procrastination

**What it looks like:** a month of Next versus an edge family, or a sudden self-hosted cluster, while DNS and webhooks wait.

**Why it breaks:** selection stopped being a clock and became a personality. The validation window closes while you audition runtimes.

**Brake:** the selection card from Chapter 2, written, with “no migration during the sprint” as a default. Pilot new infrastructure on a non-critical site.

**Stop using the method when:** the stack conversation is longer than the go-live card.

---

## Failure Mode 3 — The Empty First HTML

**What it looks like:** a beautiful client-rendered shell; `curl` returns almost nothing; the promise lives in a script the team hopes a crawler will execute.

**Why it breaks:** you cannot claim an indexable promise. Some visitors and some reviewers will not wait for the spectacle.

**Brake:** the `curl` test is a required tick, not a suggestion. Downgrade clever empty shells during the validation window.

**Stop using the method when:** you argue that “Google will handle it” as a substitute for a first response that contains the sentence you sell.

---

## Failure Mode 4 — The Single Basket

**What it looks like:** one payment account, every product, no backup application, all revenue behind one login. Or four logos on a page that all resolve to the same untested account.

**Why it breaks:** a dispute spike, a category change, or a security event can pause the business while you still have customers to fulfill. The handbook’s termination-after-incident shape is this failure in public.

**Brake:** isolation plus a started backup plus a switch playbook written before dependency. Time-to-restore beats a souvenir rate card.

**Stop using the method when:** “we’ll apply to a second pipe after we have traction” is the entire continuity plan.

---

## Failure Mode 5 — Receipt Without Entitlement

**What it looks like:** paid in the dashboard, zero in the product. Webhooks pointed at a laptop. Retries double-grant. Refunds never tested.

**Why it breaks:** you have a billing complaint factory, and you will misread silence (or anger) as a demand problem.

**Brake:** the webhook acceptance sheet. Pay, replay, fail, refund. Recurring stays off the page until renewal-day grants are proven.

**Stop using the method when:** “we’ll hook fulfillment after we restyle Checkout” has survived more than one working session.

---

## Failure Mode 6 — Abuse Naivety

**What it looks like:** “only Google login, we’ll be fine”; gift value larger than the cost of a new account; a sudden bill; a permanent IP ban that also hits a paying customer.

**Why it breaks:** bulk accounts exist. Unbounded expensive verbs get farmed. The handbook’s roughly **$30–40** grazing bill is a small shape of a large class. Your number may be quieter, or much worse. It is not a cap.

**Brake:** behavior-level shrinking of gifts; rates on expensive verbs; watch conversion, resource use, and support together. Prefer “not worth farming” over “zero abuse forever.”

**Stop using the method when:** the expensive verb is live and the only control is hope, or when a ban hammer is your first and only tool.

---

## Failure Mode 7 — “We Are Small, So We Are Safe”

**What it looks like:** CPU climbs, visitors do not; the team shrugs (“the code got slower”). A framework CVE is treated as a newsletter item for next month. Quiet sites are used as someone else’s mine.

**Why it breaks:** attackers do not need your brand to be famous. A serious hole can become a bill, a leak, and a payment-platform event (Chapter 7).

**Brake:** when resources climb without visitors, suspect abuse or intrusion first. Inventory affected projects. Compare versions to the *current* vendor advisory — archive version numbers go stale, including any you may remember from an old post (the handbook mentions a specific patched release in one incident; do not copy that number forward as advice). **Upgrade to the stated fixed release the same day.** Then re-check CPU, logs, and the invoice curve. On a self-hosted machine, also rotate secrets and consider a rebuild. Multi-project shops should use the vendor’s batch path so one site is not left behind.

**Stop using the method when:** a serious advisory is “being monitored for a week” because the sprint is busy.

This book does **not** promise that an upgrade rolls back charges or leaves no residue. It promises a sequence that lowers the odds you will still be debating next Friday.

---

## Failure Mode 8 — Cheapest Checkout, Unknown Brand

**What it looks like:** a full cutover to a lower-fee pipe because a spreadsheet won; abandonment rises; the team blames copy; there is no way back.

**Why it breaks:** trust is part of price (Chapter 7). Fees saved can be smaller than sales lost. A questionnaire shape in the handbook — distrust of the method among people who left — is the weather report.

**Brake:** slice, ask, switch-back plan. Keep net proceeds *and* abandonment reasons in the same review.

**Stop using the method when:** rate shopping is allowed to proceed without a trust hypothesis and a rollback.

---

## Failure Mode 9 — Identity Cosplay

**What it looks like:** a form that “has to get through”; a borrowed address; a passport asked to pretend to be a local ID; names that do not match the bank.

**Why it breaks:** this is not a clever tactics chapter. It is how accounts die later, often with balances attached. This book’s veto is simple: if you cannot tell the truth on the form, stop.

**Brake:** real documents, currency alignment, official paths only. Delay is cheaper than a constructed person.

**Stop using the method when:** anyone on the team is brainstorming how to “make KYC easier” by making the answers less truthful.

---

## Failure Mode 10 — Two Countries, One Pot

**What it looks like:** a personal collection code “just for a few domestic friends,” stirred into the same product that charges overseas cards; or a second-clearing agent you have not really inspected.

**Why it breaks:** you scramble legal sellers, settlement, and risk. You also train yourself to treat pipes as a junk drawer.

**Brake:** overseas and domestic lines designed apart. Official or formal onboarding at home; no hanging codes as a business path.

**Stop using the method when:** “we take everything” is achieved by mixing pots you could not draw on a whiteboard.

---

## Failure Mode 11 — Language Theater on Day One

**What it looks like:** six language toggles, two of them empty, one of them a raw machine translation; the default language does not match who actually arrives.

**Why it breaks:** you spend clock on costumes, and you bounce the people who came.

**Brake:** English first when that is the honest market; add languages from evidence; check the default against real arrivals.

**Stop using the method when:** a translation matrix is allowed to delay the core task or the webhook test.

---

## Failure Mode 12 — Using This Book to Skip Book 1

**What it looks like:** a beautiful smallest ship of a product nobody asked for; a pre-sale skipped because “shipping will tell us”; ads bought (Book 3 daydreams) to feed a loop that has no job one-liner.

**Why it breaks:** you built a pretty instrument for silence. Observable delivery of a fake job is still a fake job.

**Brake:** require the Book 1 carry-forward pack before Chapter 9 starts. If it is missing, this book pauses.

**Stop using the method when:** “we’ll validate by shipping” is a way to avoid a priced ask you are afraid to make.

---

## A Red-Line Sheet You Can Tape to the Monitor

```text
RED LINES — Ship the Smallest Thing

[ ] We do not call a laptop demo “launched.”
[ ] We do not migrate the main site during the sprint without a written exception.
[ ] curl must show the promise.
[ ] No single payment basket; backup is an application, not a logo.
[ ] No live traffic without webhook acceptance (pay / replay / fail / refund).
[ ] Expensive verbs have a rate or a shrinking gift.
[ ] Serious CVEs are patched on the vendor’s current advice the same day.
[ ] Checkout changes start as a slice, with a way back.
[ ] No invented identity.
[ ] Domestic and overseas lines stay apart.
[ ] No language zoo in week one.
[ ] No Chapter 9 without a Book 1 verdict (or a dated reason we are only rehearsing).
```

If more than three boxes cannot be ticked, you are not “being pragmatic.” You are practicing the method in costume.

---

## Where Self-Falsification Itself Fails

A red-line chapter can rot into self-hand-wringing that never ships, or into a police ritual that never updates.

**Brake for the brakes:** if a red line is blocking a truly narrower, safer, more honest loop, write a dated exception with risks first. If a red line has not been looked at in six months, it is decoration. Review the sheet at the end of each Chapter 9 sprint, and retire lines that exist only to sound strict.

---

## How to Use This Chapter in a Review

Do not read the twelve modes as a personality quiz at the end of a long week.

Use them as a review agenda. Fifteen minutes, risks first:

1. Each person silently marks the modes they have seen in the last fourteen days.  
2. You compare lists without defense for five minutes.  
3. You pick at most two modes to brake this week.  
4. You write the brake as a tick on a card, not as a speech.

If everything is “a bit of a problem,” nothing will change. Two brakes, dated, beat a confession.

If no one can name a mode, either the team is unusually clean or the method is not being used. The second is more common. In that case, walk Chapter 1 and the red-line sheet before you open Book 3.


## Takeaway

**Rule:** Shipping small has characteristic failure modes. Name them, tape them, and stop using the costume when the ticks go missing.

**This week:** Print the red-line sheet. Walk it with one other person, or with a rubber duck. Write one dated exception if you need it — or none.

**Not a promise:** Avoiding these modes does not guarantee a calm invoice, a passed review, or a converted checkout. It lowers the odds that you will lie to yourself with a public URL.


---

# Chapter 9 — A Two-Week Ship-and-Collect Sprint

The previous chapters gave you language, cards, and red lines. This chapter gives you a calendar.

Two weeks is the default because week one wants an address and a completable promise, and week two wants a payment that grants something. You can compress to seven days if you already have a host, a domain, and a pipe in sandbox. You may not compress by skipping red lines.

The output is a dated verdict: **ship**, **shrink**, or **wait**. Not a mood. Not “we mostly launched.”

If you do not have a Book 1 carry-forward pack — job one-liner, forbidden_scope, priced promise, risk list — stop here and go back, unless you are explicitly *rehearsing* the sprint on a fictional card. Rehearsal is allowed if you label it. Pretending a rehearsal is a launch is not.

---

## Sprint Rules (Pin These)

1. **The homepage promise is the only backlog.** Later/no lists are written in public (or at least in a dated file).  
2. **Risks before conclusions** on every card you close.  
3. **Commit means deploy** to a preview or to production, as you declared on day one. No zip lifestyle.  
4. **curl must show the promise** before you invite anyone who is not a designated tester.  
5. **No live money until webhook acceptance is green** (pay, replay, fail, refund).  
6. **No stack migration** of the main site during the fourteen days, unless a written exception already existed.  
7. **Cases are not forecasts.** You will not use a handbook timer or a fee-table impression as a promise to a tester.  
8. **End with a verdict in writing**, on day 14 (or on day 7 of a compress), even if the verdict is wait.

If a rule is broken, you do not “make it up on the weekend.” You write the break, and you shrink the verdict.

---

## Days 1–2 — Carry-Forward, Boundary, Selection, Host

**Day 1 morning.** Put the Book 1 pack on the wall: job one-liner, forbidden_scope, priced promise, risks. If any of the four is mush, spend the morning tightening it. Do not open a new editor.

**Day 1 afternoon.** Fill the MVP boundary card (Chapter 3). Hero sentence in one line. Core task in one line. In / out. Three risks. Conditional pass or reject.

**Day 2.** Fill the selection card (Chapter 2) and the open-source honesty field (Interlude). Import the repo to the host. Production and preview environments named. A missing secret should already fail the boot.

Done when: a preview URL exists, even if it is ugly, and the boundary card is signed (by you, with a date).

Anti-pattern: Day 2 spent choosing typography tokens.

---

## Days 3–5 — Address, Promise on the Page, Observability

**Day 3.** Attach the domain on both sides. Forward `support@` and `contact@`. Put those addresses on the site and in any payment profile you will use.

**Day 4.** Rewrite the homepage until a tired person can repeat the broom. Put the core capability on that page, even if the rest of the nav is a “later” graveyard you hide. Policy links exist.

**Day 5.** Analytics with a **frozen first touch**. Event names from Chapter 5: landing, task start, task success or fail, checkout start, payment success or fail, entitlement granted or failed. Run `curl` and paste the hero sentence into the go-live card.

Done when: a stranger could find the promise at the canonical host, and you can see your own test of the core task in the event log — even if payment is still off.

Anti-pattern: Day 5 spent adding a second language or a demo reel of unbuilt features.

---

## Days 6–7 — Core Task Honest, Fixtures, Mid-Sprint Gate

**Day 6.** Make the core task completable once, on the host, with fixtures that include nasty names (or whatever your promise’s nasty cases are). Preview and download (or the equivalent) must come from the same result. If you cannot finish the task once, you do not have a mid-sprint product. You have a brochure.

**Day 7.** Gatekeeper review of the boundary card and the go-live card, risks first. Decide, in writing:

- **Continue to payment week** if the promise is true and visible.  
- **Shrink** if the core task is only half-true; cut scope the same day.  
- **Wait** if you discovered a Book 1 hole (the job is mush, the priced promise was theater). Waiting is a legal verdict. Shame is not required; dating it is.

A seven-day compress ends here only if payment was already sandbox-green *and* you scheduled entitlement tests in days 4–6. Otherwise a seven-day compress that “skips payment until later” is a one-week brochure.

---

## Days 8–10 — Pipe, Sandbox, Entitlement

**Day 8.** Fill the payment-channel card (Chapter 6). Five filters. Net proceeds on one typical order. Primary applied. Backup at least started. Isolation declared. Domestic line on or off, on purpose.

**Day 9.** Sandbox keys on the host. Event names filled with vendor text. Webhook endpoint public, not a laptop.

**Day 10.** Webhook acceptance sheet (Chapter 7): pay, replay, fail, refund. Recurring stays off unless renewal-day grants are also tested. Cancel and contact visible in the product.

Done when: the acceptance sheet is ticked, or the verdict has already moved to wait / shrink because the pipe cannot legally or practically be tested this window.

Anti-pattern: Day 10 spent collecting processor logos for the footer.

---

## Days 11–12 — Abuse Hook, Security Sweep, Switch Playbook

**Day 11.** Rate or shrinking gift on any expensive verb. A first pass of the fraud tool on the pipe. Notifications for disputes turned on, not left at dashboard defaults.

**Day 12.** Version check against *current* vendor advisories for the framework you actually run. Write the switch playbook: who the backup is, how SKUs map, how entitlements would point at a new event source, how you would talk to users, and what cash buffer a freeze would require. It can be one page. It cannot be “TBD.”

Done when: the red-line sheet from Chapter 8 has fewer than three empty required boxes, or the empty boxes are named as reasons to wait.

---

## Days 13–14 — Invite, Observe, Verdict

**Day 13.** Invite only the people you meant to invite. If you already took pre-sale money in Book 1, this is the week you stop hiding. Fulfill or refund; do not add a third option called “soon.” Watch events. Read mail. Do not spend the day inventing a canvas.

**Day 14.** Write the verdict.

| Verdict | You may say it when | You must also |
| --- | --- | --- |
| **Ship** | Promise is completable once at the canonical host; curl is honest; webhook acceptance is green; mailbox is read; red lines are mostly ticked | Date the known holes (support load, backup still in review, encoding fixtures still thin) |
| **Shrink** | The loop works only if you cut a lie (a feature on the homepage that is not done, a recurring toggle you cannot test) | Cut the same day; set a new date |
| **Wait** | A hard blocker: no legal pipe, a safety issue, a Book 1 hole, a serious unpatched hole, identity you will not falsify | Say what would change your mind; do not “soft wait” in public as if you had shipped |

Done when: the verdict is in a file with a date, and anyone on the team can find it.

---

## Printable Two Weeks at a Glance

| Day | Focus | Exit tick |
| ---: | --- | --- |
| 1 | Carry-forward + boundary card | Hero and core task in writing |
| 2 | Selection + honesty field + host | Preview URL, secrets fail boot |
| 3 | Domain + mailbox | Both-side bind; support@ receives |
| 4 | Homepage is the backlog | Tired person can repeat the broom |
| 5 | First touch + curl | Hero visible in first HTML; events fire |
| 6 | Core task once, honest fixtures | Preview matches delivery |
| 7 | Mid-sprint gate | Continue / shrink / wait in writing |
| 8 | Channel card + net proceeds | Primary applied; backup started |
| 9 | Webhook hosted | Vendor event names filled |
| 10 | Acceptance tests | Pay / replay / fail / refund |
| 11 | Abuse + fraud tool + alerts | Expensive verb bounded |
| 12 | CVE line + switch playbook | One-page restore plan |
| 13 | Invite and fulfill | Mail read; no “soon” third option |
| 14 | Verdict | Ship / shrink / wait, dated |

---

## Seven-Day Compress (Only If Already Warm)

Use this only if a host, a domain, and a sandbox pipe already exist, and you have run this method before.

| Day | Merge |
| ---: | --- |
| 1 | Boundary, selection, honesty, preview |
| 2 | Domain, mailbox, homepage, curl, first touch |
| 3 | Core task + mid-gate |
| 4 | Channel card + hosted webhook |
| 5 | Acceptance tests + abuse hook |
| 6 | Switch playbook + CVE line + invite |
| 7 | Verdict |

If Day 1 begins with “we still need to buy a domain,” do not compress. You are bargaining with the calendar, not shortening work.

---

## What If the Sprint “Fails”?

A wait or a shrink is not a failed character test.

It is a cheaper tax than a public lie. Write what you learned in the same tone you would write a Book 1 kill: dated, specific, without a pep talk. If you collected money you cannot fulfill, refund promptly. The sprint’s dignity is the artifact, not the launch announcement.

If the only thing you learned is “we needed two more weeks for the editor,” you probably failed the boundary card on Day 1 and then ignored it. The next sprint starts with a smaller promise, not a larger calendar.

---

## Worked Sprint Narrative (Composite Week, Not a Case Study)

The following is a teaching sketch in the same composite as Book 1’s Thursday markup export. Invented names and `example.invalid` URLs. Not a report of revenue.

**Day 1–2.** The builder tapes the job one-liner to the monitor and writes “no editor” on forbidden_scope again. The boundary card keeps: submit messy markup, preview repaired names, download a packet, one credit after payment. The selection card keeps the template shell. Parser libraries still run on the fixture. Preview URL: `https://thu-packet-preview.example.invalid`.

**Day 3–5.** Apex domain binds. `support@` forwards. The hero becomes “Get a Thursday-ready export whose client names stay readable.” `curl` shows that sentence. First touch freezes a `reddit` parameter from a test link.

**Day 6–7.** A fixture with a non-ASCII client name survives the download. Mid-sprint gate: continue, with a risk that support will see encodings not in the fixture.

**Day 8–10.** No company yet, so the channel card picks a merchant-of-record sandbox (unnamed here on purpose) and starts a second application. Napkin net proceeds on a $29 credit pack — a teaching sticker, not a recommended price — after fees and a reserve. Pay / replay / fail / refund tick green. Recurring stays off the page.

**Day 11–12.** Two free exports, then a shrink to a watermarked preview if the same path repeats too fast. Framework version checked against this week’s advisory. Switch playbook: one page, SKU map, a sentence for users if checkout changes, a note that a freeze would pause new packs.

**Day 13–14.** Three depositors from Book 1 are mailed a real URL. Two finish a packet. One refund is issued because the third’s file type was never in scope — a homepage typo, cut the same day (shrink, then ship the narrower promise). Verdict file dated: **ship, with a thinner format list and a backup still in review.**

Nothing in that sketch is a forecast of what your fourteen days will earn.

---

## FAQ (Sprint)

**Can I start Week 2 first because payment is scary?**  
You can rehearse a sandbox, but you may not take live money for a promise that is not completable once. Fear of payment is not a reason to polish a cathedral.

**What if a depositor wants the editor after all?**  
It stays on later/no unless you rewrite the job one-liner and treat that as a new demand event. Price is not a hall pass.

**What if the backup pipe is still in review on Day 14?**  
You may still ship on the primary if the switch playbook is written and the risk is named. You may not pretend the backup exists.

**What if curl is clean and nobody comes?**  
That is a traffic or demand question (Book 1 or Book 3), not a reason to add features on Day 13. Record it. Do not decorate.

**What if we can only work nights?**  
Keep the order; stretch calendar dates, not the ticks. A “two-week” sprint that takes eighteen calendar days is still a two-week sprint if the ticks are honest. A fourteen-day calendar with half the ticks is not.

---

## Sprint Anti-Patterns (Quick List)

- Renaming the repo instead of attaching DNS.  
- Four processor logos, zero refund tests.  
- “Temporary” production data in preview.  
- A language toggle with empty files.  
- Buying ads on Day 5 to “have something to look at.”  
- A mid-sprint migration “while we wait for KYC.”  
- Calling a shrink a ship in a launch post.  
- Inventing a KYC story because the calendar is tight.

---

## After the Verdict — File Hygiene

Keep, in one folder:

- Boundary, selection, address, channel, webhook, switch, go-live cards (dated).  
- The verdict paragraph.  
- A short list of holes you already admitted.  
- The Book 1 pack, unchanged unless the job itself changed.

If the verdict is ship, Book 3 — *Buy Time, Not PMF* — is allowed to talk about channels and buying time. It is not allowed to become a way to paper over a core task that still fails on Thursdays.

If the verdict is wait or shrink, Book 3 will not save you. Stay here, or return to Book 1 if the job itself dissolved.

---

## Bridge to Book 3: *Buy Time, Not PMF*

Book 2 ends when a stranger can finish the promise once, and when money — test or real — can complete the loop without mythology.

Book 3 starts where builders get noisy: channels, ads, the temptation to treat a click-through rate as product-market fit. It will argue that you should own one or two channels, and that ads buy time, not a verdict on the job.

If you catch yourself buying traffic on Day 5 of this sprint, you are reading Book 3 fanfiction inside a Book 2 calendar. Close the ad tab. Open the go-live card.

### What to carry forward unchanged

- Risks before conclusions.  
- Cases as shapes, not prophecies.  
- Forbidden scope as a living document.  
- Payment as an asset with a switch plan.  
- Launch as feedback, not a graduation gift.

### What Book 3 will challenge

Attention must be bought or earned without mistaking it for a product that works. Time can be purchased. Fit cannot. The next book is about that distinction. It is not a license to reopen the cathedral.

---

## One Page You Could Tape Above the Monitor

```text
SHIP-AND-COLLECT
Promise (one sentence):
Core task (once):
curl shows the promise: yes / no
Webhook acceptance (pay/replay/fail/refund): yes / no
Mailbox read: yes / no
Backup pipe: applied / started / absent (name the risk)
Red lines missing:
Verdict (day 14): ship / shrink / wait
Date:
```

---

## Takeaway

**Rule:** Two weeks, one promise, one completable task, one tested entitlement, one written verdict. Shrink and wait are adult results.

**This week (or these two):** Run the calendar in order. Pin the eight sprint rules. Do not buy traffic as a substitute for ticks.

**Not a promise:** A finished sprint does not guarantee users, approval, or net proceeds. The composite Thursday narrative is a teaching sketch, not a scoreboard you should try to hit.


---

# Appendix — Closing Toolkit (Worked Templates)

Blank templates live in `templates/`. Blanks are not enough on a bad Wednesday. This appendix shows **filled composites** — teaching sketches, not case-study promises, not vendor recommendations, not revenue forecasts.

Use them to see density: what “enough” looks like before you call a loop live.

Filled examples use invented `example.invalid` URLs and the same Thursday Packet composite as Book 1. They are **not** reports of a real company’s revenue, ranking, conversion, or approval times.

---

## A. Filled MVP Boundary Card

```text
MVP BOUNDARY — Thursday Packet  date: 2026-11-10

Homepage promise (one sentence):
  Get a Thursday-ready export whose client names stay readable.

Core task (once, no video call):
  User submits a messy markup file → sees a preview of repaired names
  → downloads a packet → (if paid) one credit is used and shown.

In for the two-week window:
  - Promise sentence and short how-it-works
  - Fixture-tested encoding path
  - Google login + optional guest start
  - Domain, mailbox, analytics with first-touch bind
  - Test payment → webhook → export credit
  - Visible cancel / refund contact
  - Terms and privacy links

Out (forbidden or later):
  - New editor canvas
  - Comment threads
  - AI rewrite of client comments
  - Team permissions beyond “one owner, one workspace”
  - Multi-language UI
  - Second processor logo “for trust”

Risks (≥3):
  1) Preview lies (looks fixed, download is not).
  2) Credit decrements twice, or never.
  3) Support load from encodings not in the fixture.
  4) Homepage still talks like a workspace suite.

Suggestions:
  Preview must be generated from the same bytes as the download.
  Webhook acceptance sheet before any real charge.
  Expand fixtures weekly; do not pretend completeness.
  Rewrite the hero until a tired person can repeat the broom.

Conclusion: Conditional pass.
Conditions: preview/download parity test; entitlement test; hero rewrite before traffic.
```

---

## B. Filled Go-Live Checklist

```text
GO-LIVE — Thursday Packet  date: 2026-11-10

Demand carry-forward:
  [x] Job one-liner taped
  [x] forbidden_scope includes “no new editor”
  [x] Priced promise matches the hero
  [x] Book 1 risks still visible

Address:
  [x] Git → host on a named production branch
  [x] Preview and production secrets isolated; boot fails if missing
  [x] Canonical host + www redirect
  [x] support@ and contact@ receive a test message
  [x] curl shows the hero sentence

Observability:
  [x] First touch frozen on first meaningful visit
  [x] Events: land, start, success/fail, checkout, pay, entitle

Promise:
  [x] Core task completed once on the host
  [x] Fixture includes non-ASCII names
  [x] Preview matches download bytes

Payment (sandbox → live only after ticks):
  [x] Channel card filled; net proceeds napkin attached
  [x] Backup application started
  [x] Webhook acceptance: pay / replay / fail / refund
  [x] Cancel and contact visible
  [ ] Recurring (off this sprint)

Safety:
  [x] Expensive verb has a shrinking gift
  [x] Framework version checked against this week’s advisory
  [x] Switch playbook: one page
  [x] Red-line sheet: fewer than three required boxes empty

Gatekeeper:
  Risks: (1) backup still in review (2) thin file-type list (3) support load
  Suggestions: name backup risk in the verdict; cut file types on the homepage today
  Conclusion: Conditional ship
```

---

## C. Filled Payment-Channel Card

```text
PAYMENT CHANNEL CARD — Thursday Packet  date: 2026-11-10

Buyer: overseas design-ops leads, cards, English checkout.
Entity: none yet; no invented identity.
Shape: one-time credit packs now; subscription off until renewal tests exist.
Seller role: MoR for first honest charges.
Trust: MoR may be unfamiliar; recognized PSP application in motion once an entity is real.
Net proceeds: typical pack run through a napkin (fees + tax reserve + dispute reserve).
  Teaching sticker used in the napkin: $29. Not a recommended price.
Primary: one MoR, applied, sandbox live.
Backup: second application started; SKU map drafted.
Isolation: this product, this account.
Domestic line: off.
Mailbox / site: domain mail and live URL match the application.

Risks (≥3):
  1) Unfamiliar checkout brand increases abandonment.
  2) Category review delays the primary.
  3) Backup is not yet approved.
  4) Sticker too low after reserves.

Suggestions:
  Small invite first; short abandonment question.
  Read AUP before decorating the page.
  Do not treat the backup as live.
  Revisit sticker after the napkin, not after a competitor’s homepage.

Conclusion: Conditional pass for sandbox; live charges only after Chapter 7 ticks.
```

---

## D. Filled Webhook Acceptance

```text
WEBHOOK ACCEPTANCE — Thursday Packet  date: 2026-11-10

Environment: sandbox keys on the host; production keys only in production; never in Git.

Jobs tested (vendor event names to be filled on a real card):
  [x] payment_succeeded → credit +1; dashboard and email match; first-touch still frozen
  [x] replay same event → credit does not go +2
  [x] payment_failed → no credit; visible message
  [x] refunded → credit void per written policy
  [ ] recurring (off)

Fail Fast:
  Bad signature → 4xx, alert, no grant
  Unknown bind → 5xx, replayable, no silent user-create

Evidence:
  Log line: payment id, user id, credit delta, timestamp

Risks (≥3): laptop listeners; double grant on retry; mail outage confused with grant failure; refund path untested
Suggestions: hosted endpoint; event-id idempotency; split grant and notify
Conclusion: Conditional pass for one-time packs
```

---

## E. Filled Switch Playbook (One Page)

```text
SWITCH PLAYBOOK — Thursday Packet  date: 2026-11-10

If primary becomes unable to charge:
  1) Flip the pricing page to the backup once it is actually approved.
  2) Map SKU “pack-10” to the backup’s price id (table lives in this repo).
  3) Point entitlement code at the backup’s event names (adapter already sketched).
  4) Existing unused credits remain in our database; we do not ‘migrate money.’
  5) Mail template: “Checkout provider changed; your credits are unchanged; you may need to pay with a new card for the next pack.”
  6) Cash buffer: we can fulfill already-sold packs without new charges for N days
     (N filled from a real napkin, not a hope).

Risks (≥3): backup still in review; subscription (if later added) may not port; users drop at a new brand
Suggestions: keep packs one-time until this is rehearsed; do not market a brand we might leave
Conclusion: Plan is usable as a shrink-and-continue script, not as a promise of 48-hour recovery.
```

---

## F. Filled Mid-Sprint and Day-14 Verdicts (Short Forms)

```text
DAY-7 MID-GATE — 2026-11-16
Risks: fixture coverage thin; hero still slightly “workspace-ish”; mailbox not yet used in the payment profile
Suggestions: add two fixtures; cut the leftover suite language; update the profile today
Conclusion: Continue to payment week, conditional on the three suggestions same day.

DAY-14 VERDICT — 2026-11-23
Risks: backup in review; one refund issued after a typo in supported file types; support may be spiky on encodings
Suggestions: homepage file-type list cut; backup risk named in the ship note; fixture folder grows weekly
Conclusion: SHIP the narrower promise. Not a wait. Not a quiet “soft launch” of the typo.
```

---

## G. Gatekeeper Review Block (Copy)

```text
【Risks / holes】(≥3, write first)
1. …
2. …
3. …

【Suggestions】
- …

【Conclusion】
- Pass / Conditional pass / Reject / Ship / Shrink / Wait
- Conditions (if any):
```

---


## G2. Filled Selection and Address Cards

```text
SELECTION CARD — Thursday Packet  date: 2026-11-10

What must be observable in 14 days?
  Stranger reads the hero, finishes one encoding-safe packet,
  we see the event, a test payment grants one credit.

Template or build? Template shell; difference = opinionated export path.
Stack match? Stay on the template’s hosted default. No sprint migration.
Self-host? No.
Open-source honesty? Libs A/B run on the fixture; we host the workflow.

Risks (≥3): theme fights the promise; encoding support load; migration daydream; license lock-in
Suggestions: time-box theme surgery; fixture boot test; “no migration” on the wall; read the license
Conclusion: Conditional pass — template shell + hosted default
```

```text
ADDRESS CARD — Thursday Packet  date: 2026-11-10

Git → host: production branch deploys on push.
Domains: canonical apex + www redirect.
Mailbox: support@ and contact@ forward, and are read.
curl: hero sentence visible in the first HTML.
Env: preview isolated; boot fails if secrets are missing.

Risks (≥3): DNS edits drop mail records; curl skipped; reviewer mail unread; preview shares production files
Suggestions: screenshot the zone; curl is a required tick; page the inbox; separate buckets
Conclusion: Conditional pass when curl, mailbox, and isolation are green
```

---

## H. How This Appendix Relates to Book 3

If your verdict is **ship**, carry forward: the completable promise, the event names (especially first touch), the channel card, the switch playbook, and the hole list. Book 3 — *Buy Time, Not PMF* — starts at channels and at the temptation to treat clicks as fit. It does not reopen the cathedral because traffic feels lonely.

If your verdict is **shrink** or **wait**, this appendix’s value is operational and emotional: you have artifacts that prove you worked like an adult. That dignity is the product of Book 2 even when the public URL is not yet a business.

---

## I. Explicit Perimeter (Again)

Filled examples use invented `example.invalid` URLs and composite language. They are **not** reports of a real company’s revenue, ranking, conversion, approval, or payout.

Handbook figures cited elsewhere in the book — template launch clocks, a roughly $30–40 abuse bill, fee-table impressions from around October 2026, questionnaire shapes, platform dramas — remain teaching cases only.

No ticked card guarantees income. A complete toolkit only raises the odds you will refuse a cathedral, and refuse a pipe mythology, before either becomes your week.
