# Chapter 9 — One-Week Complaint Sprint

You now have more framework than a week can worship. Good. This chapter is a container, not a new religion: **seven days to move from empty air to a verdict**, using Chapters 3–8 as brakes and tools.

If you try to do everything perfectly, you will invent Failure Mode 4 (eternal digging) inside a calendar that looked like a sprint. The sprint’s job is to force artifacts and a dated decision—not to make you holy.

At the end, a short bridge points to Book 2 of *The Sea Playbook*: *Ship the Smallest Thing*. Do not sneak-build Book 2 during Day 3 because coding feels safer than asking for money.

---

## Sprint Rules (Pin These)

1. **One vertical pond** as primary; one secondary for cross-check. Not twelve.  
2. **Risks before conclusions** any time you make a gate call.  
3. **Public kills** (even if “public” means your tiny team doc).  
4. **No serious feature build**—prototypes that serve the priced page are allowed; platforms are not.  
5. **Red lines from Chapter 8 stay on.**  
6. **Case numbers are not goals.**  
7. **End of Day 7 has a written verdict:** kill / revise-and-reschedule / proceed to smallest ship.

Miss a day? Compress. Do not silently extend into a lifestyle.

---

## Day 1 — Choose the Pond and Open the Ledger

**Morning:** Pick a vertical where buyers already talk: a subreddit, review surface, plugin store niche, request board, or industry forum. Write why these speakers can pay (even roughly). If you cannot, pick another pond.

**Afternoon:** Create the Complaint Ledger file (`templates/complaint-ledger.md`). Add a Seeds column for inspiration so it does not contaminate evidence. Capture 10–20 raw artifacts minimum—titles, URLs, ugly quotes. Do not solutioneer.

**Output:** pond named · ledger opened · first rows with sources.

**Fail check:** if you spend Day 1 designing a logo, you have left the sprint.

---

## Days 2–3 — Structure, Dedupe, Four Questions

Run Chapter 3 hard.

- Fill three-part signal fields; mark holes.  
- Answer the four questions per cluster.  
- Dedupe URLs; update `repeat_count`.  
- Label `noise` / `watch` / `theme` / `killed`.  
- Force at least two kills by end of Day 3.  
- Promote at most three themes to `fire_test_next`.

Use AI if you want for drafts of the four questions. You still owe judgments. Automation does not speak in the pond as you.

**Output:** cleaned ledger · ≥2 kills · ≤3 fire-test candidates.

**Fail check:** 50 hopeful rows, zero kills → you are collecting, not deciding.

---

## Day 4 — Fire Test + JTBD

For each `fire_test_next` candidate (max three):

1. Fill `templates/fire-test.md` with risks first.  
2. Decision: PASS / FAIL / MORE SIGNAL.  
3. For every PASS, write `templates/jtbd-one-liner.md` and competing hires.  
4. Kill or demote anything that cannot hold a job sentence.

You should end Day 4 with **zero or one** PASS that has a job. Two PASSes means you are avoiding choice—pick a battlefield.

**Output:** fire pages · job one-liner for the survivor · forbidden_scope draft.

**Fail check:** PASS without risks or without “grab today.”

---

## Day 5 — Four Sources, One Card

Build one opportunity card (Chapter 6) for the survivor.

- Pain sources (≥2 independent).  
- Market behavior or explicit `none yet`.  
- Competitor scars in concrete words.  
- Tech window + open-source gap (no “not checked” if you want presale).  
- Risks ≥3.  
- Wedge one-liner rhyming with JTBD.  
- Status: `ready_for_presale` or back to kill/watch.

Run the thirty-minute chain pass if you are stalling. Then stop polishing. Cards are not novels.

**Output:** one card marked ready—or a kill with reason.

**Fail check:** ready_for_presale with open-source unchecked.

---

## Days 6–7 — Sell Air + Verdict

Execute Chapter 7 compressed:

**Day 6:** page + real price + payment path + delivery story (manual OK).  
**Day 7 morning/afternoon:** traffic from one/two ponds; collect questions; do not spam-ban yourself.  
**Day 7 evening — verdict meeting (30–45 min):**

Write:

```text
SPRINT VERDICT — date: ____
Theme:
Job one-liner:
What we offered (price + promise):
What moved (money / commits / clicks / silence):
Risks (≥3) now:
Decision: kill | revise & new sprint date | proceed to smallest ship
If proceed: broom scope (1 sentence) + forbidden_scope
If kill: public kill sentence
Chapter 8 failure modes we flirted with:
```

Celebrate kills. They are sprint outputs. Celebrate payments without deleting forbidden_scope.

**Output:** live test · dated verdict · next gate.

---

## Printable Week at a Glance

| Day | Focus | Artifact |
| --- | --- | --- |
| 1 | Pond + raw capture | Ledger opened |
| 2–3 | Structure + kills | ≤3 fire candidates |
| 4 | Fire + JTBD | 0–1 PASS + job |
| 5 | Chain card | ready_for_presale or kill |
| 6 | Page + checkout | Priced promise live |
| 7 | Traffic + verdict | Written decision |

