# Connecticut Home Value Trends: 2018–2025

### Link: ***[Final (R Markdown) Report](https://ryanmannix1.github.io/ct-home-value-trends-2018-2025/)***

## Overview

This project analyzes Connecticut county-level home values for single-family homes and condos, comparing pre-, during-, and post-COVID periods (2018–2025). The analysis is based on Zillow’s ZHVI dataset.

**Data Source:** [Zillow Research Data](https://www.zillow.com/research/data)  
**Note:** Data was downloaded on June 27, 2025; 2025 values reflect figures up to that date.

## Features

- Loads Zillow ZHVI datasets for single-family and condo homes
- Filters and analyzes Connecticut county data
- Calculates annual average home values for each county and property type (2018–2025)
- Visualizes trends over time for each county
- Generates summary tables and trend plots

## How to Use

1. Clone the repository.
2. Open the `.Rmd` file (`CT_Home_Values_Trends_2018_to_2025.Rmd`) in RStudio.
3. Ensure the required CSV files (`County_zhvi_uc_sfr_tier_0.33_0.67_sm_sa_month.csv` and `County_zhvi_uc_condo_tier_0.33_0.67_sm_sa_month.csv`) are in the working directory.
4. Knit the R Markdown file to generate an HTML report with interactive charts and tables.

## Dependencies

- R and RStudio
- R packages: `tidyverse`, `scales`, `gt`, `ggtext`, `knitr`

## File Structure

- `CT_Home_Values_Trends_2018_to_2025.Rmd` – Main analysis and report
- `CT_Home_Value_Trends_2018_to_2025.Rproj` – RStudio project file
- `README.md` – Project overview

## Author

Ryan Mannix

---
