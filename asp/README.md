# Ship, region and cabin asking-price inputs

Advertised-price inputs for 34 NCLH ships and 11 model regions, using All Aboard histories through September 28, 2026.
Departures start October 1, 2026; the cabin and region corrections were documented October 1.
`asp_by_ship_region_cabin.csv` has one row per ship, region and cabin; `key` joins those names.
Prices are USD per person per night including taxes and port fees; Window means oceanview.
Key columns are `max_asp_pppn`, `median_first_pppn`, `median_latest_pppn`, `n_sailings`, `n_units` and `as_of`.
`max_asp_pppn` takes each sailing-cabin's 90th-percentile observed price, then the median across eligible sailings.
Cabins use the same complete-cabin sailings; nonmonotonic cabin medians are pooled into an ordered price ladder.
Regions use interior itinerary ports; `deployment_check_2027.csv` compares ship-region sailing counts with CruiseTimetables.
Zero cells reflect absent eligible sailings or unpriced cabin categories; fewer than three sailings is thin coverage.
These asking-price inputs use a peak-price basis and do not measure realized fares or ticket yield.
