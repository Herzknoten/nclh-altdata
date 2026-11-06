# Reddit activity and topic refresh

Reddit posts and comments collected through Arctic Shift, covering January 2025-October 2026.
November 1-4, 2026 appears separately as a partial period and is excluded from monthly endpoint comparisons.
Units are aggregated items by community, month and topic; key columns include `items`, `mentions`, `per1000` and `partial`.
Deduplicate posts and comments by item identity, then apply fixed keyword rules without running a new sentiment model.
Activity uses three-month smoothing; the baseline weights January-May 2025 rather than literal Q1.
See `activity_monthly.csv`, `n4_chart_data.csv` and `premium_yoy.csv`; mentions measure discussion, not bookings.
