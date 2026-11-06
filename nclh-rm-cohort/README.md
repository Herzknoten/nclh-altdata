# Listing cohorts
Comparisons of prices for earlier-listed and newly listed sailings, without assuming a revenue-management system assignment.
Source: All Aboard `full-2026-09-14`; fixed price windows end 2026-09-12 and first-seen history starts 2025-10-06.
The unit is a sailing and cabin, grouped by line, departure month, region and listing cohort.
`out/fixed_summary.csv` includes cutoff, cohort, units, sailings, median_ratio, share_down_gt5 and status.
The primary new-listing cutoff is 2026-06-01, with May and July sensitivities; first observations before 2025-11-01 are treated as left-censored.
Fixed windows compare 2026-06-24 through 2026-07-14 with 2026-08-23 through 2026-09-12.
`out/since_listing_checkpoints.csv` indexes prices against each unit's first 14 observed days; companion coverage tables show support.
`out/peer_gaps.csv` reports Norwegian-minus-peer gaps and sailing-cluster bootstrap intervals.
First seen in the panel is a proxy for listing, not proof of booking-window opening or system adoption; unsupported estimates stay blank.
