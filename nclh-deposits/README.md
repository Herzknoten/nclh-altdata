# Customer deposits
This folder compares current customer deposits with subsequent revenue and capacity.
Sources are NCLH quarterly filings for 2021Q3 through 2026Q2 and the archived SEC cruise-company quarterly series.
`out/nclh_deposit_metrics.csv` has quarterly `advance_ticket_sales_musd`, `deposit_yoy_pct` and deposits per future capacity day.
`out/peer_deposit_metrics.csv` compares current deposits with next-quarter total revenue, retaining company fiscal calendars.
`out/nclh_implied_new_deposits.csv` contains the deposit bridge and its `release_basis_note`; monetary amounts are USD millions.
Year-over-year comparisons use matching quarters; capacity denominators label actual and guided inputs.
The bridge adds recognized passenger-ticket revenue to the change in current deposits and supplies a total-revenue upper bound.
Despite the legacy filename, this is a passenger-ticket-adjusted deposit change, not observed new bookings.
Long-term deposits, currency effects and the exact release of prepaid revenue are not resolved; `out/manifest.json` records output hashes.
