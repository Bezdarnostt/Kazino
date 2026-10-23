## 2026-10-23 - Form Labels & Live Region Accessibility in HTML Slot Machine
**Learning:** Raw HTML forms without explicit `<label for="...">` associations prevent screen reader users from identifying inputs. Dynamic message areas updating game status require `aria-live="polite"` so screen readers announce outcomes when balance/results change without interrupting speech.
**Action:** Always wrap form input text in explicit `<label>` elements linked to input IDs and ensure dynamic status elements are marked with `aria-live="polite"`.
