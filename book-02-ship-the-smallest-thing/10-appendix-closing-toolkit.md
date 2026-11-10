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
