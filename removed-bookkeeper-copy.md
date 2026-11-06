# Removed copy: "Bookkeeper-reviewed" (removed 2026-10-19, ET)

Removed from `index.html`, trust section ("Your books stay safe"). Ben approved removing it until a reviewing bookkeeper is lined up. It was the only bookkeeper-review claim on the page; the FAQ, hero and pricing never mentioned it.

## Exact HTML removed (third card in the trust grid)
```html
<div class="card"><div class="icon">🧮</div><div><h3>Bookkeeper-reviewed</h3><p>A bookkeeper checks balances against your trial balance before handoff.</p></div></div>
```

## Related edits made at the same time
- Trust grid changed from `grid g3` to `grid g2` so the two remaining cards stay balanced.
- Card title "QuickBooks left untouched" → "QuickBooks left untouched until you approve". Body now ends with ", and you choose when to cancel."
- "Pay after you check" body now adds "including balances against your QuickBooks trial balance".

## To re-add later
1. Change the trust grid back to `<div class="grid g3">`.
2. Paste the HTML above as the third card.
3. Optional: add a FAQ entry such as "Who checks my move? A [credential, e.g. QuickBooks Online Certified ProAdvisor] bookkeeper reviews balances against your trial balance before handoff."
