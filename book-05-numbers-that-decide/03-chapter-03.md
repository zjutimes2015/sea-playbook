# Chapter 3 — Events You Can Defend

The first report looked busy.

Thursday Packet now had a property, a realtime view, and a long list of names that had seemed harmless at midnight: `click_logo`, `click_footer`, `hover_preview`, `scroll_25`, `scroll_50`, `scroll_75`, `scroll_90`, `tab_hidden`, `tab_visible`, and a general `click` with a parameter for whatever the pointer had been near. Buried among them, sometimes, was `export_done`. Buried more rarely was a payment event without an id.

The builder opened a weekly exploration and could not answer a plain question: how many strangers had finished a repair and then paid? The report could answer how often the logo had been clicked. The logo had not been the product.

This chapter is the contract. Events are not a pile of telemetry. They are the terms under which later reports are allowed to speak. If the terms are vague, every later meeting is a dispute.

---

## Three Kinds of Events Worth Recording

Most products, including Thursday Packet, need fewer events than a tag-manager gallery will offer. Three families are enough to start, and enough to defend.

**Core-value events** name the moment the product did the job. For Thursday Packet, that is not “landed on `/repair`.” It is “preview rendered with repaired names,” or “Thursday-ready export downloaded.” These events are the ones you later sit beside retention. Did the people who finished the job come back? Did the people who only wandered leave for good?

**Path events** name the steps toward money or toward a serious yes. Registration started, registration finished, payment clicked, payment succeeded. These are the raw material of the funnel in Chapter 4. If you skip them, you will invent the break from memory.

**Intent events** name a signal that is not yet a conversion but is stronger than a page view: opened pricing, started an advanced option, asked to export, returned to an old project. These help you split people in Chapter 5. They are easy to overgrow. Add them when a question exists, not when a vendor checklist looks empty.

A fourth family is tempting and usually rejected here: decorative motion. Logo clicks, decorative hovers, and a scroll percentage on every marketing page will make a property look alive. They will also hide the three families you actually need. If a decorative event cannot change a Tuesday decision, it does not belong in the weekly contract. You can still log it in a side stream if engineering has a reason. It does not get a seat at the retrospective.

### Named examples, not a schema religion

Thursday Packet’s defended list, after the cleanup, fit on an index card:

- `repair_preview_ready` — core value; parameters: file type, count of names repaired (never the names themselves).  
- `repair_export_done` — core value.  
- `checkout_started` — path.  
- `purchase_succeeded` — path; parameter: `transaction_id`.  
- `pricing_viewed` — intent.

That is five. Five can be analyzed. Fifty cannot, not by a one-person company on a Thursday.

If your product is a generator, an analyzer, or an uploader, the core-value name will change and the pattern will not: success of the job, not contact with the page.

---

## The Acceptance Test (“Shipped” Is Not “Usable”)

The technical motion is ordinary. At the right moment, your page sends a named event with a small set of parameters. In a common Google tag setup, that call looks like a function with an event name and a payload. The official documents will move. Your acceptance test should not depend on a blog snippet remaining true.

Call an event **accepted** only when all of the following are true:

1. A debug or realtime view shows the event name when you perform the action.  
2. The parameters that later decisions will need are present and not empty — especially anything that must join to a payment.  
3. A successful payment can be matched to the ledger by a transaction id. Delay is allowed. A long mismatch that nobody investigates is not.  
4. After the processing delay the vendor warns you about — often a day, sometimes two — the event still appears in a standard report, not only in a debug stream.  
5. You are not double-counting. Single-page apps, strict development modes, and a tag that fires on both the client and the server are common ways to clone a success.

If any row fails, the honest status is “installed, not accepted.” Strategy meetings wait.

### A worked acceptance (composite)

After Chapter 2’s walk, Thursday Packet still failed rows 3 and 5. The payment event existed, and it vanished into a weekly total that could not be joined to Stripe. The export event appeared twice whenever the preview refreshed.

The fix was unglamorous. They added the transaction id from the payment pipe, and they de-duplicated the export event so that a re-render did not look like a second job. They also stopped sending the repaired names as a parameter. A typography product that stores client strings in an analytics property is not being thorough. It is being careless.

