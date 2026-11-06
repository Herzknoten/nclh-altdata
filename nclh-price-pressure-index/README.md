# Price pressure index
Monthly comparisons of observed cruise asking prices with an estimated reference price.
Source: All Aboard `full-2026-09-14`, with observations from 2025-10-06 through 2026-09-12.
The underlying unit is a sailing and cabin; prices are USD per person per night and residuals are in log-price units.
`out/monthly_index.csv` groups by scope, line, departure_month, variant, method and window, with median_residual, share_positive, units and sailings.
The reference model controls for product, departure month and lead time using observations at least 91 days before departure.
Strict close-in coefficients are unidentified; numeric alternatives assume a flat 91-120-day reference or extrapolate from earlier lead bands.
`out/model_diagnostics.csv` records training support; `out/validation.csv` records occupancy comparisons and publication timing.
`out/promotion_calendar.csv` and `out/deposit_context.csv` provide promotion and deposit context.
These assumption-dependent residuals are not calibrated occupancy estimates; blank values mean unavailable.
