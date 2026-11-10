# Chapter 8 — Where Shipping Small Breaks

Every useful method dies in characteristic ways. If you do not name those ways, “ship the smallest thing” becomes a costume for the same old cathedral — only now with a public URL.

This chapter is self-falsification on purpose. Observable delivery, clock-based selection, homepage backlogs, boring addresses, explainable infrastructure, payment assets, and entitlements can each rot. Rotten tools still look like tools. That is why they are dangerous.

Read this as red lines: conditions under which you should **stop using this method as currently practiced** — not as poetic humility at the end of a blog post.

---

## Failure Mode 1 — The Cathedral Before the Loop

**What it looks like:** a component tree for a “real editor,” a design system, a second product line, all while the sold promise is still a muted link. “We’ll launch when it’s ready.”

**Why it breaks:** the loop never starts. Deposits go stale. You learn about your taste, not about Thursday.

**Brake:** freeze work that does not make the homepage promise completable once. Put a date on the first public URL.

**Stop using the method when:** you catch yourself calling an internal demo “launched,” or when “smallest” has come to mean “we will add everything, just in a tighter font.”

---

## Failure Mode 2 — Stack Debate as Procrastination

**What it looks like:** a month of Next versus an edge family, or a sudden self-hosted cluster, while DNS and webhooks wait.

**Why it breaks:** selection stopped being a clock and became a personality. The validation window closes while you audition runtimes.

**Brake:** the selection card from Chapter 2, written, with “no migration during the sprint” as a default. Pilot new infrastructure on a non-critical site.

**Stop using the method when:** the stack conversation is longer than the go-live card.

---

## Failure Mode 3 — The Empty First HTML

**What it looks like:** a beautiful client-rendered shell; `curl` returns almost nothing; the promise lives in a script the team hopes a crawler will execute.

**Why it breaks:** you cannot claim an indexable promise. Some visitors and some reviewers will not wait for the spectacle.

**Brake:** the `curl` test is a required tick, not a suggestion. Downgrade clever empty shells during the validation window.

**Stop using the method when:** you argue that “Google will handle it” as a substitute for a first response that contains the sentence you sell.

---

## Failure Mode 4 — The Single Basket

**What it looks like:** one payment account, every product, no backup application, all revenue behind one login. Or four logos on a page that all resolve to the same untested account.

**Why it breaks:** a dispute spike, a category change, or a security event can pause the business while you still have customers to fulfill. The handbook’s termination-after-incident shape is this failure in public.

**Brake:** isolation plus a started backup plus a switch playbook written before dependency. Time-to-restore beats a souvenir rate card.

**Stop using the method when:** “we’ll apply to a second pipe after we have traction” is the entire continuity plan.

---

## Failure Mode 5 — Receipt Without Entitlement

**What it looks like:** paid in the dashboard, zero in the product. Webhooks pointed at a laptop. Retries double-grant. Refunds never tested.

**Why it breaks:** you have a billing complaint factory, and you will misread silence (or anger) as a demand problem.

**Brake:** the webhook acceptance sheet. Pay, replay, fail, refund. Recurring stays off the page until renewal-day grants are proven.

**Stop using the method when:** “we’ll hook fulfillment after we restyle Checkout” has survived more than one working session.

---

## Failure Mode 6 — Abuse Naivety

**What it looks like:** “only Google login, we’ll be fine”; gift value larger than the cost of a new account; a sudden bill; a permanent IP ban that also hits a paying customer.

**Why it breaks:** bulk accounts exist. Unbounded expensive verbs get farmed. The handbook’s roughly **$30–40** grazing bill is a small shape of a large class. Your number may be quieter, or much worse. It is not a cap.

**Brake:** behavior-level shrinking of gifts; rates on expensive verbs; watch conversion, resource use, and support together. Prefer “not worth farming” over “zero abuse forever.”

**Stop using the method when:** the expensive verb is live and the only control is hope, or when a ban hammer is your first and only tool.

---

## Failure Mode 7 — “We Are Small, So We Are Safe”

**What it looks like:** CPU climbs, visitors do not; the team shrugs (“the code got slower”). A framework CVE is treated as a newsletter item for next month. Quiet sites are used as someone else’s mine.

**Why it breaks:** attackers do not need your brand to be famous. A serious hole can become a bill, a leak, and a payment-platform event (Chapter 7).

**Brake:** when resources climb without visitors, suspect abuse or intrusion first. Inventory affected projects. Compare versions to the *current* vendor advisory — archive version numbers go stale, including any you may remember from an old post (the handbook mentions a specific patched release in one incident; do not copy that number forward as advice). **Upgrade to the stated fixed release the same day.** Then re-check CPU, logs, and the invoice curve. On a self-hosted machine, also rotate secrets and consider a rebuild. Multi-project shops should use the vendor’s batch path so one site is not left behind.

**Stop using the method when:** a serious advisory is “being monitored for a week” because the sprint is busy.

This book does **not** promise that an upgrade rolls back charges or leaves no residue. It promises a sequence that lowers the odds you will still be debating next Friday.

