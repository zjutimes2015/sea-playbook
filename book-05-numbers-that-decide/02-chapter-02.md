# Chapter 2 — Instrument First, Then Argue

The Thursday Packet builder did what tired operators do when a chart looks late: they held a meeting about the meeting.

One person said paid search was dead, because they could not see it. One person said the typography-and-exports room was still the only real channel, because the last honest yes had come from there. One person said `/repair` was a bounce trap, because a weekly average said so. Nobody could open a property that had been verified on the launch day, because the launch day had been about typography, exports, and a payment pipe. Analytics was “the kind of thing you add when there is volume.”

There was still no volume to brag about. There was already enough traffic to argue about. The argument had no instruments. It had opinions, screenshots from an ads tab that had barely been used, and a fear that silence meant the page was failing.

This chapter exists to end that kind of argument, or at least to postpone it until a stack is in place. Connecting data is not an advanced move. It is the start of the week. Optimization debates without data are metaphysics. Data, once connected, is still not cause. It is a slower, better argument.

---

## What “Instrument First” Means

Instrument first means the live site can be seen from more than one honest angle on the day it is allowed to meet a stranger — not the day a committee decides the traffic is “worth measuring.”

The default stack in the source handbook, aimed at English-first overseas sites, has four complementary views plus two money-aware additions:

| Tool | The view it gives you | What goes blind if you skip it |
| --- | --- | --- |
| **Search Console** | Indexing, queries, impressions, clicks, a rough position | You cannot tell a search problem from a page problem |
| **GA4** (or the event-based analytics you actually use) | Source, pages, events, retention, exploration | You have no funnel and no comparison that can stand |
| **Plausible** (optional) | A lighter, often more privacy-forward count | Not required; useful as a companion or a compliance choice |
| **Clarity** (or an equivalent recording tool) | Recordings, click and scroll maps, a first-pass assistant | You know that people left, not *how* they left |
| **First-party events** | Named business actions you defined | You are guessing at value from page views |
| **Stripe or the ledger** (when you charge) | Where money actually came from, by country and amount | You will let a platform’s conversion column play accountant |

These tools do not replace one another. Search Console is not GA4. GA4 is not a recording. A recording is not a ledger. When the counts disagree — and they will — the failure is often the expectation, not the vendor.

### Why the numbers will not match

Each tool filters the world differently. Sampling, bot rules, consent, ad blockers, definition of a session, and attribution windows all cut the pie on a different bias. A team that spends Friday trying to make four totals identical is not doing analytics. It is doing theology.

The usable habit is simpler: trust **trends inside one tool**, and **cross-checks across tools**, not the dream of one absolute headcount. If GA4 says the repair-complete event fell for two weeks, and the recordings on `/repair` show a new button that does not look like a button, you have a lead. If the ads platform and the ledger disagree by a wide margin, you have a homework assignment, not a license to pick the flattering table.

---

## Install on the Launch Day (Not on the Famous Day)

The veto is blunt. If Search Console and analytics are not connected, you may not claim that “SEO is not working” or that “ads are not working.” You cannot yet tell indexing from clicking, clicking from on-site loss, or on-site loss from a bid.

A second veto sits beside it. Do not promise that “installing the stack will grow the site.” The stack reduces the chance that you will argue in the dark. It does not invent demand, and it does not finish a Thursday.

### A practical install order

Do this on the day the URL is allowed to be public, or the next morning if the launch night was already too long:

1. Verify the domain in Search Console (and in Bing Webmaster if that market matters).  
2. Place the GA4 tag, or your chosen analytics tag, on every page that can matter, including the payment success page.  
3. Place Clarity, or the recording tool you will actually watch, on the same pages.  
4. Add Plausible if your market, your ethics, or your curiosity wants a second, lighter count.  
5. Confirm, with a real visit from a real browser, that something appears in a realtime or debug view.

If a teammate asks an assistant to paste official snippets into the document head, that can be a speed aid. It is not acceptance. Acceptance is a realtime event you can point at, a recording you can play, and, later, a report that still contains the event after the processing delay you were told to expect.

Thursday Packet’s early mistake was ordinary. The `/repair` form worked. The payment pipe worked. The tag was “on the list.” The list was not the site. When the first search visits arrived, the room could see typography, and it could see a receipt, and it could not see the path between them.

---

## What This Stack Can Answer (and What It Cannot)

Use the stack as a speed bump and a magnifying glass, not as an engine.

It can often answer:

