## 2026-10-08 - Accessible form labels and live regions in HTML slot machine UI
**Learning:** Legacy HTML forms lacking `<label>` elements and dynamic content updates without `aria-live` regions hinder screen reader navigation and touch interaction.
**Action:** Always wrap input field labels in `<label for="...">` associated with input IDs and mark dynamic game feedback elements with `aria-live="polite"`.
