# NCLH alternative-data archive

This repository contains the alternative data behind Cruise Capital's NCLH long pitch for the Ivy League Investment Competition in November 2026. It preserves price panels, study tables, charts and short method notes so readers can inspect the evidence and its limits. The files are research inputs and archived analyses, not a standalone investment recommendation.

Data vintages: September 14, 2026 base price export; September 28, October 20 and November 4 refreshes. Run dates identify exports, not the full range of historical observations. Card, device, filing and Reddit data have separate cutoffs documented in their folder READMEs.

## Folder index

| Folder | What | Vintage | Key files |
| --- | --- | --- | --- |
| [allaboard-accuracy](allaboard-accuracy/README.md) | Price accuracy and source-mix checks | September 14 base | `out/u5_source_mix.csv`, `out/u6_external_level.csv` |
| [allaboard-accuracy-followup](allaboard-accuracy-followup/README.md) | Price labels, repricing dates and paths | September 14 base | `out/u1_label_counts.csv`, `out/u3_path_summary.csv` |
| [allaboard-accuracy-web](allaboard-accuracy-web/README.md) | Archived provider-method research summary | September 14, 2026 | `README.md` |
| [allaboard-parquet](allaboard-parquet/README.md) | Typed price-history panels and verification | September 14 base through November 4 refresh | `out/<run>/price_history.parquet`, `partitioned/`, `verify*.json` |
| [allaboard-parser](allaboard-parser/README.md) | Sailing metadata and parser audit exports | September 12 through November 4, 2026 | `out/<run>/sailings.csv`, `verify_report.json`, `parse_errors.csv` |
| [asp](asp/README.md) | Ship-region-cabin asking-price inputs | September 28 prices; October 1 corrections | `asp_by_ship_region_cabin.csv` |
| [cruisebound-sun](cruisebound-sun/README.md) | Norwegian Sun snapshot | September 28, 2026 | `out/sun-2026-09-28/sailings.csv` |
| [dewey-evaluation](dewey-evaluation/README.md) | Card-panel and location-data evaluation | Tracker through August 7; cohorts through 2026Q2 | `data/quarterly_matched.csv`, `data/cohort_quarterly.csv` |
| [docs](docs/README.md) | Base-panel coverage tables and charts | September 14 base | `chart_data/coverage.csv`, `charts/` |
| [miami-schedule-check](miami-schedule-check/README.md) | Schedule matches and passenger-movement scenarios | September 28, 2026; 2026-2027 schedules | `out_call_match.csv`, `out_movements_summary.csv` |
| [nclh-2027-momentum](nclh-2027-momentum/README.md) | Asking-price changes for 2027 departures | September 2026; windows through September 12 | `out/momentum_by_quarter.csv` |
| [nclh-altdata-rerun-0914](nclh-altdata-rerun-0914/README.md) | Retained momentum rerun | September 2026; exact input override unrecorded | `momentum/out/momentum_by_quarter.csv` |
| [nclh-availability-signals](nclh-availability-signals/README.md) | Quote-presence and availability hypotheses | September 14 base | `out/category_presence.csv`, `out/verdict.csv` |
| [nclh-baseload](nclh-baseload/README.md) | Early versus late asking-price patterns | September 14 base, cutoff September 12 | `out/curves.csv`, `out/close_in.csv` |
| [nclh-capacity](nclh-capacity/README.md) | Listed ship-day capacity estimates | September 2026 inputs; 2026Q3-2027Q4 summaries | `out/shipday_calendar.csv`, `out/shipday_coverage.csv` |
| [nclh-deposits](nclh-deposits/README.md) | Current-deposit metrics and accounting bridge | 2021Q3-2026Q2 | `out/nclh_deposit_metrics.csv`, `out/nclh_implied_new_deposits.csv` |
| [nclh-discount-cause](nclh-discount-cause/README.md) | Descriptive markdown evidence scorecard | September 14 base, cutoff September 12 | `out/scorecard.csv`, `out/matched_metrics.csv` |
| [nclh-kpis](nclh-kpis/README.md) | Reported KPIs, guidance and fleet | 2021Q3-2026Q2; FY2021-FY2025 reports | `quarterly_kpis.csv`, `guidance.csv`, `evidence/` |
| [nclh-loadfactor-model](nclh-loadfactor-model/README.md) | Quarterly occupancy framework | Filings through 2026Q2; September price inputs | `out/nclh_reported.csv`, `out/identity_sensitivity.csv` |
| [nclh-loadfactor-web](nclh-loadfactor-web/README.md) | Archived occupancy disclosures | September 14, 2026 review | `README.md` |
| [nclh-market-news-2026-09-16](nclh-market-news-2026-09-16/README.md) | Historical news and positioning summary | September 16, 2026 | `README.md` |
| [nclh-monthly-loadfactor](nclh-monthly-loadfactor/README.md) | Monthly occupancy scenarios | September 2026; July-December 2026 readout | `out/current_monthly_readout.csv`, `out/chronological_metrics.csv` |
| [nclh-parent-brand-patterns](nclh-parent-brand-patterns/README.md) | Brand and parent pricing comparisons | September 14 base, cutoff September 12 | `out/summary.csv`, `out/correlation_summary.csv` |
| [nclh-price-pressure-index](nclh-price-pressure-index/README.md) | Assumption-dependent log-price residuals | September 14 base, cutoff September 12 | `out/monthly_index.csv`, `out/model_diagnostics.csv` |
| [nclh-pricing](nclh-pricing/README.md) | Booking curves and fare blends | September 2026 exports | `out/curve_metrics.csv`, `out-nclh-full-v2/blended_fare.csv` |
| [nclh-pricing-events](nclh-pricing-events/README.md) | Price cuts and event comparisons | September 2026 exports | `out/daily_cuts.csv`, `out/event_summary.csv` |
| [nclh-promo-events](nclh-promo-events/README.md) | Sale timing and price recovery | June 24 through September 12, 2026 observations | `out/sale_summary.csv`, `out/promotion_calendar.csv` |
| [nclh-rm-cohort](nclh-rm-cohort/README.md) | Earlier and newly listed sailing cohorts | September 14 base, cutoff September 12 | `out/fixed_summary.csv`, `out/peer_gaps.csv` |
| [nclh-yoy-lead](nclh-yoy-lead/README.md) | Year-over-year prices at comparable leads | September 14 base, cutoff September 12 | `out/headline.csv`, `out/overlap.csv` |
| [nclh-yoy-sanity](nclh-yoy-sanity/README.md) | Unreviewed raw year-over-year check | Exact source vintage unrecorded | `raw_aug_sep_same_band_output.txt` |
| [nov2026-refresh](nov2026-refresh/README.md) | Twelve studies and chart packages for the refresh | October 20 dry run; November 4 price refresh | Study READMEs, CSV/JSON tables and PNG charts |
| [region_by_class_projected](region_by_class_projected/README.md) | Archived regional and cabin projections | July 2026-December 2027 cohorts; calculation vintage unrecorded | `revenue_by_cohort_by_region.csv`, `total_revenue_by_cohort.csv` |
| [safegraph-data](safegraph-data/README.md) | Device visits and place metadata | Fleet through June 6; terminals through July 25, 2026 | `norwegian_fleet_pings.parquet`, `port_terminal_pings.parquet` |
| [sentiment](sentiment/README.md) | Reddit tone and topic aggregates | January 2025-September 2026; October 2 study | `results/v4/model/`, `linkage/` |


