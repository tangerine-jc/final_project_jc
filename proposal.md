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

## Products and workflow

We will produce four to five core figures, a standalone report, an R
Markdown website containing that report, and a narrated screencast of at
most two minutes. The homepage will link to our shared GitHub repository
and embed the published video. Using classroom readr, dplyr, purrr,
ggplot2, and Plotly methods, we will process selected columns one month
at a time and combine summary tables. Challenges include memory use,
inconsistent fields, missing outcomes, and correct denominators. We will
retain download and cleaning logs and keep raw files out of Git.
Regression is optional. If processing is not feasible by November 20, we
will reduce coverage to January 2025–August 2026 and document the
change.

## Team and timeline

曹俊泽 will lead data preparation; 赵承舜, overall comparisons; 刘峙岳,
within-route analysis and report integration; Cecilia Zhao,
airport–season analysis and video editing; and Cindy Wang, disruption
measures and website integration. Everyone will contribute code,
writing, and review in the dedicated repository. We will finalize the
proposal November 12 and submit by November 13 at 1 pm; all five will
attend the November 16–20 review. Data checks finish November 22,
analysis drafts November 27, and a complete report and website December
4. We will freeze outputs December 11, submit shared deliverables and
individual peer assessments by December 12 at 11:59 pm, and join the
December 17 discussion. All times are Eastern.
