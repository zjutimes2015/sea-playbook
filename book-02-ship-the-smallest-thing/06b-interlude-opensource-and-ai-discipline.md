# Interlude — Open Source Before You Invent, and Less Lottery in the Editor

This interlude is a bench, not a second book.

Book 1 had an interlude on GitHub and search as *demand lenses*. This one is about the two disciplines that keep a smallest ship from turning into a private science fair: **compare a working implementation before you invent**, and **treat AI coding as an engineering practice rather than a slot machine**.

If you are in a hurry, steal the two checklists, then return to Chapter 7 or 9. Do not steal them as slogans and skip the webhook test.

---

## Open Source Is an Honesty Field, Not a Mood

Book 1 already asked you to fill an open-source gap on the opportunity card. Book 2 is where people “meaning to check later” write a parser anyway.

The hard rule on this desk is the one Micheal set for the whole team: **before you improve or iterate, go to GitHub (or the equivalent public record), find a comparable open project by what it actually does — not by vibes — and read it.** Stars can help you sort. They are not a blessing. Forks are a way to study a scar. They are not a command to paste.

For Thursday Packet, this field was already half-filled: libraries A and B parsed and filled the fixture; no hosted Thursday workflow shell was found. That is the only kind of “we built it” this book respects — a written difference on top of a checked field.

**What to record, in boring prose:**

- What you searched (verbs, not brand poetry).  
- What you found (repo, license, last commit recency, whether it actually runs on *your* fixture).  
- What you will reuse.  
- What you will not reuse, and why (license, mismatch, abandonware, quality).  
- The remaining gap in one sentence.

If the gap is empty, your smallest ship may be a guide, a hosted wrapper you have permission to run, or a kill. Empty gaps are a success of honesty, not a failure of creativity.

### License, again, in daylight

Prefer licenses you and counsel can live with in a product you sell. Study-only is the default for licenses that would force you into obligations you have not accepted. Reading is always allowed. Copying into a closed product “for speed” is how you buy a later problem that no webhook can fix.

Comparable commercial sites are part of the same honesty field. You are allowed to walk their mainstream path. You are not allowed to pretend you invented it, and you are not allowed to copy assets you do not own.

---

## Why AI Coding Feels Like a Lottery

A builder will say “the model is random this week.” Sometimes the model is worse than last week. More often the task was a fog.

The handbook compresses four principles that lower the lottery feeling. They are communication rules, not magic prompts.

**1. Unambiguous demand.**  
Two teammates should read the request and picture the same Thursday packet. If you want exploration, say so on purpose. Accidental fog is not “creative latitude.” It is a way to spend tokens on a cathedral.

**2. Concrete implementation details.**  
Name the API, the docs, a sample request and response, the expected behavior on a nasty client name. For interface work, give structure or a screenshot. “Make it nice” is a slot machine.

**3. One thing at a time.**  
Module-sized changes. Control the blast radius. A single session that “also just rewrites auth” is how preview credentials leak into a client bundle.

**4. Align on understanding before code.**  
Ask the model to restate the task and list the checkboxes. Correct the prose first. Code is a late instrument.

**Conclusion.** Most lottery tickets are sliced work and unclear requests. Changing models is a second-best move.

These four are also how you stay the owner. If you cannot tell whether the output is right, you did not specify a test. Fail Fast: a fixture of nasty names should fail the build when the encoding path regresses. A model that “usually works” is not a test.

---

## Commands, Skills, and UI Scaffolds Are Assets When They Are Boring

Talking to a model in a fresh chat, every time, is how teams forget what they learned on Tuesday.

