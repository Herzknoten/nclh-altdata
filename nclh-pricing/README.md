# Booking curves and blended fares
Cruise asking-price curves, curve-shape classifications and comparisons with reported NCLH ticket revenue.
Source: All Aboard September 2026 exports, with history from 2025-10-06 through 2026-09-12, plus NCLH reported KPIs.
The basic unit is a sailing and cabin; prices are USD per person per night.
`out/curve_metrics.csv` and `out/classification.csv` contain lead-time coverage, late_ratio, mid_ratio and curve_shape_classification.
Daily medians are compared across lead-time windows; classification requires the observation span and thresholds recorded in `params/defaults.json`.
`out-nclh-full-v2/blended_fare.csv` reports blended_pppn by ship, departure_month and lead_bucket, with coverage and PLACEHOLDER flags.
`out-nclh-full-v2/tieout.csv` compares completed-sailing prices with consolidated ticket revenue per passenger cruise day.
Other output folders preserve sample, fleet, peer and earlier variants; `out.pre-fix/` contains historical results before fixes.
Cabin and brand weights remain flagged where provisional; asking prices and curve shapes do not establish realized fares or revenue-management system use.
