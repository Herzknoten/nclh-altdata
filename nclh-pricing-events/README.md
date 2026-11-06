# Pricing events
Daily price-cut counts, broad-cut dates, event-window comparisons and matched price levels.
Source: All Aboard `claude-check`, `nclh-2026-09-12` and `peers-2026-09-12`; observation history ends 2026-09-12.
The comparison unit is a sailing and cabin, using daily median USD prices per person per night.
`out/daily_cuts.csv` includes line, observation_date, n, n_cuts, cut_share, pair_coverage and broad_cut_day.
A cut is at least 5% against the nearest prior observation within three days; broad days require at least 30 pairs and a 20% cut share.
`out/event_summary.csv` and `out/matched_levels.csv` retain event and matched-cell comparisons with coverage.
`out-strat/standardized_broad_cut_events.csv` fixes the lead-time mix; companion tables test removal of the top ship.
`out-nclh-full/` and `out-peers/` contain broader export results; `out.pre-fix/` preserves historical results before fixes.
Missing pairs and unsupported comparisons stay blank; event timing and broad cuts do not establish their cause.