Templates: `complaint-ledger.md`, `fire-test.md`, `jtbd-one-liner.md`.

---

## What If the Sprint “Fails”?

It did not fail if it produced a clean kill or a sharp revise. It failed if it produced fog: no verdict, a secret half-build, a waitlist without a number, or a story that “the market is wrong” without artifacts.

Common end states:

- **Kill:** return to Day 1 with a different pond or accept a quiet month of not forcing a product.  
- **Revise:** change job, price, pond, or wedge; schedule the next sprint; do not keep the old page on life support without a date.  
- **Proceed:** enter Book 2 territory with a broom, not a museum.

---

## After the Gate — And Only After

Once money or strong commits say go, you still do not open the Inspiration Pool. You ship the smallest thing that makes the promise observable and collect payment without mythology. Conversion fine-tuning, ad scaling, SEO systems, GEO, and link trust belong later in the series. Using them as substitutes for Days 1–7 is how people buy traffic for a job that never stood.

Product taste still matters—after the gate. Before the gate, taste is often fear wearing aesthetics.

---

## Bridge to Book 2: *Ship the Smallest Thing*

Book 1 ends when demand work has done its job: you refused fake heat, named a hireable job, chained sources, and let payment speak.

Book 2 starts where builders get itchy: delivery, MVP boundaries, getting paid without confusing a checkout stub for a business, and keeping scope inside the broom you already sold. It merges the spirit of the handbook’s development and payment volumes—without promising that shipping small equals getting rich.

If you catch yourself scaffolding a monorepo on Day 4, you are reading Book 2 fanfiction inside a Book 1 sprint. Close the repo. Open the ledger.

### What to carry forward unchanged

- Risks before conclusions.  
- Payment as stronger than applause.  
- Forbidden scope as a living document.  
- Cases as shapes, not prophecies.  
- Public kills as cultural hygiene.

### What Book 2 will challenge

Handcrafted delivery must become observable product loops without betraying the job. Payment rails must get boring and reliable. “Smallest” will hurt your ego. Good. Ego built the Inspiration Wall. We are not going back.

---

## Closing the Wall

Return to Chapter 1’s whiteboard. The Inspiration Pool can exist as Seeds. It does not get Approve. The Complaint Ledger does—the boring, rude, dated artifacts that survive fire, jobs, chains, and air.

Inspiration is a seed.  
A complaint is evidence.  
A payment is a verdict.

You do not need a larger personality to use that rule. You need a week you will not dilute—and the courage to write kill when the week says so.

When you are ready to build the broom you already sold, open Book 2. Until then, keep the extinguisher on the shelf if the room is not burning.

---



## Sprint Variants (When Life Is Not a Clean Calendar)

**Three-day compress:** Day1 pond+ledger sample → Day2 fire+JTBD+card → Day3 page+verdict. Only for experienced users of the method; still keep red lines.

**Async team sprint:** assign pond captain, fire captain, page captain; daily 15-minute sync; shared kill list. Avoid parallelizing into three different products.

**Service-first sprint:** if your air is a done-with-you service, Day6–7 may be outbound to ten named prospects with a one-page SOW. Same verdict logic; different surface.

Do not invent a variant whose real purpose is avoiding checkout. Variants are for constraints, not cowardice.

### Materials checklist (evening before Day 1)

- Blank ledger  
- Fire-test template  
- JTBD template  
- Opportunity card blank  
- A notes doc for public kills  
- A boring way to take payment  
- A timer  
- Chapter 8 red lines visible  

If the payment path is “we’ll figure it out on Day 6,” start figuring on Day 0. Mid-sprint checkout archaeology creates fake silence.

### Encouragement without prophecy

You might finish the week with a kill. That can be the best commercial decision available. You might finish with a payment. That is a beginning, not a destiny. Either way, you practiced judgment at the source of pain—the scarce skill Chapter 1 named. Keep the skill. Drop the theater.

*The Sea Playbook* continues when you are ready to ship small. Book 1’s work is complete when the Inspiration Wall no longer gets to pretend it is a gate.



## Sample Day-7 Verdicts (Teaching Sketches)

**Verdict K — Clean kill**  
Theme: AI journal for generic productivity. Offer: $12/mo. Result: 400 visits from two ponds, 12 waitlist-ish compliments, 0 checkouts. Decision: kill. Public sentence: “Killed AI journal — no priced demand outside friends; substitutes already Notes/Notion; fire was identity not schedule.” Next: new pond in dirty-work finance ops.

**Verdict R — Revise**  
Theme: Thursday markup export. Offer: $49/mo. Result: 3 checkout starts, 0 completes; questions asked for hourly one-off. Decision: revise price shape to done-with-you setup fee + optional monthly; new sprint in 10 days. Failure mode flirted: almost built a queue “to help convert.”

