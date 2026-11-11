# Chapter 7 — Tracking Has to Accept the Truth

A Thursday Packet test ad, had it been allowed to run on hope, would have reported a cheerful click-through rate and a “conversion” that was actually a visit to the homepage.

The builder had pasted a basic tag, ticked a box that said sign-up, and left purchase without a value or a currency. The ads account, had it been switched to automated bidding, would have learned to buy cheap doorbells. The analytics view would have argued with the ads view, and the meeting would have been about which dashboard to trust, instead of about whether anyone had paid for a clean export.

Paid acquisition without tracking is not a clock. It is a fog machine. This chapter is the acceptance test: what counts as success, which words you buy, how you read the search-term report, when you may hand bidding to a system, and how you survive empty days without throwing the lesson away.

---

## Tell the System What Success Is

**Risks**

1. Tracking only the click, then optimizing for more clicks.  
2. Recording a purchase with no value and no currency, so the system cannot tell a nine-dollar export from a ninety-dollar accident.  
3. Reversing primary and secondary actions, so a sign-up outranks a payment, and the account learns to harvest emails.

**Suggestion — three layers, in order.**

1. **On the site**, send the events you actually mean. At minimum, a registration or sign-up, and a purchase. **Purchase must carry a value and a currency.** Without those, you cannot learn whether a sale was worth buying, and you cannot later ask a system to maximize value.  
2. **In analytics**, keep purchase as a key event. If sign-up is useful, mark it as key on purpose, as a helper, not as a replacement.  
3. **In the ads account**, make **purchase the primary** action. Keep **sign-up secondary**. Mixed primacy is how an account becomes an expensive newsletter pump.

UTM marks on the landing address are not decoration. They are how first touch, from Book 2, stays bound to a campaign you can name in a sentence.

**Conclusion.** If you cannot say what success is in a tag, you are not ready to buy a clock.

---

## A Tracking-Acceptance Sheet (The Gate Before Spend)

Treat this like Book 2’s webhook acceptance. Hope is not a test.

```text
TRACKING ACCEPTANCE — Thursday Packet

[ ] First touch still readable (source / medium / campaign)
[ ] Sign-up event fires once, and only once, for a real sign-up
[ ] Purchase event fires on a real or sandbox payment
[ ] Purchase includes value and currency
[ ] A failed or canceled payment does not record as purchase
[ ] Analytics lists purchase as key; sign-up is helper if used
[ ] Ads account: purchase primary, sign-up secondary
[ ] A test click with a UTM arrives and is visible end to end
[ ] Reddit (or other community) ads, if used, have their own
    UTM and are not blended into “google / cpc” folklore

Pay / replay / fail (yes, the same verbs):
  record a test purchase, replay the event, then a refund or
  a fail, and confirm the system did not learn the wrong story.

Risks still open:
  1)
  2)
  3)

Conclusion: Pass / Conditional pass / Reject
```

If this sheet is red, Chapter 6’s card is not allowed to go green. That is not bureaucracy. That is how you refuse to teach a system a lie.

---

## Words: Stand Where the User Stands

Keyword work in paid search is close cousin to keyword work in SEO, with one rude difference: you pay immediately.

**First principle, from the handbook, kept in one line:** stand in the user’s shoes. How would they search? The more specific the phrase, the closer it is to “I need this now.”

A teaching contrast: for an AI video job, a phrase like “text to video ai generator” is a different object than the trophy “ai video.” The second is larger and messier. It will spend. It may not spend on the job you think you sell.

Thursday Packet should be equally unromantic. People in pain type things like garbled names, encoding, client lists, and Thursday handoffs. They rarely type the builder’s category fantasy.

**Risks**

1. Buying the category trophy because it sounds like the industry.  
2. Looking at volumes for the wrong geography.  
3. Never opening the search-term report, so budget leaks into polite irrelevance.

**Suggestion.** Use the official keyword planner with the **actual countries** you will bid in. New accounts often see coarse ranges at first; more precise figures may arrive after a short stretch of real activity — a limitation, not a slight. A rough three-way split is useful: tiny volume may belong to later organic work; moderate, intent-heavy volume is a cold-start friend; huge volume is a late, careful test or a thing you refuse.

Competitive tools that map “sites buying a phrase” and “phrases a site buys” can widen a candidate list. They estimate. They do not invoice your account. If a campaign cannot move, look first at whether the phrase pool is too narrow or too vain, before you simply raise bids.

After spend begins, the **search-term report** is the adult conversation. Negate the irrelevant and the hopeless. Raise or isolate the phrases that produce a finished job at a cost you can stand. Leaving the report unopened is how a ceiling disappears into almost-related curiosity.

**Conclusion.** Buy intent, then audit what you actually bought. Volume without intent is a trophy you pay rent on.

---

## Intelligence Without a Teacher Is a Blind Flight

Automated bidding and conversion goals are not magic. They are a student. If you give them no real purchases, or the wrong primary action, they will study the wrong exam.

