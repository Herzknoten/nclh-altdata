# SafeGraph device-visit data

Weekly SafeGraph-style extracts assembled by Josh for Norwegian brand locations and broader cruise terminals.
`norwegian_fleet_pings.parquet` contains 1,704 observations with source weeks June 1, 2024 through June 6, 2026.
`port_terminal_pings.parquet` contains 296,576 observations with source weeks January 4, 2025 through July 25, 2026.
Each row is one recorded device visit; key fields are `week_start`, `caid`, `utc_timestamp`, `placekey` and `minimum_dwell`.
The matching `*_placekeys.csv` files supply location names, categories and addresses, joined on `placekey`.
Weekly files were concatenated and sorted by `week_start`, `caid` and `utc_timestamp`; source filenames supply `week_start`.
The fleet file covers four placekeys and the terminal file covers 22; brand-matched locations include non-terminal sites.
Repeated pings and overlapping files must not be summed as passengers; coverage changes can resemble changes in traffic.
No file measures bookings, ticket sales, revenue or completed cruises.
