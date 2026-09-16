# flightpath-notebooks

Public companion repo for [ML4YOU](https://github.com/andreas-he/flightpath):

- `data/deadlines.json` — the AI-safety programme deadline corpus the app renders
  (programme, deadline, cohort, location, stipend, source). Public facts only;
  regenerated weekly from the maintainer's tracker by a scrubber that never reads
  application state. Consumed by the app over `BRAIN_DEADLINES_URL`.
- `notebooks/` — Colab notebooks for coding exercises (when generation is on).
