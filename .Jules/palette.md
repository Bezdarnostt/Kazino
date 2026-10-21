# Palette's Journal - UX & Accessibility Learnings

## 2026-10-21 - Accessible inputs and live announcements in standalone HTML slot machine
**Learning:** Legacy HTML slot machine prototypes lacked explicit `<label>` bindings and `aria-live` region announcements for dynamic result messaging, impairing screen reader usability and keyboard focus clarity.
**Action:** Always associate input fields with explicit `<label for="...">` elements, add `aria-live="polite"` on dynamic message containers, and provide clear `:focus-visible` outlines for interactive controls.
