# UTT — Used Towing Trends

A market intelligence tool for the used tow-truck marketplace: trade-in appraisals grounded in real comps, a market dashboard, a searchable weekly inventory workbook, and an inventory map covering the US and Canada.

Built from ~1,700 used tow truck listings pulled across 8+ marketplaces (including verified sold prices from Ritchie Bros auctions), enriched with NHTSA VIN-decode data and live open-recall checks.

## Running it

This is a single self-contained `index.html` — no build step, no server. Open it directly in a browser, or serve the repo root with GitHub Pages.

Note: the CSV export button in the Weekly Workbook relies on a Claude Artifact-specific capability and won't be available when running outside claude.ai (e.g. here on GitHub Pages) — everything else works identically.
