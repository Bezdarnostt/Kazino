## 2026-10-30 - Accessible Dynamic Status & Form Labels in Standalone Games
**Learning:** Standalone single-page HTML games often render game messages dynamically without announcing updates to screen readers, and leave form inputs unlinked to labels. Adding `role="status"`/`aria-live="polite"` and explicitly associated `<label for="...">` tags ensures screen reader users hear game status updates and can easily navigate controls.
**Action:** Always verify dynamic status text containers have `aria-live` or `role="status"`, and inputs have matching `for` attributes on `<label>` elements.
