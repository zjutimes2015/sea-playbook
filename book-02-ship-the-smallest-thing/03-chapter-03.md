# Chapter 3 — The Homepage Promise Is the Backlog

The first paid tester for Thursday Packet opened the site on a Wednesday night.

She did not want a tour. She wanted to know, in one screen, whether Thursday would hurt less. The homepage hero said “All-in-one workspace for modern design teams.” A second fold listed eight features, two of which did not exist. The export path — the only sentence she had paid for — lived behind a menu labeled **Tools**, then **Workspace**, then **Advanced**, then a muted link: *Legacy export (beta).*

She wrote to the domain’s consumer Gmail, which bounced because there was no domain mailbox. She left.

The builder, looking at a heat map that did not exist yet, said the usual sentence: “People will find it once we add onboarding.”

They will not. Not in the way you think. A stranger believes the first honest sentence they can read. If the first sentence is a costume, the product is a costume. The backlog is not a ticket list in a side panel. The backlog is the promise on the homepage, and only the work that makes that promise completable once.

---

## What Must Be There (and What May Wait)

The handbook compresses a launch SOP into a table that is more useful than most roadmaps. I will translate it into the language of this book. It is a teaching sequence, not a certification.

| Stage | Must have | May wait |
| --- | --- | --- |
| Shell | A running template or repo; theme can be ugly | A perfect design system |
| Environment | Database, login (Google-first is a common overseas default), secrets in the host — not in Git | A complete permission matrix |
| Deploy | Git host → hosted platform, repeatable from a commit | Multi-region, blue-green, a private mesh |
| Landing page | One primary promise; enough indexable text; placeholder images allowed | A polished demo reel of features you have not shipped |
| Policy pages | Working links for terms, privacy, and basic identity | Law-firm custom prose on day one (regulated categories may require more — ask a lawyer, not a template README) |
| Analytics | A page tool plus a behavior tool you will actually open (handbook teaching stacks often mention a GA-class tool plus a session tool) | A perfect warehouse |
| Domain | Canonical basics, a sitemap that can start with the important URLs, a Search Console property | A flood of thin URLs |
| Capability | **The homepage promise, finishable once** | “We might need this later” neighbors |
| Payment | Price visible when you are ready to charge; callback and entitlement tested | The globally optimal mix of processors (Chapter 6) |

Read the table as a fence, not as a shopping list you must buy in full before Monday. The fence says: if a row in the left column is empty, you are not waiting on taste. You are waiting on the loop.

---

## Definition: Observable, Not Merely Small

**Definition.** An MVP in this book is three things at once:

1. An **indexable promise** — a stranger and a crawler can both see what you claim.  
2. **One core task** that can be completed once without you on a video call.  
3. **Observability** — you can tell that the task was tried, failed, or finished, and (once money is in play) whether the entitlement landed.

**Boundary.** “Minimum” is not a contest to delete buttons until the screenshot looks brutalist. A three-button app that cannot finish the Thursday packet is not small. It is incomplete. A twenty-page app whose only working path is the packet *can* be a smallest ship if the other pages are honestly marked later — or, better, not shipped.

YAGNI applies to the later list. KISS applies to the path. Neither rule is a license to ship a lie.

---

## The Feature Gate

**Risks**

1. The homepage promises “one-click clean packet,” but the capability is a deep-link Easter egg.  
2. Features expand sideways until the keyword and the promise drift apart.  
3. “Just one more adjacent tool” quietly becomes Editor X.

**Suggestions**

1. Find the thinnest API or library that performs the core verb (for Thursday Packet: parse, fix names, fill, export). Wire the **basic** capability first.  
2. Walk a comparable site’s mainstream path before you invent a clever one. Open-source and competitor honesty is still in force.  
3. Put the capability on the homepage. A boutique tool site often lives or dies by that visibility. A buried beta link is a way to avoid being judged.  
4. Replace placeholder images with real output samples when you have them. Samples serve trust. They still do not guarantee conversion. Never caption a sample as “typical results.”

**Conclusion.** MVP equals indexable promise plus one complete core task plus observability. Everything else is YAGNI until the loop is green.

For Thursday Packet, the core task is: upload or connect the messy markup, get a packet whose client names survive, download it, and (if they paid) have the credit decremented exactly once. Comments, version history, an AI rewrite assistant, and a collaborative canvas are souvenir-lot items. They can be written on a later list. They cannot sit in front of the packet.

---

## Login and Chat Are Friction Sensors, Not Costumes

A common overseas default is “sign in with Google first.” The handbook also discusses a one-tap prompt that reduces the redirect bounce, and a lightweight chat widget (one teaching name is a common European chat box) so early users can report a fatal bug without writing an essay.

**Risks.** Dropping authentication “to move fast.” Promising reply times you cannot keep. Blaming the widget when the one-tap prompt never shows, when the real issue is a domain allow-list.

**Suggestions**

| Capability | Teaching point | Gate |
| --- | --- | --- |
| Google sign-in | Get the boring path working | Domain and redirect URIs complete; test on the real host, not only localhost |
| One-tap style prompt | Less redirect theater | If it does not appear, check origin allow-lists first, not the component library |
| Small chat or mail entry | Lowers the cost of a fatal-bug report | Early on, this often beats “just leave an email.” Do not advertise a support SLA you do not run |

**Conclusion.** You may reduce friction. You may not blur authentication or privacy baselines. A chat box is a sensor. It is not a marketing slogan, and it is not a substitute for a domain mailbox (Chapter 4).