**Rhythm.**

- Early: clicks, or a looser goal, while you collect real sign-ups and purchases from more than one human.  
- After evidence: conversion count or conversion value, and then automated bidding if you want that help.  
- **No evidence plus automated bidding is a blind flight.**

The handbook’s “about five distinct purchasing users” before a gradual switch is a teaching threshold, not a sacrament. What you must not do is switch after one friendly card, or after a week of doorbells, and then blame the system for learning doorbells.

---

## Empty Days, and the Stop Rule You Write While Calm

Paid results are not a straight line. The most expensive habit in a first campaign is to kill it in the first quiet stretch, after you have paid the tuition and before you have collected the lesson.

That is not an argument for endless spend. It is an argument for **writing the stop rule while you are calm**.

A usable rule names:

- A ceiling (daily and fortnightly) you will not exceed while learning.  
- What you will inspect on an empty day: tracking first, then phrases, then the landing journey — not your character.  
- What “stop” means: pause, shrink, switch the phrase pool, or fix the journey, with a date.  
- What “panic” means, so you can recognize it: doubling the budget at midnight, or zeroing it because a dashboard felt humiliating.

If the journey is known to leak, the empty days are not a learning period. They are you buying a leak. Stop and fix the journey. Book 3 does not give you a poem to avoid Book 2’s unfinished work, or Book 5’s later stop-and-scale craft. It only refuses mood as a policy.

---

## Do Not Blend Rooms

A Google search click and a Reddit ads click can share a UTM discipline and still be different animals. The first often arrives with a query. The second often arrives with a mood, a curiosity, or a community habit. The unsent-letter recap in Chapters 1 and 6 is the teaching stain: a good click-through rate, a reached pay wall, no orders.

**Suggestion.** Separate campaigns, separate UTMs, separate verdicts. Do not average them into “our paid CAC.” Do not export a conclusion from one room into the other without a new test.

Thursday Packet, in particular, should be suspicious of rooms that love typography as an aesthetic and indifferent to Thursday as a deadline. Adjacent pain is not the job.

---

## Hygiene Tools, Used as Mirrors, Not as Oracles

The Interlude will walk the official ads transparency center, title monitors, and related mirrors in more detail. Here, only the rule: use them to see **whether someone is actually paying to stand on a phrase or a site**. That is a real-behavior signal. It is not a reason to copy a headline, a bid, or a business.

Open-source diagnostic helpers exist — the handbook mentions a public “ads doctor” style skill used to review exports and health scores. A doctor is not a pilot. Official documentation and your own conversion log still win.

---

## Where Tracking Theater Falsifies Itself

This chapter can rot into a new cathedral: a month of tagging, consent banners, and perfect data plans, and no primary channel, and no honest ask.

It fails when “not ready to spend” is a permanent personality, even after the sheet is green.

It fails when value is faked — a placeholder amount that makes dashboards feel serious — and a system learns a novel.

It fails when stop rules are written after the panic, which is to say not written.

It fails when a team uses tracking complexity to avoid looking at the first screen of the journey, which a user already told them was confusing.

---

## A Worked Phrase Shortlist (Composite)

Thursday Packet, if it ever bids, should look like a person in pain, not like a category deck.

**Closer to the job (candidates, not a bought list):**

- phrases around client names breaking in an export  
- non-ASCII or “weird characters” in a package or a handoff file  
- Thursday (or weekly) production export repair  
- encoding or mojibake in a client list  

**Farther, to be treated as suspects:**

- “AI design tools”  
- generic “design workspace” or “all-in-one editor”  
- adjacent emotional jobs (apology letters, typography-as-hobby) that produced clicks in Chapter 1’s warning shape  

After spend, a search-term report might show polite cousins: a query about fonts, a query about a competitor’s full editor, a query about “free name generator.” Those are not insults. They are invitations to **negate**, or to discover that your landing sentence is attracting the wrong broom. Raising the bid on a cousin because it is cheaper is how a ceiling becomes a font seminar.

**Value-parameter mistakes to run as tests, not as folklore:**

- a purchase of 0.00 because a trial or a coupon zeroed the value  
- a currency that does not match the price the buyer saw  
- tax included in one event and excluded in another, so the system learns a wobble  
- a duplicate fire on thank-you page reloads  

Any of these can be more expensive than a typo in a headline, because they teach. Green them on the acceptance sheet with a real sandbox pass, including a refund.

Community campaigns, if they appear later, get their own shortlist and their own UTM. Do not paste this search shortlist into a Reddit targeting box and call it consistency. It is not consistent. It is lazy.

## Takeaway

**Rule:** A clock without a truthful purchase event is a fog machine. Intent first, then volume. Write the stop rule while you are calm.

**This week:** Green a tracking-acceptance sheet. Audit words in the geography you will actually bid in. Keep rooms unblended.

**Not a promise:** Planner ranges, “about five purchasers,” and any tool-estimated volumes are teaching aids, not a contract with the auction.