**Verdict P — Proceed**  
Theme: same markup export after revise. Offer: $299 setup for first 5. Result: 2 strangers paid. Decision: proceed to smallest ship — scripted manual pipeline, written SLA hours, automation backlog locked behind ten deliveries. Forbidden scope: multiplayer editor, AI rewrite suite.

These sketches are not targets. They show what a non-fog ending looks like.

## FAQ (Sprint)

**Q: Can I start midweek?**  
A: Yes. Rename days as steps. Keep the verdict date sacred.

**Q: What if my pond is tiny?**  
A: Tiny + specific beats huge + vague. If tiny and silent after an honest offer, that is still a verdict.

**Q: Can I hire help for Day 6 copy?**  
A: Yes, if they write from your fire page and job sentence—not from generic SaaS templates.

**Q: What if I get a yes from a big logo?**  
A: Great. Still write risks. Logo heat can be a single-source illusion with longer payment cycles. Use a paid pilot shape.

**Q: Do I need a company entity to sell air?**  
A: Follow your local rules. Method-wise, clarity and ability to deliver matter more than logo polish. Do not use entity delay as eternal digging.

## One Page You Could Tape Above the Monitor

1. Seed ≠ evidence ≠ verdict.  
2. Ledger rows need sources.  
3. Fire: risks first.  
4. Job: When / want / so I can.  
5. Chain: pain → wallet weather → scars → window + OSS.  
6. Air: price + stranger path + dated stop.  
7. Red lines on.  
8. Kill is output.  
9. Cases ≠ OKRs.  
10. Book 2 only after verdict.

If you only remember ten lines from Book 1, remember those.




## Worked Sprint Narrative (Composite Week)

**Monday:** You pick a design-ops adjacent forum and a plugin review surface. Ledger opens with fourteen raw links. Seeds get two AI-journal ideas so they stop polluting rows.  
**Tuesday:** Four-question pass clusters into three themes. Two meme piles become noise. One export theme repeats.  
**Wednesday:** Dedupe; kill a “pretty dashboard” theme; promote export + invoice-chase; kill invoice-chase after weak payment clues.  
**Thursday:** Fire PASS on export with three risks (support load, OSS libs exist, niche seasonality). JTBD written; competing hires include VA and screenshots.  
**Friday:** Card completed; OSS note says libs exist, shell does not; status ready_for_presale.  
**Saturday:** Page live at a flinch-worthy price; checkout tested; post with disclosure in one pond.  
**Sunday:** One stranger pays for setup; two ask for features in forbidden_scope; verdict = proceed with manual pipeline; forbidden_scope expanded; Book 2 entry criteria written.

Another week ends at Wednesday with two kills and no PASS. Also success. The narrative only matters as proof that days produce artifacts—not vibes.

### Energy management

Demand sprints are emotionally spiky. Schedule something non-product after the Day 7 verdict—walk, meal, unrelated hobby. Otherwise you will reopen the repo at midnight to soothe yourself. Soothing builds museums.

### Handoff note to future you

Write a 10-line handoff even if you are solo: pond, survivor job, price, what moved, risks, forbidden_scope, next book step. Future you will not remember the feelings. Future you will remember the file if it exists.



### Metrics for the sprint itself (process, not vanity)

Count only: sources logged, kills written, fire pages completed, cards completed, priced offers live, dated verdicts. Do not count words in the ledger as success. Do not count hours as virtue. A short week with a clean kill beats a long week with a beautiful fog deck.

If you run monthly sprints, keep a simple streak: consecutive weeks with a dated verdict. Broken streaks matter more than perfect frameworks. Restart without drama.

When Book 1’s draft sits beside Book 2’s empty folder, resist the urge to outline five products. One broom that survived air is enough work for a season.

Print the week table. Put it on the desk. When someone asks what you are working on this week, point at the day—not at a vision slide. Vision slides reopen the Inspiration Wall. Day numbers keep the broom in view.

End of Book 1 draft path: chapters 1–9 now form a single English manuscript suitable for Kindle shaping. Editing passes can tighten; the spine is here.
 The series continues only after that dignity is practiced once in public, even if public means a three-line kill in your own doc.

Keep going only when the artifacts are real.
 That is enough.
 One clean week beats a decorative quarter.
 Write it down today, clearly.

## Takeaway

**One-week sprint:** pond → ledger → fire+JTBD → chain card → priced air → dated verdict.  
**Rules:** one/two ponds, risks first, kills count, no platform build, Chapter 8 red lines on.  
**Fail = fog.** Kill/revise/proceed are all valid ends.  
**Book 2 bridge:** ship the smallest observable thing after the verdict—not during Day 3.  
**Carry forward:** risks-first, payment>applause, forbidden scope, no numeric prophecy.  
**Watch for:** sprint cosplay that secretly becomes a build; waitlists; monorepo itching.  
**Series:** *The Sea Playbook* Book 1 complete in draft; Book 2 is *Ship the Smallest Thing*.
