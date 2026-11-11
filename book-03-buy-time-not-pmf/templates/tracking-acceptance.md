# Tracking-acceptance sheet (blank)

Treat this like a webhook test. Hope is not a test. No spend while this sheet is red.

```text
TRACKING ACCEPTANCE — product:          date:

[ ] First touch still readable (source / medium / campaign)
[ ] Sign-up event fires once, and only once, for a real sign-up
[ ] Purchase event fires on a real or sandbox payment
[ ] Purchase includes value and currency
[ ] A failed, canceled, or refunded payment does not remain a purchase
[ ] Analytics lists purchase as key; sign-up is helper if used
[ ] Ads account: purchase primary, sign-up secondary
[ ] A test click with a UTM arrives and is visible end to end
[ ] Community (or other non-search) ads have their own UTM and are
    not blended into a search total

Value-parameter checks:
  [ ] Trial or coupon does not record 0.00 as a teacher
  [ ] Currency matches the price the buyer saw
  [ ] Tax treatment is consistent
  [ ] Thank-you reloads do not duplicate the event

Pay / replay / fail notes:

Risks still open:
  1)
  2)
  3)

Suggestions:

Conclusion: Pass / Conditional pass / Reject
```
