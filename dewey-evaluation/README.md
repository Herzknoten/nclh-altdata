# Dewey alternative-data evaluation

Descriptive evaluation of ConsumerEdge card panels, SafeGraph location coverage and reported cruise-company revenue.
Tracker observations span January 2018 through August 7, 2026; retained cohort quarters span 2021Q3-2026Q2.
`data/quarterly_matched.csv` contains brand-quarter `matched_spend_usd`, `matched_spend_yoy` and `matched_day_count`.
`data/cohort_quarterly.csv` contains brand-quarter `unique_customers`, `customers_yoy` and `spend_per_customer`.
Tracker growth matches calendar days across Norwegian, Royal Caribbean and Carnival in both comparison years.
Cohort customer and payment-intensity measures use their own panel; its dollars are not interchangeable with Tracker dollars.
`data/capture_quarterly.csv` and `data/correlations.csv` compare card observations with reported revenue; `input_manifest.csv` records provenance.
All retained Tracker card quarters are partial, and actual daily cohort coverage is unverified; correlations remain exploratory.
SafeGraph coverage tables describe devices and locations; card customers are not passengers, and payment size is not a fare.
