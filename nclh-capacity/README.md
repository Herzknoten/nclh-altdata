# NCLH listed capacity
This folder estimates listed fleet capacity by brand, region, month and quarter.
Sources are the September 12, 2026 All Aboard sailing export, ship cabin tables and NCLH filings.
Regional summaries cover 2026Q3 through 2027Q4; the calendar retains underlying sailing dates.
`out/shipday_calendar.csv` has one selected ship-day with `brand`, `ship`, `date`, `listing_id`, `region` and `berths`.
`out/shipday_capacity_by_region_quarter.csv` reports `capacity_days` and `share_of_brand_capacity`.
`out/shipday_price_cohort_share.csv` separates `price_panel_ports` from `broad_itinerary` and gives roster-gap bounds.
Capacity days equal lower berths times sailing days; hotel packages are excluded and overlapping ship-days are resolved once.
Month and quarter boundaries split voyages; `out/shipday_coverage.csv` and `out/shipday_sensitivity.csv` show coverage and rule sensitivity.
These are listed-calendar estimates, with incomplete fleet coverage and an embarkation or itinerary proxy for region.
