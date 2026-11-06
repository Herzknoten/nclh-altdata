# Early price cuts by cruise line

All Aboard histories in the November 4, 2026 exports for Norwegian, Royal Caribbean and Carnival.
The unit is a sailing and cabin category, grouped by departure month and 300-day or 420-day lead.
Key columns include `line`, `lead_days`, `month`, `kit_cabins`, `kit_share` and `kit_released`.
The metric is the share ever at least 10% below its first observed daily ask by the specified lead.
Require 60 days of earlier history and observed coverage through the lead; monthly groups receive equal weight.
See `monthly_by_line.csv`, `contrasts.csv` and `verdicts.csv`; missing future threshold coverage is not a zero cut rate.
