# Complaint Ledger

Companion template for *Complaints, Not Inspiration* (Chapter 3).  
One row = one source artifact (thread, review cluster, help post, request-board item).  
Empty fields are allowed and informative—especially `paid_clue` and `risk`.

**Signal filter (all three, or mark what’s missing):** already using · frequency · gap

---

## Four questions (required spine)

| # | Question | What to write |
|---|----------|----------------|
| Q1 | Top concentrated complaints | Up to 3 themes in the user’s words |
| Q2 | Substitutes mentioned most | Tools, humans, manual workflows, “do nothing automated” |
| Q3 | Tool-shaped opportunities | Smallest wedge that removes the fire—not a category reboot |
| Q4 | Payment clues | Quotes/links to willingness-to-pay, existing paid tools, VA/agency spend—or `none yet` |

---

## Row fields

Copy one block per source.

```text
## Ledger row — YYYY-MM-DD — short theme label

source_url: 
source_type:  # reddit | plugin_review | discord | request_board | support | other
captured_at:  # ISO date
vertical / community: 

# Three-part signal (yes / no / unclear)
already_using: 
frequency: 
gap: 
gap_one_liner:  # expensive | hard | heavy | missing scene | unstable | other — in concrete words

# Four questions
q1_top_complaints: 
  - 
  - 
  - 
q2_substitutes: 
  - 
q3_wedge_opportunity: 
q4_payment_clues: 

# Honesty fields
repeat_count:  # independent times you’ve seen this theme (update as you go)
paid_clue:  # quote/link OR "none yet"
open_source_gap:  # what exists (e.g. GitHub) / why not just use it / "not checked"
risk:  # at least one reason this row might be noise or unbuildable

# Decision
status:  # noise | watch | theme | killed | fire_test_next
kill_reason:  # if killed
notes: 
```

---

## Theme roll-up (optional weekly sheet)

| Theme | Sources (n) | Repeat count | Paid clue? | Open-source gap | Risks (≥1) | Status |
|-------|-------------|--------------|------------|-----------------|------------|--------|
|       |             |              |            |                 |            |        |

**Stopping rules**
- Stop collecting when new rows stop changing the top 3 complaints for a theme.
- Do not promote a theme with empty payment clues after a deliberate substitute/pricing look—mark `watch` or run a priced pre-sale instead of building.
- Do not jump from theme → six-month architecture; next step is fire test / sell air.

**Not a promise:** A full ledger does not guarantee revenue. It improves the odds you kill fake demand before it becomes a roadmap.
