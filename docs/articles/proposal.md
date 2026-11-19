# 

Addressed to: BST260 Teaching Team, Fall 2026

## Project overview

For my final project, I plan to write two vignettes using two different
datasets. The first will describe firearm law records from the RAND
database. The second will describe firearm mortality rates from the CDC.
I will analyze each dataset separately and focus on patterns in the
data.

\#Topic 1 :

**Research question:** Do the proportions of restrictive and permissive
firearm law records differ across law classes in the RAND dataset?

- Unit of analysis: One firearm law record.
- Population: Firearm law records included in the RAND database.
- Exposure: Law.Class; Effective.Date.Year will be used to describe
  changes over time.
- Outcome: Effect, a categorical variable that identifies a record as
  restrictive or permissive.
- Missing data: I will exclude records missing Law.Class or Effect from
  the proportion comparisons. I will exclude records missing
  Effective.Date.Year from the time trend analysis.
- Confounders: I will not adjust for confounders because this is a
  descriptive analysis and will not estimate the causal effect of laws.

## Topic 2: Firearm mortality by state and year

**Research question:** How did firearm death rates vary across states
and over time from 2014 through 2024?

- Unit of analysis: One location in one year.
- Population: Locations included in the dataset from 2014 through 2024.
- Exposure: Year and location, used to describe differences over time
  and across locations.
- Outcome: Death.Rate, a continuous variable.
- Missing data: I will check for missing values and exclude records
  missing the year, location, or death rate from the relevant analyses.
- Confounders: I will not adjust for confounders because this analysis
  will describe patterns and will not try to explain their causes.
