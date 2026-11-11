# Palette's UX Journal

## 2026-11-11 - Semantic Labels, Live Region & Initial State in Slot Machine
**Learning:** In simple vanilla HTML games without frameworks, form inputs often lack explicit `<label for="...">` associations and screen readers don't announce dynamic message changes unless `aria-live="polite"` is set. Furthermore, rendering the initial empty/ready slot reels on page load prevents UI layout jumping when the user starts playing.
**Action:** Always provide explicit `id`/`for` label associations, live regions for dynamically updated game status messages, and initialize visual slots on load.