If Thursday Packet can run a first export without an account, that can be legitimate — Chapter 7 will talk about guest checkout — but the backend still has to bind the work and the payment to an entitlement. “No login” is not “no memory.”

---

## Forbidden Scope Is a Living Document

Book 1 asked you to keep a forbidden_scope list next to the job one-liner. Book 2 is where that list gets tempted.

Every request from a friendly tester will sound reasonable. “Could it also comment?” “Could it also be a light editor?” “Could it also store our whole design system?” Reasonable requests are how Editor X re-enters through the side door.

The rule is mechanical:

- If the request does not help the job one-liner complete once, it is **later** or **no**.  
- If it contradicts forbidden_scope, it is **no**, even if a tester will pay a little more for it. Price is not a hall pass to blow the wedge.  
- If you accept it, you rewrite the homepage promise the same day. A promise that is not allowed to change while the backlog changes is how teams learn to lie.

Write the decision down. Public later/no lists are cultural hygiene, the same as public kills in Book 1.

---

## A Worked Boundary Card (Composite)

```text
MVP BOUNDARY — Thursday Packet  date: 2026-11-10

Homepage promise (one sentence):
  Get a Thursday-ready export whose client names stay readable.

Core task (once, no video call):
  User submits a messy markup file → sees a preview of repaired names
  → downloads a packet → (if paid) one credit is used and shown.

In for the two-week window:
  - Promise sentence and short how-it-works
  - Fixture-tested encoding path
  - Google login + optional guest start
  - Domain, mailbox, analytics with first-touch bind
  - Test payment → webhook → export credit
  - Visible cancel / refund contact
  - Terms and privacy links

Out (forbidden or later):
  - New editor canvas
  - Comment threads
  - AI rewrite of client comments
  - Team permissions beyond “one owner, one workspace”
  - Multi-language UI (English first; Chapter 5)
  - Second processor logo “for trust”

Risks (≥3):
  1) Preview lies (looks fixed, download is not).
  2) Credit decrements twice, or never.
  3) Support load from encodings not in the fixture.
  4) Homepage still talks like a workspace suite.

Suggestions:
  Preview must be generated from the same bytes as the download.
  Webhook acceptance sheet before any real charge (Chapter 7).
  Expand fixtures weekly; do not pretend completeness.
  Rewrite the hero until a tired person can repeat the broom.

Conclusion: Conditional pass.
Conditions: preview/download parity test; entitlement test; hero rewrite before traffic.
```

This is a teaching sketch. It is not a claim that a product named Thursday Packet exists or earns.

---

## Where Promise-Driven Scope Falsifies Itself

The homepage-as-backlog rule fails when:

- The real job is a bundle that cannot be demonstrated in one task (a marketplace with two sides, for example). Then the smallest ship is still *one* completable side of the loop, honestly labeled. Do not use the bundle as an excuse to ship two half-sides.  
- Safety requires friction the homepage would rather hide (age gates, generation moderation, irreversible payments). Put the friction in the path. A smooth lie is not a smallest ship.  
- You keep rewriting the hero to match whatever you built this afternoon. That is the Inspiration Wall in a new font. Change the promise only when the job one-liner changed, and treat that as a demand event, not a copy tweak.

---

## Promise Drift: A Fifteen-Minute Diagnostic

Once a week, even inside the sprint, read the homepage aloud and then complete the core task as if you were unpaid and slightly impatient.

Ask:

1. Does the first sentence still match the job one-liner from Book 1?  
2. Can you finish the task without opening a “docs” tab the team wrote for themselves?  
3. Does any nav item or screenshot advertise a later/no item as if it were present?  
4. If a depositor forwarded only the hero sentence to a colleague, would that colleague be surprised by what actually runs?

If you fail two of the four, you do not have a copy problem. You have drift. Fix it the same day: rewrite the hero, hide the lie, or formally change the job (which is a demand event, not a polish task).

A screenshot folder of “what the homepage looked like on Day 4, Day 7, and Day 14” is a cheap honesty device. If the sentence got vaguer as the days passed, the cathedral is leaking in through adjectives.

---

## FAQ (Homepage as Backlog)

**Is a waitlist page a homepage promise?**  
Only if the waitlist states a priced broom you already sold or are honestly pre-selling, and does not imply a working button. A waitlist that talks like a shipping product is advertising fiction (Chapter 1’s boundary).

**Can the core task live in an authenticated app if the homepage is marketing?**  
Yes, if the homepage says so, and if a signed-in tester can still finish once without a tour. “Marketing site plus hidden app” fails when the app’s first screen is a suite and the broom is again under Advanced.

**What if legal needs a longer disclaimer than the hero?**  
Put the hero first and the disclaimer adjacent and readable. Do not hide the broom under a paragraph of fear, and do not hide the risk under a peppy slogan.

**What if testers keep asking for a tour anyway?**  
Record the sticking point as an event class. Improve the one path. A tour video is a later tool, not a substitute for a path that cannot be finished silently.


## Takeaway

**Rule:** The homepage promise is the backlog. MVP means an indexable promise, one complete core task, and the ability to see what happened.

**This week:** Write the hero in one sentence. Put the capability on that page. Move everything else to later/no. Make a boundary card with three risks.

**Not a promise:** A visible promise does not guarantee conversion. Samples and chat boxes are instruments, not revenue spells.
