# Palette's Journal

## 2024-11-07 - Standalone HTML Slot Machine Form Accessibility & Live Region
**Learning:** For standalone vanilla HTML apps with no frameworks or design systems, input elements nested in plain `div` tags lack `<label>` associations, causing screen reader navigation to read values without context. Additionally, dynamic score/status messages updated via JavaScript need `aria-live="polite"` and `role="status"` to be announced to assistive tech users, and interactive elements benefit from explicit `:focus-visible` styling.
**Action:** When working with vanilla HTML apps, always pair inputs with `<label for="...">`, make dynamic output containers live regions (`aria-live="polite"`), and provide distinct `:focus-visible` outlines.
