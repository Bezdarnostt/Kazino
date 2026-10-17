## 2025-10-17 - Dynamic Game State Live Regions & Form Labels
**Learning:** Static HTML game components that update messages dynamically (such as win/loss notifications) require explicit `aria-live="polite"` and `role="status"` attributes for screen readers to speak results without page reloads, along with explicit `<label for="...">` associations for input fields.
**Action:** When working on standalone HTML mini-games, ensure dynamic status outputs have live region attributes and all numerical input controls are properly linked to `<label>` tags.
