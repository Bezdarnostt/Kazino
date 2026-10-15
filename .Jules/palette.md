# Palette's Journal - UX & Accessibility Learnings

## 2026-10-15 - Slot Machine Form Accessibility & Live Region Feedback
**Learning:** Raw input elements without explicit `<label for="...">` associations hinder screen reader usability, while dynamic game result changes need `role="status"` and `aria-live="polite"` so announcements occur naturally without interrupting keyboard flow.
**Action:** Always link form labels explicitly with inputs and mark dynamic status/result containers with `role="status"` and `aria-live="polite"` in slot machine or web game applications.
