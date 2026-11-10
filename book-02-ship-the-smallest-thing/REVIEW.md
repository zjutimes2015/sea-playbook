# REVIEW — Book 2 Ship the Smallest Thing

**Date:** 2026-11-09 (America/Los_Angeles)  
**Unit:** First full English manuscript (handbook 08 + 07 spirit) + listing pack + gates  
**Track:** A (English nonfiction / Sea Playbook)

---

## Gatekeeper block (≥3 risks → fixes → ship note)

### Risks / holes (write first)

1. **Two source volumes in one book.** Merging development (08) and payment (07) can produce a “two pamphlets glued together” feel if the through-line (Thursday Packet) or the three-line rule fails to bind them.  
2. **Handbook fee tables and vendor dramas misread as advice.** October 2026 rate impressions, a roughly $30–40 abuse bill, trust-questionnaire weather, and a termination-after-incident shape could be copied as current quotes or as forecasts.  
3. **Stale CVE / version numbers.** The source archive mentions a patched release in one framework incident. Copying that number forward would be bad advice.  
4. **Scope creep into Book 3/4.** Attribution, SSR, and ads-adjacent notes could accidentally become a traffic or SEO book.  
5. **calibre EPUB not run tonight.** Upload-week typesetting issues (TOC, fonts) remain unchecked until deferred gate.  
6. **LanguageTool CLI still blocked** (no Java on the box), as in Book 1 — residual grammar risk on a first full draft.

### Suggestions / fixes applied

1. One composite through-line (Thursday Packet, carried from Book 1) plus a single rule: launch is feedback; the homepage promise is the backlog; pipes are not a business. Payment chapters start only after the address and promise work.  
2. Front matter, takeaways, listing description, and appendix perimeter restated: official pages and contracts win; cases ≠ OKRs; no approval / payout / conversion / income guarantees. Fee tables labeled as ~October 2026 structural contrast.  
3. Chapter 8 tells readers to use the *current* vendor advisory and explicitly not to copy archive version numbers forward.  
4. First-touch and curl/SSR kept as engineering gates; channel scaling and SEO systems pointed at Books 3–4 with a hard “no ads on Day 5” sprint rule.  
5. STATUS marks **calibre deferred until upload week**; do not publish without it.  
6. Manual English craft pass plus codespell (MoR false positives ignored) and proselint; remaining nits documented below.

### Conclusion

- **Conditional ship** as KDP-ready *manuscript + listing pack* for human upload prep (~**25,752** English words in `BOOK2-FULL.md`).  
- **Conditions:** keep calibre gate before actual KDP publish; spot-check Look Inside for perimeter language and for fee-table “not a quote” labels; price in $7.99–$9.99; no auto-upload.

---

## English craft notes

- Voice target: human colleague; short gate sentences; case → definition → boundary. Named reader: overseas/indie builder with a Book 1 proceed verdict, itching to overbuild.  
- Banned filler watched: moreover / delve / tapestry / unlock the power / landscape / robust / seamless — not found in the manuscript.  
- Quotes: XP community / Ron Jeffries “You aren’t gonna need it” (YAGNI) attributed; Steve Blank’s outside-the-building teaching named without inventing a new wording or testimonial. No invented customer quotes. Composite Thursday Packet uses `example.invalid` and is labeled a teaching sketch.  
- Through-line preserved: Book 1 broom already sold → cathedral temptation → clock-based selection → homepage backlog → address → explainable infra → pipes as assets → entitlements land → red lines → two-week verdict → Book 3 bridge.

---

## Tool gates

### proselint

- Ran via a local venv: `proselint check` on front matter, chapters, interlude, appendix, and templates.  
- Fixes applied: paragraph starting with “But” (Ch1); cliché “on the same page” (Ch6, Ch8) rephrased; “less true” uncomparable (Ch8) rephrased; “Early-member” hyphen nit (Ch6) rephrased.  
- Leftovers (accepted): two `misc.capitalization.days` hits on host-like strings `thursdaypacket.example` and `thursday.packet.gmail.com` in Chapter 4 — not prose weekday errors.  
- Manual redundancy / slogan / AI-filler scrub on the full unit.

### LanguageTool

- Java is still not installed on the box, so LanguageTool CLI / `language-tool-python` cannot start (same deferral as Book 1, 2026-11-05).  
- Manual EN grammar/spelling pass on all chapters, plus `codespell` (noise: MoR → “more”; ignored). Re-run LanguageTool when Java is available or on upload week.

### calibre

- **Deferred until upload week** (per nightly rule: calibre before KDP upload, not mandatory every draft night if export is heavy).  
- Do not treat manuscript ship as “published.”

---

## Ship note

New Book 2 unit: front matter, Ch1–9, Interlude (open source + AI discipline), Appendix toolkit, five templates, `KDP-LISTING.md`, and this REVIEW. `BOOK2-FULL.md` merged (~25,752 words). Queue advances to Book 3 — *Buy Time, Not PMF*. Mirror to the box books folder. Calibre remains for upload week, as with Book 1.
