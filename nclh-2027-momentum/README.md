# 2027 asking-price momentum
Compares Norwegian and peer asking-price changes for 2027 departures, with a Q4 2026 comparison check.
Source: the original brief specifies All Aboard `full-2026-09-13`, with analysis windows ending 2026-09-12.
Prices are USD per person per night; the measurement unit is a sailing and cabin combination.
`out/momentum_by_quarter.csv` and `out/momentum_by_month.csv` include `median_ratio`, `units`, `sailings` and `median_later_lead_days`.
The baseline divides median daily prices for 2026-08-23 through 2026-09-12 by those for 2026-06-24 through 2026-07-14, requiring five observed days per window.
`out/momentum_bootstrap.csv` reports Norwegian-minus-peer gaps and 90% intervals from resampling whole sailings with their cabins.
`out/momentum_robustness.csv`, `out/momentum_daily_index.csv` and `out/momentum_endpoint_coverage.csv` document sensitivities and coverage.
`out/regression_q4_2026.csv` checks the 90-120-day over 150-180-day forward ratio.
Caribbean scope uses embarkation ports; asking-price changes do not measure bookings, occupancy or realized yield.
