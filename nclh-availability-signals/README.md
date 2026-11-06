# Availability signal checks
Tests whether saved All Aboard fields or quote patterns can support a cabin-availability or occupancy measure.
Source: `full-2026-09-14` and saved pages labelled 2026-09-12; the completed analysis includes September 13 history observations.
Underlying units are sailings, cabin categories and observation days, with summaries by line, departure quarter and lead band.
`out/category_presence.csv` separates `quoted_days`, `observed_sailing_days` and `whole_sailing_missing_days`.
`out/sample_pages.csv`, `out/sample_cabins.csv` and `out/field_inventory.csv` preserve sampled status fields and freshness evidence.
`out/candidate_signals.csv` reports category dropouts, sustained price steps and terminal quote gaps; `out/signal_events.csv` identifies events.
Methods separate missing categories from missing whole sailings and compare candidate directions with reported consolidated NCLH occupancy.
`out/verdict.csv` records each candidate's coverage, interpretation and usability.
Snapshot status and quote presence cannot establish historical remaining inventory; no occupancy percentage is estimated.
