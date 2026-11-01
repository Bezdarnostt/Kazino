## 2025-05-18 - Standalone Game Form Labels and Live Regions
**Learning:** In standalone lightweight HTML/JS games with dynamic UI updates, bare inputs lack programmatic labels for screen readers and dynamic status updates (like balance and game outcome messages) are silently ignored unless marked with `aria-live="polite"` and `role="status"`.
**Action:** Always wrap or associate inputs with explicit `<label for="...">` elements and assign `aria-live="polite"` to dynamically updated gameplay messages and score counters.
