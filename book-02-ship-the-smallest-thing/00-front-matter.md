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
