# The Affordability Squeeze
### How Rising Costs Have Outpaced Income Across American Counties (2009–2023)

📊 [View Final Presentation (PDF)](Presentation/STA518-Final-Presentation.pdf)
📄 [View Full Report](https://alyshain.github.io/sta518-project/Report/STA518-Project-Report.html) · 📊 [View Presentation (PDF)](Presentation/STA518-Final-Presentation.pdf)

---

## Overview
This project investigates whether income growth kept pace with inflation across U.S. counties from 2009 to 2023. By combining American Community Survey (ACS) data with Consumer Price Index (CPI) data, we examine trends in real income, housing costs, and poverty at the county level.

## Key Findings
- Prices rose ~42% over the study period
- Income growth lagged significantly in high-poverty counties
- Housing cost burden (spending >30% of income on rent) is concentrated in lower-income areas
- The income growth gap between high- and low-poverty counties is statistically significant (permutation test, p < 0.05)

## Data Sources
| Source | Dataset | Coverage |
|---|---|---|
| U.S. Census Bureau | ACS 5-Year Estimates | 3,000+ counties, 2009–2023 |
| Bureau of Labor Statistics | CPI-U | National inflation index |

## Methods
- County-level panel data construction and cleaning
- Inflation adjustment to 2024 dollars using CPI-U
- Exploratory data analysis and choropleth mapping
- Permutation test to assess statistical significance of income growth differences across poverty tiers

## Tech Stack
`R` · `tidyverse` · `ggplot2` · `sf` · `leaflet` · `tidymodels`

## Authors
Alyshai Nadeem · Camden Davis · Gerrit Mitchell · Thrisha Jawahar

*STA 518 — Grand Valley State University, Winter 2026*
