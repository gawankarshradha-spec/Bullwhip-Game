# Bullwhip Run

A short, tap-to-play browser game that teaches the **bullwhip effect** in supply chain management to undergraduate students.

**Play it:** open `index.html` in any browser (no install, no server). If GitHub Pages is enabled for this repo, it is served at `https://gawankarshradha-spec.github.io/Bullwhip-Game/`.

## How it works
1. **Sign in** with username, first name and last name (all required).
2. **30-second briefing** on the bullwhip effect.
3. **Five rounds, one decision each.** You run a store selling ~10 drinks a week. Each round applies one concept: reacting to a one-week spike (forecasting), a late truck (lead time), a bulk discount (order batching), supplier rationing (shortage gaming), and choosing the best fix (information sharing). After each tap, the order ripples up the chain so you see how much the factory ends up making. 20 / 10 / 0 points per round, 100 total.
4. **Extra credit quiz:** 5 questions, 1 point each.
5. **Results and CSV export:** downloads `bullwhip_<username>.csv` with Username, First Name, Last Name, Game Score, Extra Credit, Final Score and Date. Opens directly in Microsoft Excel.

## Files
- `index.html` — the whole game (HTML, CSS and JavaScript in one file).