Two days later, the report contained five events that could be counted without a blush. Only then did the funnel chapter become legal.

---

## Event Inflation and the Opposite Error

Inflation is the more common wound. A team is afraid of missing something, so every click becomes an event. The weekly review then becomes a museum of motion. Nobody can find the job.

The opposite error is prideful minimalism: only page views, with conversions inferred from “time on page” or from a thank-you URL that a single-page checkout never quite hits. You will present a number. You will not be able to defend it.

The cure is a written contract, short enough to read aloud:

- The question this event answers.  
- The name, stable once accepted. Renaming without a mapping is how history disappears.  
- The parameters that are required, and a ban on parameters that contain personal or client content.  
- The owner who must notice if the event goes silent.  
- The date it passed the acceptance test.

If you cannot read the contract in one minute, you do not have a contract. You have a catalog.

---

## Consent, Blockers, and the Gap You Must Declare

Some people will refuse a banner. Some browsers will block a tag. Some recordings will be empty on purpose. The gap is not a moral failure of your stack, and it is not a license to pretend the remaining sample is the whole population.

When you interpret a week, say the gap out loud. “This conversion rate is among sessions that accepted measurement.” That sentence is uglier than “our conversion rate is.” It is also true. A decision that cannot survive the uglier sentence should not be taken.

Do not compensate by secretly collecting more than you declared. This book is not legal advice. It is a craft rule: a number you cannot explain in the same words you showed the visitor is not a number you may scale on.

---

## What an Event Is Not Allowed to Claim

An event can tell you that a job was finished, or that a step was attempted. It cannot tell you that the product should exist. It cannot tell you the true, final, cross-device cause of a purchase. It cannot promise that fixing a double-fire will raise revenue by a pleasant percentage.

The source archive includes a cheerful line about a payment dashboard that went “from idea to usable quickly.” Treat that as a shape: a ledger view can be stood up without a mythology. Do not treat it as a schedule for your own Stripe queries, and do not treat a pretty money chart as a substitute for accepted events on the path that produced the money.

---

## Official Names, Custom Names, and a Silent Week

Vendor lists of “recommended events” are a shared vocabulary. They are useful when you are lost for a name. They are not a product description. If Thursday Packet calls a finished typography export `generate_lead` because a recommended list waved at that label, later reports will look professional and mean the wrong thing. Prefer a plain name you can say at the desk, then, if you must, map it to a recommended name in a footnote of the contract.

Once a name is accepted, keep it still. A mid-month rename without a mapping is a quiet way to erase history. If you must rename, write the old name, the new name, and the date in the contract, and expect a broken week in the report while both exist.

A silent week deserves an owner. If `purchase_succeeded` disappears, someone has to notice before the retrospective invents a market story. Put that owner on the card. A one-person company can still be the owner. The point is the check, not a new hire.

Parameters can lie even when the name is honest. A `value` field in the wrong currency, a `success` flag that is always true, or a file-type parameter that says `unknown` for every upload will pass a casual glance in a debug view and poison a month. Acceptance is not only “the event arrived.” It is “the fields a later decision will need are true enough to use.”

## Where This Framing Falsifies Itself

**Some products have one meaningful action.** A single-purpose utility may only need “job succeeded” and “payment succeeded.” Forcing a five-event religion onto a one-button tool is ceremony.

**Some compliance regimes will shrink what you may collect.** Shrink, then. A smaller, consented contract is better than a lavish one you cannot defend. The chapter’s claim is not “collect these five names or fail.” It is “do not argue from events you have not accepted.”

**Server-side events can be the more honest path** when a client tag is unreliable. If you go that way, the acceptance test still applies. A server log is not accepted until a report a human uses can see it, and until a payment can still be joined.

**A large company may have an existing taxonomy.** Adapt the three families to that taxonomy rather than inventing a parallel dialect. Two names for the same job is another form of inflation.

---

## Takeaway

**Rule:** An event is a contract. “The tag is on the site” is not a contract.

**This week:** Write five named events or fewer, walk them through the acceptance list, and delete or demote the decorative ones that cannot change a Tuesday. Do not hold a funnel meeting until a report, not only a debug view, can see the path.
