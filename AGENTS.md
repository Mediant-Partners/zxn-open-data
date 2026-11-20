# zxn-open-data: agent rules

Estate rules: `/Users/ml/_dev/AGENTS.md`. Websites devroot: `/Users/ml/_dev/_websites/AGENTS.md`. Analysis lives in
`Mediant-Partners/zxn-research` (private); this public repo holds only what a study publishes.

- **PUBLIC repo.** Aggregates only. Never a domain, business name, company number, person, prospect, price, raw row, token or
  internal note. Every cell has a count of 10 or more; smaller cells are dropped (not rounded).
- One folder per study: `studies/<id>/` with the CSVs, `DICTIONARY.md` and `METHOD.md` (sample, date, collection, exclusions,
  limits, conflicts, next update). Add a row to the README table.
- The CSVs are written by the study's `analyse.sql` in zxn-research, never edited by hand. The blog's chart reads the same numbers.
- Words follow `_estate/docs/COPY-DOCTRINE.md` and pass `copy-check`; rule 27 tone. Brand "zxn.uk". No em dashes.
- Licence CC BY 4.0 (`LICENSE`). Corrections are noted in `METHOD.md` with a date.
- The orchestrator or the blog publisher worker pushes here, one study at a time.
