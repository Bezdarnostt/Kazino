# Palette's Journal

## 2026-11-04 - Accessible Form Controls and Dynamic Announcements in Standalone HTML Games
**Learning:** Standalone vanilla HTML games often omit basic semantic associations (such as `<label for="...">` tags and live region attributes like `aria-live="polite"`). Screen readers fail to announce dynamic game events like wins, losses, or jackpot payouts without an ARIA live region. Furthermore, keyboard-only users need explicit focus-visible states on interactive buttons and inputs.
**Action:** Always provide explicit `<label for="...">` elements for numerical inputs, add `aria-live="polite"` to dynamically updated feedback containers, and provide clear `:focus-visible` outlines. Keep standalone duplicates like `Kazilnomerodyn` and `kazinodlyapochatkufhdhd.html` strictly synchronized.
