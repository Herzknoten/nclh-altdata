# All Aboard price-history Parquet
Typed copies of All Aboard Analytics listing-page history, from the September 14 base export and September 28, October 20 and November 4 refreshes in 2026.
Each row is a sailing-cabin observation: `sailing_id`, `line`, `ship`, `depart_date`, `nights`, `scraped_at`, `cabin`, `price`, `days_before_departure`; price is USD per person per night.
`out/<run>/price_history.parquet` and `partitioned/` are alternative copies, not additive data; `verify*.json` and `convert*.json` retain conversion evidence.
Conversion preserves values and nulls; partitions group by line and departure month, while `scraped_at` is the site's observation time, not the download time.
Present: `full-2026-09-14` covers 17 lines; `nclh-2026-09-28` is partitioned-only Norwegian, Oceania and Regent history with Royal Caribbean history also present.
Present: `peers-2026-09-12` and `peers2-2026-09-12` are overlapping early seven-line exports: Norwegian, Oceania, Regent, Royal Caribbean, Carnival, Celebrity and Princess.
November wave (partitioned-only, all verified PASS): `full-2026-09-28` and `full-2026-11-04` cover the full 17-line universe; `full-2026-11-04` holds 11,379,847 rows.
`nclh-2026-10-20` and `nclh-2026-11-04` cover Norwegian, Oceania and Regent.
`peers-2026-10-20` and `peers-2026-11-04` cover Royal Caribbean and Carnival.
Use one run and one representation at a time; changing coverage and revised histories prevent treating refreshes as disjoint observations.
Asking prices are not bookings or realized fares; verification checks exported values, not the provider's economic accuracy.
