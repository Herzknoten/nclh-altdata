# Base-loading pattern checks
Measures whether Norwegian asking-price changes are concentrated far ahead of departure or close to sailing.
Source: All Aboard `full-2026-09-14`, filtered through 2026-09-12; `out/diagnostics.json` records the input and cutoff.
Prices are USD per person per night; underlying units are sailing and cabin combinations.
`out/curves.csv` groups `median_index`, `units` and `sailings` by line, departure month, observation period and lead band.
Curves normalize each unit to its own median price 150-240 days before departure; missing anchors remain blank.
`out/far_out.csv` compares prices at leads of at least 241 days before and after 2026-07-01.
`out/close_in.csv` reports 7-30-day over 60-120-day late ratios and 90-120-day over 150-180-day forward ratios.
`out/events.csv` measures cuts on 2026-08-10, 2026-08-12 and 2026-08-29; gap, trend and coverage files support comparisons.
Caribbean embarkation scope and all-region sensitivities are descriptive; prices cannot establish management intent or realized yield.
