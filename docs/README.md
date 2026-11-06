# Panel coverage figures
Aggregate tables and SVG charts describing the September 2026 All Aboard price panel.
Source: `allaboard-parquet/out/full-2026-09-14/partitioned/`; older runs were not concatenated.
Observation dates span 2025-10-06 through 2026-09-13, with departures from 2025-10-12 through 2028-12-30.
`chart_data/coverage.csv` records 10,760,269 price rows, 29,201 sailings and 17 lines, as reported in the original figure audit.
`chart_data/line_coverage.csv` contains `line`, `rows`, `sailings` and `ships`; other tables group observations by month, cabin or lead time.
`charts/` contains five SVGs, including `sailings_by_line.svg` and `observations_by_month.svg`.
Aggregations count sailings by line, ship and sailing ID; timestamps are interpreted in UTC.
Coverage includes post-departure observations, so these figures describe the source panel rather than an analysis-ready sample.
