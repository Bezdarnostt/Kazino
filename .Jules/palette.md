## 2024-10-24 - Standalone HTML Form Input & Dynamic Live Regions
**Learning:** Standalone HTML slot machine inputs were missing associated `<label>` tags and focus-visible indicators, making them difficult for screen reader users and keyboard navigators. Dynamic game status updates in plain `div` elements were silent to screen readers.
**Action:** Always associate `<input>` elements with explicit `<label for="...">` tags, apply visible `:focus-visible` CSS rules for interactive controls, and use `aria-live="polite"` on message containers for real-time game announcements.
