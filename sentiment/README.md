# Reddit customer-sentiment study

Arctic Shift aggregates for r/NCL, r/royalcaribbean and r/CarnivalCruiseFans, covering January 2025 through September 2026.
The October 2, 2026 study used 873,962 archive records, 834,395 eligible records and 16,800 sampled items.
Units are community-period tone summaries, hypothesis contrasts and topic rates; private source texts and author-level data are absent.
`results/v4/model/hypotheses.csv` reports `claim`, `estimate_points`, `n_items`, `n_authors` and `protocol_verdict`.
`results/v4/model/tone_cells.csv` reports `community`, `period`, `negative_share` and `balance_points`.
Two model raters label sampled items; period estimates give each observed eligible author one vote after sampling adjustment.
Comparisons use communities' own 2025 baselines; first-hand trip reports, topic rates and capacity diagnostics remain distinct.
Human validation is absent: model agreement measures repeatability, and conditional sampling intervals omit classification uncertainty.
See `results/v4/model/final_verdicts.csv` and `linkage/linkage_gates.csv`; hypothesis and model-linkage gates remain not estimable.