| Instrument | Use | Gate |
| --- | --- | --- |
| Saved commands (a markdown recipe plus arguments, in the teaching example of a coding agent) | Repeated checks: a go-live lint, a typo pass, a sitemap peek | Version the text. Stop pasting a page-long prompt from memory. |
| Skills (multi-step flows that may call your own APIs) | Work you already did twice | Write inputs, outputs, and failure behavior. Secrets never live in a plaintext skill committed to a public repo. |
| UI generators (the handbook names a design-to-layout tool as a teaching example) | Theme experiments, a section, exported markup or notes that a local assistant then implements | The output is a prototype accelerator. It does not replace accessibility, performance, or the `curl` test. |

**Conclusion.** If you have said the same prompt three times, it wants to become an asset. “Vibe coding” becomes a practice when the practice has files.

For Thursday Packet, a saved command that runs the fixture, the `curl` promise test, and a webhook signature check will save more Thursdays than a new theme.

---

## Four Hard Rules, Applied to This Book

Micheal’s coding rules are not decoration. Here is where they land in a smallest ship:

| Rule | Landing in Book 2 |
| --- | --- |
| **YAGNI** | Do not build a future factory. Do not rewrite what the template already does. |
| **KISS** | Prefer a host to a private cluster. Prefer one obvious query to a distributed tale. |
| **Naming is design** | First-touch fields, entitlements, and credits must be searchable. Ban `data`, `temp`, `util`, `handle` as empty names. |
| **Fail Fast** | Missing secrets, bad webhook signatures, and quota edges should fail visibly. Silent `except: pass` is a bug. |
| **Open source before you invent** | Login, payment hooks, i18n, and SSR: read a mature path and a comparable site first. |

If a pull request (or your lonely commit message) cannot survive this scan, it is not “scrappy.” It is future folklore.

---

## A Ninety-Minute Bench Session (When You Are Stuck Inventing)

You do not need a full research week. You need a timed honesty pass.

**Minutes 0–15.** Write the verb you think you must invent. Search public code and two comparable sites for that verb. Save the queries.

**Minutes 15–40.** Run the best candidate on your fixture, or honestly record that you could not. Read the license.

**Minutes 40–60.** Write the gap sentence and the reuse sentence. If the gap is empty, stop the invention.

**Minutes 60–90.** If a gap remains, write a request for the next coding session using the four principles: unambiguous, concrete, one thing, a restated plan. Add one Fail Fast test to the request.

That is enough to keep Thursday Packet from becoming a third parser.

---

## Where This Interlude Falsifies Itself

Open-source honesty fails when the comparable work is in a category you must not copy (stolen data, clearly pirated assets, or a license you will not honor). Walk away.

AI-discipline fails when you use “write a precise prompt” as a way to avoid talking to a user, or when Fail Fast tests are generated by the same model and never read by a human. A test you do not understand is a costume.

The bench session fails when you extend it into a three-day framework tour (Failure Mode 2). Ninety minutes, then back to the promise.

---

## A Request You Can Reuse (Thursday-Shaped)

Here is a request that follows the four principles. Steal the shape, not the product.

```text
Task (one thing): Make the export path preserve non-ASCII client names in the
downloaded packet, using library A already in the repo.

Context: Fixture files are in fixtures/names/. Expected outputs are in
fixtures/names/expected/. Do not add an editor. Do not change auth.

Docs: link to library A’s encode API (paste a sample request/response).

Please restate: the input, the output, the files you will change, and the
test you will add. Wait for a yes before writing code.

Fail Fast: add a test that fails the build if any fixture name is corrupted.
If a required env var is missing, the command should exit non-zero.
```

If your real requests are longer than this and also vaguer, the lottery will return. If they are shorter and still vague (“fix export”), the lottery will return faster.


## Takeaway

**Rule:** Compare a working implementation before you invent. Treat AI coding as specified, sliced, tested work — not as a lottery you could win by switching models.

**This week:** Fill the honesty field for the core verb. Save one command you have already typed three times. Add one Fail Fast fixture.

**Not a promise:** A popular repository, a high star count, or a fluent assistant does not guarantee a correct entitlement or a safe license. Official docs, licenses, and your fixture win.
