# End-Grain Board Planner

Design an end-grain cutting board pattern, pick wood species, and get a material
cut list, a step-by-step cut plan, and a downloadable build guide — all in one
self-contained page, no install and no backend required.

Live site: https://zo718.github.io/end-grain-board-planner/

Built by Zo718 with the help of Claude.

## Changelog

### 2026-09-01
- Renamed "Strips/board" to "Fit per board" in the Boards to buy table, so it reads as capacity vs. requirement instead of two similar-looking labels.
- Replaced the "Leftover strip" figure with "Strips needed" — the old number counted a whole board's un-ripped width as if it were wasted material; now it's obvious at a glance why one board (or several) covers a design.

### 2026-08-31
- Added a **Boards to buy** section: a per-species table showing how many raw boards to purchase, based on your actual Stock length, width and thickness — a more literal companion to the board-footage-based Material estimate.
- Added a **Stock width** input (with 5"/6"/7"/8" presets), plus quick-select presets for **Stock length** (24"/48"/96") and **Stock thickness** (1"/2", now defaulting to 3/4" for dressed/S4S lumber).
- Added a "Planning on dimensional lumber?" heading above the stock inputs.
- Fixed numeric table headers rendering left-aligned while their values sat right-aligned underneath — headers now line up over every data table on the page.
- Reordered the page so Boards to buy sits right after Edge-grain vs. end-grain, ahead of the cut plan (in both the on-page layout and the PDF/print guide).

### 2026-08-28
- Reworked the wood-grain texture rings drawn on the board preview to be larger and clipped to each square's edges, closer to how real end-grain growth rings look.

### 2026-08-25 — Initial release
- Stock thickness input, so material estimates reflect the lumber you're actually buying instead of a fixed 3/4" assumption.
- Common board size quick-select chips (12×18", 18×24", 24×36").
- New original "Woven Diamond Inlay" pattern.
- Illustrated, click-to-zoom step icons for the cut plan, colored to match each design's actual wood species.
- Edge-grain vs. end-grain visual comparison.
- One-click downloadable PDF build guide, generated entirely client-side.
- Deployed as a standalone site on GitHub Pages.
