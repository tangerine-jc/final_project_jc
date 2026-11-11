Are Morning Flights Really More Punctual?
================
November 11, 2026

**Team:** 曹俊泽 (jc6961), 赵承舜 (cz3006), Cecilia Zhao (yz5434), Cindy
Wang (yw4817), and 刘峙岳 (zl3802).

## Motivation

Is an earlier flight worth the early alarm? We will examine whether
morning flights arrive late less often, how much of any advantage
remains within comparable routes, and whether it varies across airports
and seasons. Cancellations and diversions will help assess whether the
answer changes when unsuccessful trips are included.

## Data and analysis

We plan to download 44 monthly files from [BTS Reporting Carrier On-Time
Performance](https://www.transtats.bts.gov/Fields.asp?gnoyr_VQ=FGJ),
covering reported US domestic flights from January 2023 through August
2026. An August 2026 pilot contains 608,389 records; the full count
remains to be established.

Morning means scheduled departure at 06:00–09:59 in the origin airport’s
local time, compared with 10:00–21:59; overnight flights will be shown
separately. Our primary outcome is arrival delay of at least 15 minutes
among non-cancelled, non-diverted flights with valid arrival delay.
Cancellation and diversion rates will use all eligible reported flights,
with unknown outcomes documented separately. We will plot hourly delay
rates, compare percentage-point differences within directional
route–carrier–year-month groups containing at least 30 completed
observations per departure group, and report the retained sample’s
coverage. Airport–season comparisons will use the 20 busiest origin
airports in 2023 plus JFK, LGA, and EWR. We will vary the morning cutoff
and restrict direct comparisons across years to January–August. Results
will describe associations, including absent or reversed advantages.
