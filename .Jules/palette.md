## 2026-10-20 - Standalone HTML Live Regions and Input Labeling
**Learning:** Standalone HTML slot machine components lacked explicit label tags for inputs (`initialBalance`, `bet`, `slotsCount`) and dynamic status announcements for `#message` and `#balance`. Adding `aria-live="polite"` and explicit `<label for="...">` elements significantly improves screen reader usability for fast state updates.
**Action:** When working on standalone HTML apps, ensure form controls are explicitly associated with labels and live regions are designated with `aria-live="polite"` for dynamic gameplay updates.
