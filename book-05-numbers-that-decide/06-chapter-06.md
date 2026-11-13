# Chapter 6 — The Recording Is a Diagnosis, Not a Verdict

The quantitative break at Thursday Packet was clear enough to be misused.

Export-complete lagged preview-ready. A bar chart said so for two weeks. A person who liked action wrote “simplify the homepage” at the top of a list, because a homepage is a place you can always simplify, and because an assistant, asked to summarize recordings and maps, had produced three tidy bullets: reduce clutter, increase contrast, shorten the form. The bullets were not vicious. They were generic. Generic advice is how a real wound — a caption that did not look like a button — gets lost under a renovation.

This chapter is the qualitative half of the same week. A recording and a map exist to explain a number you already distrust or already intend to act on. They are not a substitute for the number, and an assistant’s summary of them is not a sentence you may carry out at full site scale. The source archive has a charming line about “watching two recordings and understanding.” Treat the charm as a shape: a few watched sessions can beat a long argument. Do not treat it as a promise that two clips will always reveal the truth, or that a summary of two hundred clips is a strategy.

---

## Why the Count Is Not Enough

A funnel can tell you *where* people left. It is much weaker at telling you *how* they left.

They may have clicked a region that is not a control. They may have opened a footnote, found the one fact they needed, and closed the tab in peace — a “bounce” that was a finished short job. They may have watched the preview render, tried to select a name, and thought the page was frozen. They may have met a payment form that failed on a card their country uses. They may have been a bot, a colleague, or you, testing, and your own sessions may be polluting a small sample.

Without a recording or a careful live sit-in, you will invent a personality for the visitor. The personality will resemble your fear or your favorite theory. Thursday Packet’s favorite theory, for a week, was “the page is too typographic; people want a plainer converter.” The recordings, when someone actually watched them, did not show a craving for a plainer religion. They showed a pointer circling a specimen caption, and a thumb on a narrow screen that never quite landed on the download.

That is the job of this layer: to keep you from remodeling the house because a door handle was painted to look like trim.

### What to watch, in a useful order

Do not start with a random theater of “interesting” sessions. Start from the break you already named.

1. Filter to the page and, if you can, to the sessions that reached the step before the break and did not complete the next one.  
2. Watch a few of those all the way through, at a speed you can still see a hesitation. Take notes in verbs: circled, paused, pinched, opened, closed, typed, deleted. Ban adjectives like *confused* until a verb has earned them.  
3. Open the click or scroll map for the same page and the same rough period. Look for heat on non-controls, and for cold regions on the control you thought was obvious.  
4. Only then, if you use an assistant to summarize recordings or maps, treat the result as a **first diagnosis**. It must be checked against at least a sample you watched yourself before it becomes a change list.

If the assistant and the watched sample disagree, the sample wins until you understand the disagreement. If they agree, you still write a small, reversible experiment, not a brand redesign.

---

## Assistants, MCP, and the Speed That Lies

A recording assistant that can cluster sessions is a time saver. So is a connector that lets you ask an analytics property a question in ordinary language. The source archive includes a path for asking GA4, through a model, in plain speech, and a charm line about that ease. Speed is real. So is the failure mode.

The risks are practical, not mystical:

- Permissions that are broader than read-only, or credentials left where they should not be.  
- A model that invents a metric definition, or quietly changes the date range you thought you asked for.  
- A fluent paragraph that enters a weekly report as if it had been a query result.

The gate is dull on purpose. A natural-language answer enters a decision only after a human can replay it in the official interface, or against the raw API response. The assistant is not the analyst of record. You are.

The same gate applies to a summary of recordings. “The AI watched everything” is not a method. It is a way to skip the two clips that would have shown the caption. Use the summary to find clusters you might have missed. Then watch. If you cannot watch, you cannot yet change the page at scale.

Thursday Packet used an assistant once, early, and received the generic renovation list. Used later, after the filter was set to “preview ready, export missing,” the same kind of tool pointed at the lower third of the page. That pointer was useful. It was still not a verdict until a human watched five sessions and saw the same circling.

---

## A Worked Diagnosis (Composite)

Five sessions, not two hundred, were enough to write a diagnosis at Thursday Packet — enough, in this composite, to change the next experiment, not enough to declare a law.

Session A: a desktop visitor from the typography room previewed, smiled (you cannot see a smile; you can see they enlarged a name), and found the export only after scrolling past the specimen twice. The job finished. The control was late, not invisible.

Session B: a narrow-screen visitor from search previewed, tapped the specimen, tried to pinch, and left. The caption never received a tap that counted as a download.

Session C: a visitor opened pricing, scrolled, and left from `/pricing` without anger visible in the cursor. The “bounce” from a blended report had included this peaceful exit.

Session D: a visitor reached checkout and stopped when a payment method they expected was absent. That is a pipe problem, and it is not solved by a clearer typography caption.

Session E: the builder’s own test account, unfiltered, looked like a superhuman converter. It was removed from the week.

The diagnosis that survived this sample was narrow: the export control on `/repair` is easy to mistake for a caption, especially on a narrow screen. The non-diagnosis was equally important: the homepage was not, in this sample, the break. The generic converter visitor might still be a Book 4 problem — a page asked to finish a job it did not claim — but that is a different experiment, not a renovation of everything typographic.

They wrote the diagnosis at the top of the experiment card, listed risks first (small sample, possible mix of jobs, payment method still untested), and only then changed the control. That is the order. Diagnosis, risks, change. Not change, hope, screenshot.

---

## Privacy, Masking, and the File You Must Not Record

Thursday Packet repairs other people’s documents. A recording tool that stores a client list is not a thorough stack. It is a leak.

Mask or disable recordings on surfaces that can show uploaded content. Do not send names, addresses, or document text as event parameters (Chapter 3 already said this; it is worth repeating where the clips live). Use test files in your own walkthroughs. If a real session appears with real client data, treat it as an incident, not as a convenient example for the retrospective.

Consent applies here as it did in the event chapter. If a person declined, you do not get to “need” their session for the diagnosis. Write the gap. Live with a thinner sample.

---

## Where This Framing Falsifies Itself

**Some breaks are fully visible in the count.** If a payment API failed for three hours and the success event dropped to zero, you may not need a recording to know the pipe broke. Still, a clip can show you how the error appeared to a person, which is useful for a message, not for the diagnosis of the outage.

**Some products cannot legally or ethically record.** Then you sit with people, or you read support mail, or you instrument only consented, non-sensitive events. The principle is qualitative check, not a vendor logo.

**A huge sample of recordings can still be watched badly.** Speed-watching two hundred clips at 8× is another way to miss the caption. A structured sample beats a theatrical binge.

**An experienced specialist may run a tighter assistant loop than this chapter allows.** If they can show a replay path from summary to raw clip, they are still inside the gate. If they cannot, they are asking you to trust fluency.

---

## Takeaway

**Rule:** A recording explains a break. An assistant’s summary is a first diagnosis, and it does not get to remodel the site until a human has watched a sample.

**This week:** Take the steepest step from Chapter 4, watch a handful of sessions that reached the prior step and failed the next, and write a diagnosis in verbs before anyone is allowed to “simplify the homepage.”
