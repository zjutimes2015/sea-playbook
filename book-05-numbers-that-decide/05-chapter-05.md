# Chapter 5 — Kill the Average User

The weekly conversion rate at Thursday Packet was a polite number. It was also a lie of omission.

In one blended row, the typography-and-exports room, the `/repair` search visits, a leftover ads test, desktop, mobile, new people, returning people, exporters, and wanderers had been poured into a single glass and stirred. The glass was called “the user.” The user was said to convert at a rate that made the room feel adult. The user, being an average, could not be found in any recording.

A second polite number sat in the ads tab: conversions, attributed to the campaign, in a window the platform had chosen. A third number sat in GA4, smaller, under a different model. A fourth sat in Stripe, which knew about money and almost nothing about creative. Each table had a defender. The meeting lasted an hour and produced a sentence: “Overall, we are fine, but mobile is weak, so we should scale what is working.” Nobody could say what was working, because the average had eaten the evidence.

This chapter takes the lid off the blender. Then it writes down which table is allowed to decide which kind of question. Perfect attribution is not on offer. A transparent rule is.

---

## Comparisons That Have a Right to Speak

A comparison is not a decoration in a report. It is how you stop talking about a person who does not exist.

Start with splits you can defend with a decision:

- **Channel or source.** The typography-and-exports hook versus the `/repair` query versus a paid test. You are asking which visits complete core value and which visits only wander. Clicks are not the prize. Completed jobs and paid jobs are.
- **Device.** Not because “mobile is the future,” but because a control that looks like a caption will fail on a narrower screen first.
- **New versus returning.** A returning typography regular may look like a conversion machine and hide a cold path that still cannot finish.
- **Did the core event, or not.** This is often the most honest split in the book. People who exported versus people who did not are already two products.

You can add country later, especially when the ledger shows money clustering. You can add campaign or content group when the sample can bear it. You may not add a dozen vanity segments on the first week and then “see what’s interesting.” Fishing is not a comparison. It is a way to find a story you already wanted.

### From a difference to an action (the gate)

A difference is not yet a verdict. Pass it through four questions:

1. Has the difference held for more than one week, or is it a single wobble?
2. Can a recording, a map, or a real complaint explain it in words a human said?
3. Which book, or which owner, receives the work? Paid structure belongs to the ads discipline. Channel mix belongs to the traffic discipline. A page that does not receive the query belongs to search. Payment friction belongs to the pipe. A broken control belongs to the product.
4. Are you about to write a “strategic” conclusion from one week of weather?

If you cannot pass the four, the legal output is a note: “difference observed, not yet actionable.” The legal output is not a new religion about a channel.

The end of a comparison is a **reversible experiment**, not a permanent myth. “This hook deserves another careful week” is a grown sentence. “This hook is the only future of the company” is a souvenir.

---

## Thursday Packet, Split (Composite)

When the blender was turned off, the polite weekly rate came apart.

Visits from the typography-and-exports room still completed preview and, after the export button was made into a button, often completed the file. A subset paid. The path was familiar, and the hook was doing the job Book 3 had asked it to do.

Visits from the `/repair` query previewed almost as often, then paused. Some of those people were shopping for a generic “document converter,” the fat phrase Book 4 had already refused to worship. They wanted a different finish than a Thursday-ready typography export. Last-click, in Book 4, had already warned that a page can lose the job it did not claim. The comparison now showed the same wound in numbers: search visits were not “worse users.” They were often different jobs.

The leftover ads test produced clicks and almost no core-value events. The platform still found a way to look useful inside its own window. The ledger was quiet.

Mobile, as a blend, looked rude. Mobile from the typography room was acceptable. Mobile from cold search was poor, and the recordings showed the same caption-that-was-not-a-button, plus a pricing footnote that some people opened and closed in peace. “Fix mobile” would have been the average talking. “Fix the export control, and stop pretending generic converter traffic is typography traffic” was the comparison talking.

None of this required a data warehouse. It required the splits, two weeks of patience, and the humility to let a polite average die.

---

## Several Truths at Once (Attribution Without Physics)

You will, if you run ads or email or search at the same time, see more than one conversion total. This is normal. It is not a scandal, and it is not a reason to freeze every campaign until the totals marry.

Four common tables, and what they are trying to optimize:

| Table | What it is serving | Typical bias |
| --- | --- | --- |
| **Ads platform** | Its own model and window | It tends to take credit for itself; it will not match GA4 on a faithful day |
| **GA4 paths or models** | Google’s world, including modeled gaps | Consent, modeling, and cross-device limits all cut in |
| **Your first-touch field** (UTM or referrer saved on the user) | The rule you wrote | Lost parameters, later rewrites, in-app browsers, and direct visits will pollute it |
| **Stripe or the ledger** | Where the money came from | It will almost never tell you which headline did the work |

The forbidden move is to pick, each Friday, the table that flatters the plan, and to announce that attribution is now clear. The opposite forbidden move is to stop all paid work because three tables disagree.

A good-enough rule for an early overseas site is narrower than a textbook:

- Use the ads platform, inside a written cap, to steer **daily bids and budgets** — that is an ads-book skill, not a reason to ignore the ledger.
- Use GA4 quality, plus first-touch on people who actually paid, to decide **which channels and which pages deserve more care**.
- Use the ledger for **finance**. Money is money. A platform’s conversion is not money.

Good enough, at this stage, means you can answer three questions:

- Which kind of channel brought more **paying** people, not merely more clicks?
- Between search, the owned room, and paid, who completes the **core event** more often?
- Did a campaign’s UTM appear as first touch on a person who paid?

Not good enough, and actively downgraded here, is a quest for perfect multi-touch theater, a unified identity across years and devices, or a sectarian fight that assigns every branded query to SEO or to ads as a matter of faith.

### When the tables conflict

Look at instrumentation and consent first. Then look at windows and models. Only then argue about the business. If first touch is overwritten on every session, you do not have a marketing debate. You have an engineering defect. If a payment event still lacks a transaction id, you are back in Chapter 3.

Say your rule out loud, in the same words internally and externally: “This is the contribution under this model and this window.” Do not say “the true source.” Attribution is a management agreement. It is not a law of physics.

---

## Where This Framing Falsifies Itself

**A single-channel product can wait to split.** If almost every stranger still comes from one room, a forced four-way comparison will manufacture noise. Keep the core-event split. Add channel splits when a second source is real.

**A large, mixed acquisition team may need a heavier model** than “good enough.” If you have that team, you also have a duty to write the rule and to stop shopping for a flattering table. Complexity is not a license to skip the four-question gate.

**Brand search will flatter organic** if you let it. People typing your product name are often memory, as Chapter 1 already said. Compare brand and non-brand before you congratulate a page, or before you cut a campaign that may have created the memory.

**Privacy constraints may prevent some joins.** If you cannot send a transaction id, or cannot store a first-touch field, write the limitation and decide with thinner evidence. Do not invent a precise story the data is not allowed to support.

---

## Takeaway

**Rule:** The average user is a blender. Comparisons, held for more than a week and explained in a recording, are what turn a difference into a reversible experiment.

**This week:** Split one report by channel and by “core event done or not.” Write which table is allowed to decide budget, which table is allowed to decide care, and which table is the ledger. Do not scale a blend.