All ten price runs are present in both `allaboard-parser/out/` (sailing tables and parser audits) and `allaboard-parquet/out/` (verified Parquet price histories). The largest, `full-2026-11-04`, holds 11,379,847 price rows across 17 lines.

## How to load the price panel

Run from the repository root in an environment with pandas, PyArrow and DuckDB. The examples use the present September 14 base export; choose one run, since snapshots overlap and may revise history.

```python
from datetime import date
from pathlib import Path
import pandas as pd

run = "full-2026-09-14"
path = Path("allaboard-parquet/out") / run / "price_history.parquet"
prices = pd.read_parquet(
    path,
    columns=["sailing_id", "line", "ship", "depart_date", "scraped_at", "cabin", "price"],
    filters=[("line", "=", "norwegian"),
             ("depart_date", ">=", date(2027, 1, 1)),
             ("depart_date", "<", date(2027, 2, 1))],
    use_threads=False,
)
```

Or query the same file with DuckDB:

```python
import duckdb

with duckdb.connect(config={"threads": 1}) as db:
    db.execute("SET TimeZone = 'UTC'")
    sample = db.execute("""
        SELECT sailing_id, line, depart_date, cabin, price, days_before_departure
        FROM read_parquet('allaboard-parquet/out/full-2026-09-14/price_history.parquet')
        WHERE line = 'norwegian'
        LIMIT 5
    """).fetchdf()
```

For a partitioned-only run, read the `partitioned/` files with Hive inference disabled because `line` is already stored in the files. Single-file and partitioned data are alternative representations; do not concatenate them. `verify*.json` records historical conversion checks and does not revalidate the source today.

## Definitions

- A price observation is a non-null advertised cabin ask in USD per person per night. `scraped_at` is the provider's historical observation time in UTC, not our page-download time.
- Price index = ask / first observed ask x 100. Some archived studies use a fixed lead-time, peak-price or calendar anchor instead; their README and columns govern those variants. First observed does not necessarily mean first offered for sale.
- Lead = days before departure, calculated from departure and observation dates. The base panel retains some post-departure rows; apply the study's cutoff explicitly.
- Departure-month cohorts group sailings by scheduled departure month, not by quote-observation month or passenger payment month.
- Cabin categories are `inside`, `oceanview`, `balcony` and `suite`; `Window` in model inputs means oceanview. A ship may not offer or price every category.
- Identify a sailing with `line`, `ship` and `sailing_id`; ship slugs alone are not globally unique. Missing values mean unavailable unless a study explicitly defines otherwise.

## Caveats

Asking prices are not bookings or realized fares. Missing quotes do not establish sellouts, inventory or occupancy. Listing coverage, historical revisions, brand mix and observation windows vary across runs; older exports named peers include seven lines, unlike the two-line October and November peer refreshes. Models of occupancy, capacity or revenue retain their assumptions and are not additional observed quantities.

Card customers are not passengers, and payments can include deposits, installments, refunds and different merchant channels. Card panels have partial and changing coverage. Reddit labels are model-generated, with no human validation in the retained study; sampling intervals do not cover classification uncertainty. Phone pings are devices, not passengers, and overlapping extracts cannot be added as unique people. Schedules and projected movements are not realized port traffic. Unsourced vintages are labeled unverified in their folder notes.

The November refresh omits `discipline/out/sailing_windows.csv` because it is about 112 MB (112,681,311 bytes), above the 95 MB file limit; retained close-in summaries remain in `nov2026-refresh/closein-discipline/`.

## Sources and terms

Sources represented here are All Aboard Analytics listing pages; Dewey datasets from ConsumerEdge, Veraset and SafeGraph; Reddit via Arctic Shift; CruiseTimetables; Miami-Dade County; NCLH filings; and Cruisebound for the Norwegian Sun snapshot. Folder notes and retained manifests identify the source and vintage of each output; listing a provider does not imply its data has the same coverage or unit as another provider's data.

Third-party data remain subject to their providers' terms.
