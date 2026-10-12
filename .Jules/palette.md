## 2024-10-12 - Explicit Labels and Live Regions for Plain HTML Games
**Learning:** Standalone HTML slot machines in this repo had form inputs without explicit `<label for="...">` associations and dynamic game messages without `aria-live="polite"`.
**Action:** Always link form labels to input IDs and mark dynamic message containers as `role="status" aria-live="polite"` so screen reader users receive instant audio feedback when balance/game status changes.
