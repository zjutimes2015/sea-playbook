# Chapter 5 — Jobs, Not Personas

Personas are flattering. Jobs are rude.

A persona lets a room agree on a cartoon: “Maya, 32, urban, power user, values simplicity.” Everyone nods. Nobody has to say what Maya is trying to finish before her train arrives. A job-to-be-done sentence is ruder. It names a situation, a struggle, and a progress the buyer wants. If you cannot write that sentence, you do not yet have demand standing on its feet—you have a mood board with demographics.

This chapter sits after the fire test on purpose. Heat without a job produces feature museums: rooms full of buttons that answer complaints one-by-one without ever being *hired* for a coherent piece of progress. Heat plus a clear job produces a broom with a handle—something a panicked hand can find in the smoke.

You will still meet people who say “we already know our user.” Sometimes they do. More often they know a persona slide. The test is simple: can they write the when / want / so-I-can line without glancing at the slide? If not, the slide was decoration.

---

## The Milkshake Logic (Public Attribution, Not Fan Fiction)

Clayton Christensen and colleagues popularized a hard teaching story in jobs-to-be-done work, retold in places such as *Competing Against Luck* and related Harvard Business School teaching materials: a fast-food chain wanted to improve milkshake sales. Early instincts pointed at the product—“make it tastier,” “thicken the profile,” optimize for a persona of milkshake lovers. Deeper attention to *when* and *why* people bought unsettled that frame.

In the morning, some buyers were hiring the milkshake for a long commute: thick enough to last, easy in one hand, more interesting than a boring breakfast. Later in the day, parents might hire a milkshake for a different job—something closer to a small, acceptable treat tied to time with a child. Same product category. Different jobs. Different improvement directions.

I am not quoting a private interview transcript. I am pointing at a publicly taught pattern you can verify in Christensen’s JTBD books and talks: **if you optimize “better milkshake” without naming the job, you improve the wrong attributes.** Morning-commute jobs care about duration, one-handed convenience, and surviving the drive. Evening-treat jobs care about portion, timing, and the social negotiation around “yes, you can have this.” Average those jobs into one “better shake” and you serve neither.

For indie builders, the milkshake is not about dairy. It is about refusing to let “users age 25–40 who like AI” replace “when I finish a client call on Thursday, I want to export markups that do not break, so I can send the file before dinner.”

### What to copy from the story (and what not to)

**Copy:** observe hiring moments; separate jobs that share a SKU; let the job choose which attributes matter; treat “do nothing” and “hire a human” as competitors.  
**Do not copy:** pretending you ran the original study; inventing dialogue; using “JTBD” as incense while still shipping feature bingo; forcing every product into a cute food metaphor in your investor update.

If a teammate starts a sentence with “According to the milkshake story…” and ends it with a feature list that ignores situations, interrupt kindly. The story is a warning about misplaced optimization—not a costume for the same old roadmap.

---

## Why Personas Fail Early Demand Work

Personas are not evil. They fail early demand work for mechanical reasons:

1. **They aggregate away the scene.** Averaging people deletes the Thursday handoff and the Monday export.
2. **They invite empathy theater.** Teams debate whether Maya would “vibe” with indigo or teal while the fire spreads in production.
3. **They smuggle inspiration.** Once Maya exists as a character, someone will invent what Maya “must want next.”
4. **They confuse identity with progress.** Buyers hire products for progress in a circumstance—not to join your persona club or your Notion aesthetic.
5. **They age badly across borders.** A US-coded persona paragraph translated into another market often keeps the adjectives and loses the job.

If you already have revenue and need marketing language, personas can return as communication tools. Before the gate, they are usually costumes for inspiration.

### The feature museum

Walk a museum: each room answers a complaint somebody once shouted. “Export CSV.” “Dark mode.” “AI summary.” “SSO someday.” No room answers *why today*. Visitors wander. Nobody hires the museum to finish a job before dinner. Complaint-led teams that skip JTBD recreate museums with better analytics—dashboards that prove you listened, not that you were hired.

A job sentence is a rope that ties features into a single hire—or proves half the features are souvenirs from a weekend brainstorm.

---

## The One-Liner You Will Actually Use

Write this until it hurts less:

> **When** [situation / trigger],  
> **I want to** [action / progress],  
> **so I can** [outcome that matters in that scene].

Examples (composites for teaching—not case-study promises):