---

## Failure Mode 8 — Cheapest Checkout, Unknown Brand

**What it looks like:** a full cutover to a lower-fee pipe because a spreadsheet won; abandonment rises; the team blames copy; there is no way back.

**Why it breaks:** trust is part of price (Chapter 7). Fees saved can be smaller than sales lost. A questionnaire shape in the handbook — distrust of the method among people who left — is the weather report.

**Brake:** slice, ask, switch-back plan. Keep net proceeds *and* abandonment reasons in the same review.

**Stop using the method when:** rate shopping is allowed to proceed without a trust hypothesis and a rollback.

---

## Failure Mode 9 — Identity Cosplay

**What it looks like:** a form that “has to get through”; a borrowed address; a passport asked to pretend to be a local ID; names that do not match the bank.

**Why it breaks:** this is not a clever tactics chapter. It is how accounts die later, often with balances attached. This book’s veto is simple: if you cannot tell the truth on the form, stop.

**Brake:** real documents, currency alignment, official paths only. Delay is cheaper than a constructed person.

**Stop using the method when:** anyone on the team is brainstorming how to “make KYC easier” by making the answers less truthful.

---

## Failure Mode 10 — Two Countries, One Pot

**What it looks like:** a personal collection code “just for a few domestic friends,” stirred into the same product that charges overseas cards; or a second-clearing agent you have not really inspected.

**Why it breaks:** you scramble legal sellers, settlement, and risk. You also train yourself to treat pipes as a junk drawer.

**Brake:** overseas and domestic lines designed apart. Official or formal onboarding at home; no hanging codes as a business path.

**Stop using the method when:** “we take everything” is achieved by mixing pots you could not draw on a whiteboard.

---

## Failure Mode 11 — Language Theater on Day One

**What it looks like:** six language toggles, two of them empty, one of them a raw machine translation; the default language does not match who actually arrives.

**Why it breaks:** you spend clock on costumes, and you bounce the people who came.

**Brake:** English first when that is the honest market; add languages from evidence; check the default against real arrivals.

**Stop using the method when:** a translation matrix is allowed to delay the core task or the webhook test.

---

## Failure Mode 12 — Using This Book to Skip Book 1

**What it looks like:** a beautiful smallest ship of a product nobody asked for; a pre-sale skipped because “shipping will tell us”; ads bought (Book 3 daydreams) to feed a loop that has no job one-liner.

**Why it breaks:** you built a pretty instrument for silence. Observable delivery of a fake job is still a fake job.

**Brake:** require the Book 1 carry-forward pack before Chapter 9 starts. If it is missing, this book pauses.

**Stop using the method when:** “we’ll validate by shipping” is a way to avoid a priced ask you are afraid to make.

---

## A Red-Line Sheet You Can Tape to the Monitor

```text
RED LINES — Ship the Smallest Thing

[ ] We do not call a laptop demo “launched.”
[ ] We do not migrate the main site during the sprint without a written exception.
[ ] curl must show the promise.
[ ] No single payment basket; backup is an application, not a logo.
[ ] No live traffic without webhook acceptance (pay / replay / fail / refund).
[ ] Expensive verbs have a rate or a shrinking gift.
[ ] Serious CVEs are patched on the vendor’s current advice the same day.
[ ] Checkout changes start as a slice, with a way back.
[ ] No invented identity.
[ ] Domestic and overseas lines stay apart.
[ ] No language zoo in week one.
[ ] No Chapter 9 without a Book 1 verdict (or a dated reason we are only rehearsing).
```

If more than three boxes cannot be ticked, you are not “being pragmatic.” You are practicing the method in costume.

---

## Where Self-Falsification Itself Fails

A red-line chapter can rot into self-hand-wringing that never ships, or into a police ritual that never updates.

**Brake for the brakes:** if a red line is blocking a truly narrower, safer, more honest loop, write a dated exception with risks first. If a red line has not been looked at in six months, it is decoration. Review the sheet at the end of each Chapter 9 sprint, and retire lines that exist only to sound strict.

---

## How to Use This Chapter in a Review

Do not read the twelve modes as a personality quiz at the end of a long week.

Use them as a review agenda. Fifteen minutes, risks first:

1. Each person silently marks the modes they have seen in the last fourteen days.  
2. You compare lists without defense for five minutes.  
3. You pick at most two modes to brake this week.  
4. You write the brake as a tick on a card, not as a speech.

If everything is “a bit of a problem,” nothing will change. Two brakes, dated, beat a confession.

If no one can name a mode, either the team is unusually clean or the method is not being used. The second is more common. In that case, walk Chapter 1 and the red-line sheet before you open Book 3.


## Takeaway

**Rule:** Shipping small has characteristic failure modes. Name them, tape them, and stop using the costume when the ticks go missing.

**This week:** Print the red-line sheet. Walk it with one other person, or with a rubber duck. Write one dated exception if you need it — or none.

**Not a promise:** Avoiding these modes does not guarantee a calm invoice, a passed review, or a converted checkout. It lowers the odds that you will lie to yourself with a public URL.
