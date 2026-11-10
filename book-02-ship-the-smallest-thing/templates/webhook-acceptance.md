# Webhook acceptance sheet (blank)

A payment has not landed until the entitlement has landed. Replays must be idempotent.

```text
WEBHOOK ACCEPTANCE — product:          date:

Environment (sandbox / production): keys location:

Vendor event names mapped to jobs:
  payment succeeded:
  payment failed:
  refunded / disputed:
  recurring renewal (or “off”):

Tests:
  [ ] Pay → entitlement + dashboard + mail agree; first touch still frozen
  [ ] Replay → no double grant
  [ ] Fail → no grant; visible message
  [ ] Refund or void → written policy happens
  [ ] Recurring renewal (or explicitly off the page)

Fail Fast (signature, bind, environment mismatch):

Evidence log fields:

Risks (≥3):

Suggestions:

Conclusion: Pass / Conditional pass / Reject
Conditions:
```
