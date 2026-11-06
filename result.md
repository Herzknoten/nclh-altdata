# Lane G2 completion report

Completed November 6, 2026. Only this clean tree was written; no git, network, rec-admit or test suite was used. The root `.codex-runs/` and `.lane-clean-audit.json` were left untouched.

## Changes and checks

- U1: no remaining forbidden research-tree paths found; no additional removals needed. Earlier cleanup removed 347 files and 52 directories, recorded in `.lane-clean-audit.json`.
- U2: added all 28 missing top-level READMEs; shortened five existing top-level notes and three nested sentiment notes, preserving evidence limits and removing stale links.
- U3: replaced the root README with vintages, every top-level folder, load examples, definitions, caveats, sources and the required terms line.
- U4: all 34 research-folder and 12 November-subfolder READMEs are 5-12 lines; all 50 READMEs have no em/en dashes; all Markdown file links resolve; all actual parser and Parquet run directories are listed.
- No retained research-tree file exceeds 95,000,000 bytes. `discipline/out/sailing_windows.csv` was skipped at about 112 MB (112,681,311 bytes), as recorded by lane G.
- Both Python code blocks in the root README executed unchanged: pandas loaded 71,279 filtered rows and seven columns; DuckDB returned five sample rows using one thread.
- All 210 copied November-wave files match the SHA-256 values in the earlier audit. The earlier audit file retains SHA-256 `6f19dee96f8be13baa92c6b3bf78d52883aa32e5551125163815e4759ced1359`.

All checks ran with `taskset -c 0 /home/rich/devdata/venv-nclh-ivy/bin/python -`, with check code supplied on standard input. Structural/link/run checks: exit 0. README loading examples: exit 0. Copied-file hash check: exit 0. Final inventory and structural check: exit 0. No test suite, compilation, conversion, upstream analysis rerun or live-source verification was requested or run.

## Handoff and limits

Parquet copies remain with the orchestrator: `full-2026-09-28`, `nclh-2026-10-20`, `peers-2026-10-20`, `nclh-2026-11-04`, `peers-2026-11-04`, `full-2026-11-04`. Their parser exports are present. Recheck inventory and replace the pending wording when those directories arrive.

The exact rerun input override, raw year-over-year cross-check provenance and regional projection calculation vintage remain undocumented in the retained evidence; the respective READMEs say so. Protected runtime metadata directories `.codex-runs/`, `.git/`, `.agents/` and `.codex/` are excluded from cleanup, README requirements and inventory. No user decision is needed for the completed documentation work.

The earlier brief requested reports outside this tree; the current write restriction takes precedence, so this report is stored here. Research parameters in `nclh-pricing/params/defaults.json` are retained as method evidence, not tool configuration.

Memory candidates: none.

## Earlier removal classes

| Class | Files removed by lane G |
| --- | ---: |
| Briefs and review drafts | 75 |
| Scripts, notebooks, compiled code | 103 |
| Nested .gitignore files | 22 |
| Long write-ups and supporting notes condensed into READMEs | 41 |
| Backup files (*.orig) | 2 |
| Lock files (*.lock) | 3 |
| Codex execution records (.codex-runs/) | 3 |
| Test directories (tests/) | 24 |
| Run logs and snapshots (logs/) | 45 |
| Run status and log files (*.exit, *.log) | 18 |
| Graphify tool records and caches (graphify-out/) | 11 |

## Final inventory

File sizes are exact logical bytes, not allocated disk blocks. Counts include READMEs and all regular files outside protected runtime directories. The root row includes this report, the preserved audit, README, `.gitignore` and the existing one-byte `charts` file.

| Folder | Files | Bytes |
| --- | ---: | ---: |
| allaboard-accuracy | 8 | 2451028 |
| allaboard-accuracy-followup | 13 | 1635967 |
| allaboard-accuracy-web | 1 | 735 |
| allaboard-parquet | 807 | 193736525 |
| allaboard-parser | 52 | 45558346 |
| asp | 3 | 109421 |
| cruisebound-sun | 2 | 4566 |
| dewey-evaluation | 16 | 1008681 |
| docs | 16 | 38714 |
| miami-schedule-check | 6 | 164212 |
| nclh-2027-momentum | 9 | 603053 |
| nclh-altdata-rerun-0914 | 9 | 602848 |
| nclh-availability-signals | 19 | 5183805 |
| nclh-baseload | 10 | 613725 |
| nclh-capacity | 25 | 4477787 |
| nclh-deposits | 5 | 68449 |
| nclh-discount-cause | 26 | 7019757 |
| nclh-kpis | 49 | 5362488 |
| nclh-loadfactor-model | 21 | 165926 |
| nclh-loadfactor-web | 1 | 923 |
| nclh-market-news-2026-09-16 | 1 | 983 |
| nclh-monthly-loadfactor | 22 | 323926 |
| nclh-parent-brand-patterns | 27 | 5189423 |
| nclh-price-pressure-index | 9 | 1035676 |
| nclh-pricing | 49 | 16254454 |
| nclh-pricing-events | 70 | 16062440 |
| nclh-promo-events | 13 | 5618633 |
| nclh-rm-cohort | 11 | 2177185 |
| nclh-yoy-lead | 16 | 9535627 |
| nclh-yoy-sanity | 2 | 1624 |
| nov2026-refresh | 205 | 85804321 |
| region_by_class_projected | 80 | 15669302 |
| safegraph-data | 5 | 18340453 |
| sentiment | 121 | 15159339 |
| (root) | 5 | 498854 |
| **Total** | **1734** | **460479196** |

Total: 460.479196 MB (439.147182 MiB).
