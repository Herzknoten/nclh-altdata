# All Aboard parsed exports
Saved All Aboard Analytics listing-page exports from September 12-14, September 28, October 20 and November 4, 2026.
`out/<run>/sailings.csv` has one row per sailing with `sailing_id`, `line`, `ship`, `depart_date`, `nights` and cabin `*_pppn` asks in USD per person per night.
`verify_report.json` compares decoded page values with exports; `parse_errors.csv` retains diagnostics, and historical sample `price_history.csv` files retain sailing-cabin observations.
The parser resolves the sailing's own page panel and skips undecodable pages; PASS allows documented skips and does not imply complete industry coverage.
Early Norwegian snapshots: `2026-09-12`, `2026-09-12.pre-fix`, `2026-09-12.pre-fix2` and `claude-check`; the pre-fix directories are historical evidence.
Sample runs: `samples`, `samples.pre-fix` and `samples.pre-fix2`, each containing Norwegian, Oceania and Regent examples.
Full-universe runs target 17 lines: `full-2026-09-13` is an interim snapshot, `full-2026-09-14` the base export, followed by `full-2026-09-28` and `full-2026-11-04`; only verification reports remain in the first two directories.
NCLH runs: `nclh-2026-09-12`, `nclh-2026-10-20` and `nclh-2026-11-04` cover Norwegian, Oceania and Regent; the September 12 export also contains one Royal Caribbean sailing.
Early `peers-2026-09-12` and `peers2-2026-09-12` retain reports and manifests for seven lines: Norwegian, Oceania, Regent, Royal Caribbean, Carnival, Celebrity and Princess.
November-wave peer runs `peers-2026-10-20` and `peers-2026-11-04` cover Royal Caribbean and Carnival; all six September 28/October 20/November 4 wave directories are present here.
Large price-history CSVs are omitted in favor of the sibling Parquet folder; overlapping runs must not be concatenated without an explicit revision policy.
