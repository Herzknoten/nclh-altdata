# Promotion events
Comparisons of Norwegian price-cut waves with dated sales and subsequent price recovery.
Source: All Aboard `full-2026-09-14`, observations from 2026-06-24 through 2026-09-12, and a sourced promotion calendar.
The unit is a sailing and cabin; results compare Norwegian with Royal Caribbean, Carnival, Celebrity and Princess by region and lead band.
`out/promotion_calendar.csv` records sale dates and confidence; `out/sale_daily.csv` and `out/sale_summary.csv` contain price changes and recovery measures.
A cut exceeds 5%; recovery means returning within 2% of the baseline within 3, 7 or 14 days after the sale.
Classification uses mature-cohort recovery bounds and promotion exposure; complete-case measures remain a sensitivity.
`out/clean_horizons.csv` identifies promotion-free target dates, with unit counts, median ratios and below-95% shares.
`out/wave_persistence.csv` and `out/background_drift.csv` track persistence and the timing of cumulative changes.
Uncertain sale dates, overlapping promotions and missing follow-up limit interpretation; these are asking-price observations.
