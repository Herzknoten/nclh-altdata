# Monthly occupancy scenarios
This folder combines monthly price signals, listed capacity and quarterly occupancy benchmarks.
Sources are NCLH filings, the September 14, 2026 All Aboard export, and archived 2019 and 2023-2025 seasonal references.
Capacity uses service months; price signals use departure-month sailing-cabin cohorts, so their time allocation differs.
`out/monthly_capacity.csv` has `brand`, `month`, `listed_capacity_days` and coverage flags for October 2025 through December 2027.
`out/current_monthly_readout.csv` gives July-December 2026 `quarter_guidance_pct`, `illustrative_seasonal_pct` and method ranges.
Seasonal and indicator methods distribute quarterly occupancy to months while preserving the quarterly benchmark.
`out/chronological_expanding_window.csv` and `out/chronological_metrics.csv` distinguish chronological evaluation from retrospective diagnostics.
Chronological indicator evaluation scored only one distinct quarter, 2026Q2, which cannot establish predictive value.
Current scenarios are benchmarked to guidance, not independent estimates; method ranges are not confidence intervals.
