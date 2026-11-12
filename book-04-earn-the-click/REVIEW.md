# Book 4 review gate — Earn the Click

**Date:** 2026-11-11 (America/Los_Angeles)  
**Unit:** Book 4 manuscript + listing pack + templates  
**Track:** A (English nonfiction / playbook)  
**Word count:** `BOOK4-FULL.md` is **24,551** English words (`wc -w`). Complete KDP-ready manuscript (front matter, Ch 1–9, Interlude, Appendix). Series advice had aimed at 30–38k because three handbooks sit in this volume; this unit is a full book in the same band as Books 2–3, not a “Part A” milestone, and was not padded to manufacture a higher count.

---

## Gatekeeper block (≥3 risks before any praise)

**【Risks / holes】**
1. Length is under the 30–38k band in `series/01-SERIES-SPLIT-ADVICE.md`. A later polish pass could deepen worked SERP walks or the Interlude’s page-type matrix; a later pass must not add inventory-like chapters to chase a number.  
2. LanguageTool CLI still cannot run on this box (no Java), so English mechanics rely on a human craft pass plus codespell, same deferral as Books 1–3.  
3. Product and crawler names (answer surfaces, bot lists, schema testers, llms.txt adoption) will move; the manuscript tells readers to recheck official docs, but a dated sentence can still age between now and upload week.  
4. The Thursday Packet composites, if quoted out of context, could be mistaken for a real company’s coverage or citation results. The front matter and Appendix H label them; listing copy must keep the same perimeter.  
5. calibre EPUB/TOC/fonts is again deferred until upload week, so “KDP-ready manuscript” is not “published.”

**【Suggestions】**
- Keep the book complete and unpadded; if a later unit expands it, expand tests and limitations, not outline moss.  
- Re-run LanguageTool when Java is available or on upload week.  
- Recheck official crawler and schema documentation during export week; adjust bot names if they moved.  
- Human KDP upload only; no auto-publish.

**【Conclusion】**
- **Conditional pass** for a KDP-ready manuscript ship: review gates 1–2 done (proselint clean except intentional lowercase query strings; LanguageTool deferred with codespell + craft pass); calibre remains a publish-week gate.  
- Conditions: do not treat this commit as a live ASIN; do not quote composite figures as results.

---

## Track A checks

- Through-line: Thursday Packet after a Book 3 keep verdict → Organic board / index-as-business myth → search as a system → a keyword map you can defend → crawler-received HTML → increment and last-click → citability (seen ≠ chosen) → links as trust with a five-step brake → red lines → two-week search-and-citation verdict → Book 5 bridge.  
- No MRR or income promises. Handbook figures (index-rate ~17% toward nearly 100%, organic ~+40% shape, ~68 sites / 744 articles and an “about four times” editing contrast, “ten times the traffic” title language) are labeled teaching shapes.  
- Self-falsification sections exist in each chapter, the Interlude, and Chapter 8.  
- Named reader, short-sentence gates, case → definition → boundary, banned-filler scrub (no moreover / delve / tapestry / unlock-the-power class phrases found).  
- Verifiable public attribution used sparingly: llms.txt associated with Jeremy Howard / the fast.ai direction of work; no invented quotations or testimonials.  
- Handbook 12 is an Interlude, not a sixth title.

---

## Tool gates

### proselint

- Ran via `/tmp/proselint-venv`: `proselint check` on front matter, chapters, interlude, appendix, listing, and templates, then on `BOOK4-FULL.md`.  
- Fixes applied: lexical illusion on a “Volume / Volume” heading; title-scoped operator wording (the tool preferred “entitle” over the documented search operator); “obviously”; “true facts”; “for free”; “Repeat the same”; “useable”; an `amber` color name that tripped an a.m./p.m. rule.  
- Leftovers: lowercase `thursday` in **query-string / URL** table cells (`thursday packet`, `thursday-agenda`), kept on purpose because they are typed queries or paths, not calendar prose. Same class of false positive as weekday-hostname leftovers in earlier books.  
- Manual redundancy / slogan / AI-filler scrub on the full unit.

### LanguageTool

- Java is still not installed on the box, so LanguageTool CLI / `language-tool-python` cannot start (same deferral as Books 1–3).  
- Manual EN grammar/spelling pass on all chapters, plus `codespell` (**0 findings** after fixing `useable` and a `sting`/`string` false friend by rewriting the sentence). Re-run LanguageTool when Java is available or on upload week.

### calibre

- **Deferred until upload week** (per nightly rule: calibre before KDP upload, not mandatory every draft night if export is heavy).  
- Do not treat manuscript ship as “published.”

---

## Ship note

New Book 4 unit: front matter, Ch1–9, Interlude (tool-page types and the factory temptation; handbook 12 held as a bench, not a sixth title), Appendix toolkit, five templates, `KDP-LISTING.md`, and this REVIEW. `BOOK4-FULL.md` merged (24,551 words). Queue advances to Book 5 — *Numbers That Decide*. Mirror to the box books folder. Calibre remains for upload week, as with Books 1–3.
