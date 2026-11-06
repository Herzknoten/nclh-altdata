# Re-cuts by departure cohort

All Aboard asking-price histories through November 4, 2026, combining September, October and November exports.
The unit is a sailing and cabin category, grouped by departure month and lead at the first observed cut.
Key columns include `line`, `lead_band`, `departure_month`, `n_units`, `recut_share_pct` and `median_rel`.
A first cut is at least 5% below the first observed daily ask; a re-cut is a further 10% within 90 days.
Compare September 2026-March 2027 with April-December 2027 within lead bands, giving observed months equal weight.
See `monthly_by_line_band.csv`, `group_summary.csv`, `contrasts.csv` and `run_manifest.json` for coverage and support.
