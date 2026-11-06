# Miami schedule comparison
Compares PortMiami calls with All Aboard sailings and estimates passenger movements under stated occupancy scenarios.
Source: CruiseTimetables 2026 and 2027 Miami schedules fetched 2026-09-28, plus the project's ship-berth table.
`calls_ctt_2026.csv` and `calls_ctt_2027.csv` contain `date`, `line`, `ship`, arrival and departure times, and scheduled passengers.
`out_call_match.csv` matches ship-date calls to sailing starts and ends; `out_calls_movements.csv` records `berths`, `legs` and `dataset_match`.
`out_movements_summary.csv` groups calls and scenario movements by `period` and `scope`.
A turnaround contributes two movements per berth times occupancy; an arrival-only or departure-only call contributes one.
The original report states that all 229 dataset Miami departures in calendar 2027 matched a scheduled call.
Schedules can change, and whether Oceania and Regent count toward the cited minimum annual guarantee remains unresolved.
