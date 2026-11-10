# Chapter 9 — A Two-Week Ship-and-Collect Sprint

The previous chapters gave you language, cards, and red lines. This chapter gives you a calendar.

Two weeks is the default because week one wants an address and a completable promise, and week two wants a payment that grants something. You can compress to seven days if you already have a host, a domain, and a pipe in sandbox. You may not compress by skipping red lines.

The output is a dated verdict: **ship**, **shrink**, or **wait**. Not a mood. Not “we mostly launched.”

If you do not have a Book 1 carry-forward pack — job one-liner, forbidden_scope, priced promise, risk list — stop here and go back, unless you are explicitly *rehearsing* the sprint on a fictional card. Rehearsal is allowed if you label it. Pretending a rehearsal is a launch is not.

---

## Sprint Rules (Pin These)

1. **The homepage promise is the only backlog.** Later/no lists are written in public (or at least in a dated file).  
2. **Risks before conclusions** on every card you close.  
3. **Commit means deploy** to a preview or to production, as you declared on day one. No zip lifestyle.  
4. **curl must show the promise** before you invite anyone who is not a designated tester.  
5. **No live money until webhook acceptance is green** (pay, replay, fail, refund).  
6. **No stack migration** of the main site during the fourteen days, unless a written exception already existed.  
7. **Cases are not forecasts.** You will not use a handbook timer or a fee-table impression as a promise to a tester.  
8. **End with a verdict in writing**, on day 14 (or on day 7 of a compress), even if the verdict is wait.

If a rule is broken, you do not “make it up on the weekend.” You write the break, and you shrink the verdict.

---

## Days 1–2 — Carry-Forward, Boundary, Selection, Host

**Day 1 morning.** Put the Book 1 pack on the wall: job one-liner, forbidden_scope, priced promise, risks. If any of the four is mush, spend the morning tightening it. Do not open a new editor.

**Day 1 afternoon.** Fill the MVP boundary card (Chapter 3). Hero sentence in one line. Core task in one line. In / out. Three risks. Conditional pass or reject.

**Day 2.** Fill the selection card (Chapter 2) and the open-source honesty field (Interlude). Import the repo to the host. Production and preview environments named. A missing secret should already fail the boot.

Done when: a preview URL exists, even if it is ugly, and the boundary card is signed (by you, with a date).

Anti-pattern: Day 2 spent choosing typography tokens.

---

## Days 3–5 — Address, Promise on the Page, Observability

**Day 3.** Attach the domain on both sides. Forward `support@` and `contact@`. Put those addresses on the site and in any payment profile you will use.

**Day 4.** Rewrite the homepage until a tired person can repeat the broom. Put the core capability on that page, even if the rest of the nav is a “later” graveyard you hide. Policy links exist.

**Day 5.** Analytics with a **frozen first touch**. Event names from Chapter 5: landing, task start, task success or fail, checkout start, payment success or fail, entitlement granted or failed. Run `curl` and paste the hero sentence into the go-live card.

Done when: a stranger could find the promise at the canonical host, and you can see your own test of the core task in the event log — even if payment is still off.

Anti-pattern: Day 5 spent adding a second language or a demo reel of unbuilt features.

---

## Days 6–7 — Core Task Honest, Fixtures, Mid-Sprint Gate

**Day 6.** Make the core task completable once, on the host, with fixtures that include nasty names (or whatever your promise’s nasty cases are). Preview and download (or the equivalent) must come from the same result. If you cannot finish the task once, you do not have a mid-sprint product. You have a brochure.

**Day 7.** Gatekeeper review of the boundary card and the go-live card, risks first. Decide, in writing:

- **Continue to payment week** if the promise is true and visible.  
- **Shrink** if the core task is only half-true; cut scope the same day.  
- **Wait** if you discovered a Book 1 hole (the job is mush, the priced promise was theater). Waiting is a legal verdict. Shame is not required; dating it is.

A seven-day compress ends here only if payment was already sandbox-green *and* you scheduled entitlement tests in days 4–6. Otherwise a seven-day compress that “skips payment until later” is a one-week brochure.

---

## Days 8–10 — Pipe, Sandbox, Entitlement

**Day 8.** Fill the payment-channel card (Chapter 6). Five filters. Net proceeds on one typical order. Primary applied. Backup at least started. Isolation declared. Domestic line on or off, on purpose.

**Day 9.** Sandbox keys on the host. Event names filled with vendor text. Webhook endpoint public, not a laptop.

**Day 10.** Webhook acceptance sheet (Chapter 7): pay, replay, fail, refund. Recurring stays off unless renewal-day grants are also tested. Cancel and contact visible in the product.

Done when: the acceptance sheet is ticked, or the verdict has already moved to wait / shrink because the pipe cannot legally or practically be tested this window.

