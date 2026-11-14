# South Korea CO₂ Emissions Analysis (1990–2024)

An exploratory data analysis of South Korea's annual carbon dioxide (CO₂) emissions from 1990 to 2024 using R in Posit Cloud.

## Overview & Data Source
- **Dataset:** Annual CO₂ emissions per country from [Our World in Data (OWID)](https://ourworldindata.org/co2-emissions)
- **Scope:** South Korea (1990–2024, 35 years)
- **Units:** Million Tonnes

## Key Findings
- **1990 Emissions (Min):** 250.51 million tonnes
- **2024 Emissions:** 584.77 million tonnes
- **Peak Year (Max):** 2018 at 670.17 million tonnes
- **Mean (1990–2024):** 509.69 million tonnes
- **Median (1990–2024):** 521.71 million tonnes
- **Standard Deviation:** 120.06 million tonnes

## Repository Files
- `South_Korea_CO2_Analysis.R` — Complete R script that imports the OWID dataset, filters for South Korea, computes summary statistics and year-over-year changes, exports CSV/text outputs, and generates visualizations.
- `KOR_co2.csv` — Cleaned annual CO₂ emissions dataset for South Korea (1990–2024) in million tonnes.
- `KOR_summary.csv` — Summary statistics table (mean, median, standard deviation, minimum, peak, and latest values).
- `KOR_yearly_changes.csv` — Dataset containing year-over-year absolute changes and annual percentage changes.
- `KOR_session_info.txt` — R environment and session metadata for reproducibility.
- `Annual_CO2_Emissions_KOR.png` — Line chart visualizing South Korea's annual CO₂ emissions trend from 1990 to 2024.
- `Annual_Percentage_Change_KOR.png` — Line chart showing South Korea's year-over-year percentage change in CO₂ emissions.

## How to Run
1. Open `South_Korea_CO2_Analysis.R` in RStudio or Posit Cloud.
2. Run the entire script (`Source`)—no external R packages are required.
