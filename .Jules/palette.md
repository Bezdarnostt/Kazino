## 2026-10-26 - Standalone HTML accessibility improvements
**Learning:** Simple HTML/JS widget applications often lack explicit form labels and ARIA live regions for dynamic score/balance/status updates, leaving screen reader users without feedback on game state changes.
**Action:** Always link form controls with explicit `<label for="...">` tags and add `aria-live="polite"` to dynamic text containers (like balance or message displays).