- When I finish client markup every Thursday afternoon, I want to export a PDF that keeps comments and non-ASCII names, so I can send it before dinner without hiring a freelancer.
- When a new hire submits expenses on day four, I want to reject blurry receipts in one pass, so finance does not chase screenshots across Slack for a week.
- When my Shopify store hits ten SKUs of bundles, I want inventory math I do not trust a spreadsheet with, so a stockout does not surprise me on a paid-ad Monday.
- When I paste the same client brief into a chat tool every Monday, I want the constraints to persist, so I stop retyping the same guardrails before the real work starts.

Weak versions to reject on sight:

- When I am a busy professional, I want a better productivity suite, so I can be my best self. (Persona incense.)
- When I use software, I want AI, so I can save time. (Category fog.)
- When life is hard, I want delight, so I feel inspired. (Poster, not hire.)
- When our enterprise scales, I want digital transformation, so we achieve synergy. (Slide fungus.)

Template: `templates/jtbd-one-liner.md`.

### Stress tests for the sentence

1. **Independent rewrite:** Could two teammates independently write nearly the same sentence from the same ledger rows? If not, the job is still mush.
2. **Scene outcome:** Does the “so I can” name something that happens in a place and time? “So I can be efficient” fails. “So I can send before dinner” passes.
3. **Buzzword removal:** Strip AI / platform / seamless / delightful. Does progress remain intelligible? If not, the buzzword was doing the pretending.
4. **Competing hires:** Name what they grab instead—including “do nothing,” “ask an intern,” “pay a VA,” or “miss the deadline and apologize.” Jobs live in competitive sets. Lone jobs in a vacuum are usually fantasies.
5. **Ugly broom test:** Would they hire a plain solution that only completes this sentence? If they insist on a suite, you may have failed Chapter 4 while carrying Chapter 5 language.

---

## From Ledger Row to Job (A Small Worked Path)

Take Chapter 3’s Row B energy: Thursday PDF markups break; stack named; weekly schedule; paid partial fixes exist.

Fire test (Chapter 4): PASS on frequency + dirty work + already pays.

Now force the job without inventing a company:

- **Situation:** Thursday client handoff after markup.
- **Want:** export that preserves comments and names.
- **So I can:** send before dinner without a freelancer.

Notice what disappears: “AI-powered collaboration platform for modern agencies.” Notice what remains: a broom handle. Your `q3_wedge_opportunity` field in the ledger should now rhyme with this sentence. If the wedge says “rebuild document OS” while the job says “Thursday export,” you are already drifting into museum mode—usually because someone got excited about architecture.

Write competing hires beside the sentence: current PDF tool, freelancer on a marketplace, “send a folder of screenshots,” delay the client and absorb the shame. Pricing conversations later will argue with those hires. They will not argue with Maya’s favorite color.

### A second worked path (scale disaster)

Ledger theme: inventory for small Shopify sellers doing bundles. Already using spreadsheets. Fine at three SKUs; collapses near ten. Payment clue: people pay freelancers for “ops cleanup” after stockouts. Fire shape: scale disaster + already pays.

Job draft:

- When my bundle SKUs cross the edge of what a spreadsheet can hold in my head, I want trustworthy inventory math before I launch ads, so I do not sell air and refund in public.

Wedge rhyme: bundle-aware inventory check—not “full ERP.” Forbidden scope: warehouse robotics fantasies.

If your team keeps sliding into ERP language, re-read the sentence aloud until embarrassment does its job.

---

## Interviews Without Cosplay

You do not need a research department. You need fewer, sharper questions when you talk to humans—especially strangers, not friends who want you to succeed:

- Tell me about the last time this went wrong—where were you, what was the time pressure?
- What did you grab?
- What did you try that failed?
- What did it cost—hours, money, a client, sleep?
- What would you have paid *in that moment* to make it stop—not in abstract “value,” in cash or hours?
- If an ugly version only solved *that* moment, would you still use it?

Avoid leading with: “Would you use an AI-powered X?” Avoid touring your mockups first. Mockups teach people to perform politeness. Politeness is not a purchase order.

Capture their words into the ledger. Then rewrite *your* JTBD sentence until it can survive their words. If your sentence only survives your pitch deck, kill it without a eulogy.

### 5W2H as a scene restorer

When a job feels blurry, restore the scene with plain reporter questions: who, what, when, where, why, how, how much (time or money). You are not writing a novel. You are preventing the sentence from floating into brand fog. If “where” and “when” stay blank, you are still in persona land.

### Sampling without fake science

Five honest conversations with people who recently felt the fire beat fifty clicks on a survey that asks whether they “like innovation.” Surveys are not forbidden; they are weak as verdicts. Use them to find candidates for conversations, not to crown a job.

---

## Multiple Jobs, One Product (Choose a Battlefield)

