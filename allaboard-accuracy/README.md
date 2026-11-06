# All Aboard accuracy checks
Retained data from an internal audit of All Aboard asking-price quality and comparability.
Source: `full-2026-09-14`, with history from 2025-10-06 through 2026-09-13 and a 2026-09-12 analysis reference date.
Prices are USD per person per night; underlying units are sailing and cabin combinations.
`out/u5_source_mix.csv` groups source hosts and price changes by line, departure quarter and lead band.
`out/u6_external_level.csv` includes `median_asking_pppn`, `reported_ticket_per_pcd` and `asking_to_reported_ratio`.
The external comparison uses positive quotes strictly before departure and reported NCLH ticket revenue per passenger cruise day.
`run_manifest.json` and `checks/` retain provenance and review comparisons; only two of the seven main audit CSVs are retained here.
Asking fares and reported gross ticket revenue have different inclusions and coverage; their ratio is not a yield estimate.