- Which step loses the most people.
- Which kind of channel keeps people longer, or brings them back.
- Whether someone is clicking a region that is not a control.
- Which queries already show you, but have no page that finishes the job.
- Which countries actually pay, once a ledger exists.

It cannot, by itself, answer:

- Whether this product should exist. That is still Book 1.  
- Perfect multi-touch causality. Chapter 5 will give you a “good enough” rule, not physics.  
- How much a copy change will raise conversion. You can test; you cannot prophesy.  
- The engineering detail of why a URL is not indexed. That still belongs to Book 4.  
- Which payment method or fee schedule you should choose. That still belongs to Book 2’s payment work.

If a meeting asks the dashboard to choose a product, fire the meeting, not the product. If a meeting asks the dashboard to guarantee a lift, fire the guarantee.

---

## GA4’s Job in This Stack

In this book, GA4 (or an event-based cousin) is not a hit counter. Its value is the event: a named thing a person did that you cared enough to record.

Official recommended events are a starting vocabulary. They are not your product. “Generate succeeded,” “export downloaded,” “repair previewed,” and “payment succeeded with a transaction id” are the kinds of names Thursday Packet actually needs. Chapter 3 will design those names and the acceptance test. This chapter only places the tool in the stack and warns against two opposite errors.

The first error is to collect only page views and then invent a conversion in a slide. The second is to collect every click and then drown. Event inflation is how a site becomes unreadable to itself.

If your market or your conscience prefers a lighter tool as the daily counter, use it. Do not use the preference as a reason to skip events on the path that takes money. A privacy-forward count of visits plus a carefully chosen, consented event on payment is often more honest than a lavish property nobody trusts.

---

## A Worked Install (Composite)

On a Tuesday, the Thursday Packet builder finally verified the domain, placed the tags, and walked the path by hand:

1. Opened `/repair` from a clean browser.  
2. Uploaded a messy markup file.  
3. Watched the preview name list appear.  
4. Exported the Thursday-ready file.  
5. Paid the test amount on the live pipe, then refunded it.  
6. Opened the debug or realtime view and looked for the events by name.  
7. Opened Clarity and confirmed that the session existed, and that the names on the screen were not a client’s real names from a production file they should not have used.

Two failures showed up immediately, which is the point of an install week rather than a shame week.

The payment success event fired, but it had no transaction id, so the ledger and the analytics property could not be joined later. The export event fired twice, because a front-end effect had run twice. Neither failure meant “analytics is unreliable.” Both meant “the contract is not accepted.” They fixed the id and the double-fire before anyone was allowed to hold a strategy meeting.

That is the standard. Code merged is not data usable.

---

## Where This Framing Falsifies Itself

**Some internal tools should not be fully instrumented in a third-party cloud.** A page that displays other people’s documents may need a tighter privacy design than a marketing homepage. Consent, data-retention settings, and a rule that recordings are masked or disabled on sensitive surfaces are part of instrumentation, not a reason to skip it entirely. You can still count a consented, named event — “export completed” — without recording a client’s file.

**A tiny static site with one email link may not need the full suite on day one.** If the entire product is a single page and a mailbox, Search Console plus a simple counter may be enough until a path exists. The moment you have a preview, an account, or a payment, the exception expires.

**Regulatory requirements can change the default tools.** If you serve a market that objects to a vendor, you may lead with a lighter, more local, or more privacy-forward option. The principle stands: instrument before you argue. The logo on the tag can change. Official legal advice, which this book is not, wins.

**A mature team may already have a warehouse.** Good. This book will not tell you to abandon it for a cute four-tile stack. It will tell you that a warehouse without accepted events and a written verdict is still a filing cabinet, only more expensive.

---

## Handoffs This Chapter Refuses to Steal

- How you buy traffic, and how a campaign is structured, remains Book 3.  
- How a query is chosen, and how a crawler is allowed to finish, remains Book 4.  
- How the first-touch field is stored in your own database is engineering work from Book 2’s discipline: do it, and do not overwrite first touch on every session.  
- How a payment method is chosen remains a payment problem.

This chapter only demands that the mirrors exist, that you expect them to disagree, and that you stop holding strategy meetings in a dark room.

---

## Takeaway

**Rule:** Connecting the stack is the start of the argument, not the prize at the end of a growth story.

**This week:** Verify Search Console, place analytics and recordings on the live path, and walk the path once until a realtime view agrees that you were there. Do not declare a channel dead before that walk exists.
