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
