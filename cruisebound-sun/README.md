# Norwegian Sun asking prices

Cruisebound sailing-page snapshot collected September 28, 2026, covering Norwegian Sun sailings absent from the All Aboard panel.
`out/sun-2026-09-28/sailings.csv` contains 14 sailings departing October 24, 2026 through March 24, 2027.
The unit is one sailing with cabin-category fares in USD per person for the whole voyage.
Key columns are `sailing_id`, `depart_date`, `nights`, `embark_port`, `inside_inclusive` and `inside_exclusive`.
Inclusive prices contain taxes and fees; exclusive prices exclude them; divide by `nights` for a nightly comparison.
Sailing IDs were probed and structured offer prices checked against the lowest cabin fare.
The original comparison found inclusive nightly prices close to All Aboard at the median, with substantial sailing-level variation.
This folder contains one snapshot, not a daily history; April 2027 sailings and Norwegian Star were outside the probed range.
