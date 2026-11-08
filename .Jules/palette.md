# Palette's UX Journal

## 2026-11-08 - Accessible form labels and live feedback in standalone web games
**Learning:** In standalone lightweight HTML/JS game interfaces, inputs are frequently rendered with plain text nodes next to `<input>` controls instead of explicit `<label for="...">` associations, which breaks screen reader accessibility and prevents clicking labels to focus inputs. Additionally, dynamic game status messages (e.g., win/loss) lack ARIA live regions (`role="status" aria-live="polite"`), preventing non-sighted players from hearing spin outcomes.
**Action:** When updating standalone slot machine or game interfaces, always wrap input descriptions with `<label for="...">`, attach `role="status"` and `aria-live="polite"` to the announcement banner, and pair `:hover` styles with `:focus-visible` outlines.
