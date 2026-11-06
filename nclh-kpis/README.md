# NCLH reported operating data
This folder contains quarterly operating and financial disclosures, guidance and fleet records extracted from NCLH filings.
Sources are archived results releases for 2021Q3 through 2026Q2 and annual reports for FY2021 through FY2025.
`quarterly_kpis.csv` has `quarter`, `capacity_days`, `passenger_cruise_days`, `occupancy_pct`, revenue and current advance ticket sales.
`guidance.csv` has `release_date`, `period`, `metric`, `low`, `high`, `point`, `unit` and source snippets.
`fleet.csv` and `fleet_by_year.csv` describe ships and annual fleets; `provenance.csv` and `evidence/` retain extraction evidence.
Quarterly values use each quarter's own release; later changed comparatives are recorded separately in `restatements.csv`.
Financial statement amounts are converted to USD millions where named `_musd`; missing or qualified figures remain blank.
Current advance ticket sales exclude long-term deposits, and occupancy can exceed 100% because capacity uses lower berths.
`release_manifest.csv` and `validation.csv` preserve source hashes and arithmetic checks for the 20 reported quarters.