Anti-pattern: Day 10 spent collecting processor logos for the footer.

---

## Days 11–12 — Abuse Hook, Security Sweep, Switch Playbook

**Day 11.** Rate or shrinking gift on any expensive verb. A first pass of the fraud tool on the pipe. Notifications for disputes turned on, not left at dashboard defaults.

**Day 12.** Version check against *current* vendor advisories for the framework you actually run. Write the switch playbook: who the backup is, how SKUs map, how entitlements would point at a new event source, how you would talk to users, and what cash buffer a freeze would require. It can be one page. It cannot be “TBD.”

Done when: the red-line sheet from Chapter 8 has fewer than three empty required boxes, or the empty boxes are named as reasons to wait.

---

## Days 13–14 — Invite, Observe, Verdict

**Day 13.** Invite only the people you meant to invite. If you already took pre-sale money in Book 1, this is the week you stop hiding. Fulfill or refund; do not add a third option called “soon.” Watch events. Read mail. Do not spend the day inventing a canvas.

**Day 14.** Write the verdict.

| Verdict | You may say it when | You must also |
| --- | --- | --- |
| **Ship** | Promise is completable once at the canonical host; curl is honest; webhook acceptance is green; mailbox is read; red lines are mostly ticked | Date the known holes (support load, backup still in review, encoding fixtures still thin) |
| **Shrink** | The loop works only if you cut a lie (a feature on the homepage that is not done, a recurring toggle you cannot test) | Cut the same day; set a new date |
| **Wait** | A hard blocker: no legal pipe, a safety issue, a Book 1 hole, a serious unpatched hole, identity you will not falsify | Say what would change your mind; do not “soft wait” in public as if you had shipped |

Done when: the verdict is in a file with a date, and anyone on the team can find it.

---

## Printable Two Weeks at a Glance

| Day | Focus | Exit tick |
| ---: | --- | --- |
| 1 | Carry-forward + boundary card | Hero and core task in writing |
| 2 | Selection + honesty field + host | Preview URL, secrets fail boot |
| 3 | Domain + mailbox | Both-side bind; support@ receives |
| 4 | Homepage is the backlog | Tired person can repeat the broom |
| 5 | First touch + curl | Hero visible in first HTML; events fire |
| 6 | Core task once, honest fixtures | Preview matches delivery |
| 7 | Mid-sprint gate | Continue / shrink / wait in writing |
| 8 | Channel card + net proceeds | Primary applied; backup started |
| 9 | Webhook hosted | Vendor event names filled |
| 10 | Acceptance tests | Pay / replay / fail / refund |
| 11 | Abuse + fraud tool + alerts | Expensive verb bounded |
| 12 | CVE line + switch playbook | One-page restore plan |
| 13 | Invite and fulfill | Mail read; no “soon” third option |
| 14 | Verdict | Ship / shrink / wait, dated |

---

## Seven-Day Compress (Only If Already Warm)

Use this only if a host, a domain, and a sandbox pipe already exist, and you have run this method before.

| Day | Merge |
| ---: | --- |
| 1 | Boundary, selection, honesty, preview |
| 2 | Domain, mailbox, homepage, curl, first touch |
| 3 | Core task + mid-gate |
| 4 | Channel card + hosted webhook |
| 5 | Acceptance tests + abuse hook |
| 6 | Switch playbook + CVE line + invite |
| 7 | Verdict |

If Day 1 begins with “we still need to buy a domain,” do not compress. You are bargaining with the calendar, not shortening work.

---

## What If the Sprint “Fails”?

A wait or a shrink is not a failed character test.

It is a cheaper tax than a public lie. Write what you learned in the same tone you would write a Book 1 kill: dated, specific, without a pep talk. If you collected money you cannot fulfill, refund promptly. The sprint’s dignity is the artifact, not the launch announcement.

If the only thing you learned is “we needed two more weeks for the editor,” you probably failed the boundary card on Day 1 and then ignored it. The next sprint starts with a smaller promise, not a larger calendar.

---

## Worked Sprint Narrative (Composite Week, Not a Case Study)

The following is a teaching sketch in the same composite as Book 1’s Thursday markup export. Invented names and `example.invalid` URLs. Not a report of revenue.

**Day 1–2.** The builder tapes the job one-liner to the monitor and writes “no editor” on forbidden_scope again. The boundary card keeps: submit messy markup, preview repaired names, download a packet, one credit after payment. The selection card keeps the template shell. Parser libraries still run on the fixture. Preview URL: `https://thu-packet-preview.example.invalid`.

**Day 3–5.** Apex domain binds. `support@` forwards. The hero becomes “Get a Thursday-ready export whose client names stay readable.” `curl` shows that sentence. First touch freezes a `reddit` parameter from a test link.

