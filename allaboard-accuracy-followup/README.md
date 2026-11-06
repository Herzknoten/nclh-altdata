# All Aboard accuracy follow-up
Checks price labels, broad repricing dates and the shape of price changes in 2027 departure cohorts.
Source: `full-2026-09-14` and saved All Aboard pages labelled 2026-09-12.
Prices are USD per person per night; comparisons use sailing and cabin units, grouped by line and date.
`out/u1_label_counts.csv` preserves `exact_string`, `topics`, `occurrences` and `pages`; `out/u1_sample.csv` identifies sampled pages.
`out/u2_event_summary.csv` reports `median_change`, eligible `units` and shares moving more than 5% around 2025-11-05.
`out/u3_path_summary.csv` groups paths by `shape`; daily-step and decline-date CSVs retain timing and coverage denominators.
Methods compare paired windows and distinguish gradual, single-step and reversing paths; `out/run_manifest.json` records inputs.
Price paths cannot identify whether promotions, fare-tier changes or inventory releases caused a move.
