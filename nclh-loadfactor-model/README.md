# Quarterly occupancy framework
This folder compares reported occupancy with deposit and asking-price proxies and illustrative forward scenarios.
Sources are NCLH filings through 2026Q2, the September 14, 2026 All Aboard export, and archived deposit and capacity studies.
`out/nclh_reported.csv` records quarterly `capacity_days`, `passenger_cruise_days`, `occupancy_pct` and `ticket_per_pcd_usd`.
`out/identity_sensitivity.csv` varies revenue and realized-price assumptions; `out/benchmark_metrics.csv` reports errors in percentage points.
`out/price_quarterly.csv` contains sailing-cabin sample counts, `median_ratio`, cut shares and the occupancy comparison basis.
Occupancy equals passenger cruise days divided by lower-berth capacity days; the identity scenarios require independent revenue and price assumptions.
Deposit and price proxies are compared descriptively with actuals; guidance is kept separate from reported occupancy.
The archived local filing search did not provide peer occupancy, and the proper Q4 2026 deposit proxy lacked September-end deposits.
Scenarios are not independent forecasts; Norwegian asking-price samples differ in brand scope from consolidated NCLH occupancy.