**Day 6–7.** A fixture with a non-ASCII client name survives the download. Mid-sprint gate: continue, with a risk that support will see encodings not in the fixture.

**Day 8–10.** No company yet, so the channel card picks a merchant-of-record sandbox (unnamed here on purpose) and starts a second application. Napkin net proceeds on a $29 credit pack — a teaching sticker, not a recommended price — after fees and a reserve. Pay / replay / fail / refund tick green. Recurring stays off the page.

**Day 11–12.** Two free exports, then a shrink to a watermarked preview if the same path repeats too fast. Framework version checked against this week’s advisory. Switch playbook: one page, SKU map, a sentence for users if checkout changes, a note that a freeze would pause new packs.

**Day 13–14.** Three depositors from Book 1 are mailed a real URL. Two finish a packet. One refund is issued because the third’s file type was never in scope — a homepage typo, cut the same day (shrink, then ship the narrower promise). Verdict file dated: **ship, with a thinner format list and a backup still in review.**

Nothing in that sketch is a forecast of what your fourteen days will earn.

---

## FAQ (Sprint)

**Can I start Week 2 first because payment is scary?**  
You can rehearse a sandbox, but you may not take live money for a promise that is not completable once. Fear of payment is not a reason to polish a cathedral.

**What if a depositor wants the editor after all?**  
It stays on later/no unless you rewrite the job one-liner and treat that as a new demand event. Price is not a hall pass.

**What if the backup pipe is still in review on Day 14?**  
You may still ship on the primary if the switch playbook is written and the risk is named. You may not pretend the backup exists.

**What if curl is clean and nobody comes?**  
That is a traffic or demand question (Book 1 or Book 3), not a reason to add features on Day 13. Record it. Do not decorate.

**What if we can only work nights?**  
Keep the order; stretch calendar dates, not the ticks. A “two-week” sprint that takes eighteen calendar days is still a two-week sprint if the ticks are honest. A fourteen-day calendar with half the ticks is not.

---

## Sprint Anti-Patterns (Quick List)

- Renaming the repo instead of attaching DNS.  
- Four processor logos, zero refund tests.  
- “Temporary” production data in preview.  
- A language toggle with empty files.  
- Buying ads on Day 5 to “have something to look at.”  
- A mid-sprint migration “while we wait for KYC.”  
- Calling a shrink a ship in a launch post.  
- Inventing a KYC story because the calendar is tight.

---

## After the Verdict — File Hygiene

Keep, in one folder:

- Boundary, selection, address, channel, webhook, switch, go-live cards (dated).  
- The verdict paragraph.  
- A short list of holes you already admitted.  
- The Book 1 pack, unchanged unless the job itself changed.

If the verdict is ship, Book 3 — *Buy Time, Not PMF* — is allowed to talk about channels and buying time. It is not allowed to become a way to paper over a core task that still fails on Thursdays.

If the verdict is wait or shrink, Book 3 will not save you. Stay here, or return to Book 1 if the job itself dissolved.

---

## Bridge to Book 3: *Buy Time, Not PMF*

Book 2 ends when a stranger can finish the promise once, and when money — test or real — can complete the loop without mythology.

Book 3 starts where builders get noisy: channels, ads, the temptation to treat a click-through rate as product-market fit. It will argue that you should own one or two channels, and that ads buy time, not a verdict on the job.

If you catch yourself buying traffic on Day 5 of this sprint, you are reading Book 3 fanfiction inside a Book 2 calendar. Close the ad tab. Open the go-live card.

### What to carry forward unchanged

- Risks before conclusions.  
- Cases as shapes, not prophecies.  
- Forbidden scope as a living document.  
- Payment as an asset with a switch plan.  
- Launch as feedback, not a graduation gift.

### What Book 3 will challenge

Attention must be bought or earned without mistaking it for a product that works. Time can be purchased. Fit cannot. The next book is about that distinction. It is not a license to reopen the cathedral.

---

## One Page You Could Tape Above the Monitor

```text
SHIP-AND-COLLECT
Promise (one sentence):
Core task (once):
curl shows the promise: yes / no
Webhook acceptance (pay/replay/fail/refund): yes / no
Mailbox read: yes / no
Backup pipe: applied / started / absent (name the risk)
Red lines missing:
Verdict (day 14): ship / shrink / wait
Date:
```

---

## Takeaway

**Rule:** Two weeks, one promise, one completable task, one tested entitlement, one written verdict. Shrink and wait are adult results.

**This week (or these two):** Run the calendar in order. Pin the eight sprint rules. Do not buy traffic as a substitute for ticks.

**Not a promise:** A finished sprint does not guarantee users, approval, or net proceeds. The composite Thursday narrative is a teaching sketch, not a scoreboard you should try to hit.
