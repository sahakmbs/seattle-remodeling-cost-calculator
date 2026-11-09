# Seattle Remodeling Cost Calculator 2026

Static GitHub Pages site for **Seattle MasterFix Precision Craftsmanship**.

## What it does

Visitors pick a remodel project, enter size when it applies (sq ft / linear ft / units), choose a finish level, and see:

- A MasterFix estimated range
- The Seattle market midpoint for comparison
- A link to the matching guide on [seattlemasterfix.com](https://seattlemasterfix.com/)

Prices come from `Seattle_Remodeling_Costs_2026.csv` / `price_bands_2026.md` (live MasterFix bands).

## Status

Published Nov 9, 2026 with Bill's approval: https://sahakmbs.github.io/seattle-remodeling-cost-calculator/ (repo: https://github.com/sahakmbs/seattle-remodeling-cost-calculator). Prices are the v3 bands from `price_bands_2026.md`.

## Local preview

```bash
cd calculator-site
python3 -m http.server 8080
# open http://127.0.0.1:8080/
```

## Deploy

1. Create a public repo (suggested name: `seattle-remodeling-cost-calculator`).
2. Push the contents of this folder to the default branch.
3. Enable GitHub Pages (Deploy from branch → `/` root).
4. Optional custom domain later; canonical points at `https://sahakmbs.github.io/seattle-remodeling-cost-calculator/` (live).

## Files

- `index.html` — calculator UI, FAQ, LocalBusiness/GeneralContractor JSON-LD
- `logo.svg` / `logo.png` — official navy brand mark
- `.nojekyll` — skip Jekyll processing on GitHub Pages

## NAP

Seattle MasterFix Precision Craftsmanship · 5415 6th Ave NW, Seattle, WA 98107 · (206) 550-4576 · WA L&I SEATTMP744NL