Same buyer, multiple jobs—the milkshake pattern again. A freelancer might hire accounting software for “don’t get surprised by tax week” and separately for “look legit on an invoice.” A shop owner might hire a tool for inventory truth and also for “make me feel like a real operator.” If you optimize both at once with a tiny team, you will average yourself into mush.

Pick the battlefield job for v0. Write the other jobs in a parking lot labeled *not this broom*. Later books in *The Sea Playbook* can widen delivery. This book’s job is to stop you from pretending three battlefields are one PASS.

### Overseas and language

Jobs travel awkwardly across languages. A literal translation of your English one-liner may name a job nobody hires—or name a job that is already owned by a WeChat workflow you do not see from an English subreddit. When you build for overseas markets, rewrite the sentence with scene words from the communities where buyers already complain. Do not bless a translated persona paragraph and call it JTBD.

Country distribution belongs next to the situation clause when money will move across borders. A job that only exists where you cannot collect payment is a research note, not a product brief.

---



### Sticky-note jobs (a bad hybrid)

Some teams write JTBD on sticky notes the size of a fortune cookie: “When busy, want speed, so success.” That is persona incense with better grammar. If the note cannot hold a concrete Thursday, it is not a job sentence—it is a slogan. Use a full page. Jobs deserve the dignity of verbs and clocks.

## Gate Link: No Job, No Demand Standing

Add this checklist beside your fire decision:

- [ ] JTBD one-liner written in when / want / so-I-can form
- [ ] Competing hires listed (including do-nothing / human)
- [ ] Wedge rhymes with the job (not with a category reboot)
- [ ] At least one external quote or paraphrase supports the situation clause
- [ ] Buzzwords removed once as a stress test

If the fire PASSed but the job will not write, status becomes MORE SIGNAL or FAIL. Heat without hire direction is how teams fund museums and call it roadmap courage.

---

## Light Self-Falsification

**If every job sentence includes “AI,”** you are optimizing a hammer. Remove the word; see if progress remains.

**If jobs only appear inside your team,** you are interviewing a mirror. Mirrors flatter founders.

**If you collect twenty jobs and refuse to pick one,** you are running a museum with a bag check and calling it discovery.

**If “so I can” is always your metric vanity** (“increase engagement,” “drive retention”), you have swapped the buyer’s progress for yours.

**If you cite JTBD to end arguments without writing the sentence,** you are using theory as a club. Write the sentence or drop the acronym.

**If the sentence is beautiful and the ledger is empty,** you wrote poetry. Poetry is allowed in Seeds—not at the gate.

---

## Closing the Handle

Chapter 4 asked whether the fire is real. Chapter 5 asks what progress gets hired when it is. Together they stop two failure modes: building extinguishers for rooms without smoke, and building museums for smoke without a job.

Chapter 6 will insist that even a clean job still needs a chain of sources—pain, market behavior, competitor scars, and a technical window—before you trust it with a week you will not get back.

Until then, keep Maya off the whiteboard unless she can speak in when / want / so-I-can. Cartoons do not hire brooms. Situations do.

---



## Jobs Versus Outcomes Versus Metrics

Teams blur three layers:

- **Job:** progress in a situation (the hire).  
- **Outcome:** what “done” looks like in that scene (send before dinner).  
- **Metric:** what you measure internally (activation rate).

JTBD work lives in the first two. Metrics are servants. When metrics climb into the “so I can” clause—“so I can increase retention”—you have colonized the buyer’s sentence with your dashboard. Buyers do not wake up hiring you to move your charts. They wake up trying to get through Thursday.

Keep metrics on a separate sticky if you must. Never let them overwrite the job line.

### Switching costs as competing hires

Competing hires include inertia. “Do nothing” is often the strongest competitor because it is free and familiar. Your job sentence should make clear why doing nothing fails *this week*, not in abstract strategy time. If doing nothing is fine for another month, Chapter 4 probably should not have PASSed.


## Takeaway

**Buyers hire products for progress in a situation—not to join your persona.**

**Milkshake lesson (Christensen et al., public JTBD teaching / *Competing Against Luck* lineage):** same product, different jobs → different improvements. Do not average jobs into a mushy “better.”

**One-liner:** When… I want to… so I can…

**Stress:** scene outcome, competing hires, wedge rhyme, external words, buzzword removal.

**Template:** `templates/jtbd-one-liner.md`.

**Watch for:** feature museums; teal debates; translated personas; “AI” as a fake job; empty ledgers with pretty sentences.

**Next:** Chapter 6 — four sources, one chain. A job still needs cross-checks before you trust it with a week of your life.
