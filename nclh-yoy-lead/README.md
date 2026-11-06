# Year-over-year prices at comparable lead times
Monthly comparisons of 2027 and 2026 cruise asking prices, separating exact lead matches from modeled adjustments.
Source: All Aboard `full-2026-09-14`, with observations restricted to 2025-10-06 through 2026-09-12.
The unit is a sailing and cabin; price levels are USD per person per night and changes are percentages.
`out/headline.csv` includes scope, month, cabin, line, method, change_pct, dollar levels, sample counts and interval_reason.
`out/coverage.csv`, `out/overlap.csv` and `out/exact_yoy.csv` document support and exact same-lead comparisons.
The revised headline holds common ship, embark port, exact nights and cabin support fixed and normalizes observations to a common supported lead.
Peer pooling holds brand weights fixed; sailing-cluster bootstrap intervals carry coverage limits into the comparisons.
`out/broad_matching_sensitivity.csv` and `out/same_ship_yoy.csv` preserve alternative comparisons; input fingerprints record provenance.
Missing support and unavailable intervals remain blank; modeled lead adjustments and OTA asking prices are not realized fare comparisons.
