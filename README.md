# California Natural Gas Consumption Analysis (1990–2024)
An independent Excel and Tableau project exploring how natural gas consumption varies over time, across California counties, and between sectors.
Explore the Interactive Tableau Dashboard: 
https://public.tableau.com/views/CAGasComsumptiom/Dashboard1

Source: https://www.energy.ca.gov/files/energy-consumption-data-files
# Project Overview
California's natural gas demand differs across counties, economic sectors, and years. This project uses publicly available California Energy Commission (CEC) consumption data to examine historical statewide trends, identify high-consumption counties, and compare residential with non-residential demand.

The analysis covers 1990–2024 and is presented through an interactive Tableau dashboard with year and sector filters.
# Analytical Questions
1. How has California's statewide natural gas consumption changed between 1990 and 2024?
2. Which counties account for the highest natural gas consumption over the selected period?
3. How do leading counties differ by sector?
4. How does residential natural gas consumption compare with non-residential consumption over time?
5. How can county-level consumption and contribution to the statewide total be explored geographically?
# Data Sources
Publisher: California Energy Commission (CEC)
Source: CEC Energy Consumption Data Files
Format: Excel (.xlsx)
Period analyzed: 1990–2024
Consumption unit: Million therms (MMTherms)

The Tableau workbook includes county-level natural gas consumption and statewide natural gas totals. Relevant files listed by the CEC include:
- AGG_CONSUMPTION_NG_COUNTY_TBL_ada.xlsx — annual county-level natural gas consumption.
- TOTAL_NG_TBL_ada.xlsx — annual statewide natural gas totals.
The analysis uses fields for year, county, sector, residential/non-residential category, and consumption, along with calculated fields in Tableau. The source page also provides natural gas utility-level files.

**Data provenance note:** The original data files are maintained by the CEC. This repository is an independent analytical project and is not an official CEC publication.
# Data Preparation
Data preparation and quality checks were performed in Microsoft Excel before dashboard development in Tableau, including:
- Reviewing null or missing values.
- Validating data fields and ensuring appropriate data types.
- Normalizing data for consistent analysis.
- Checking the fields used for yearly, county-level, and sector-level comparisons.
In Tableau, the analysis uses calculated measures for statewide year-over-year percentage change and county share of total consumption.


# DASHBOARD FEATURES
| View | Purpose |

| **Statewide Consumption Trend** | Shows annual statewide natural gas consumption and year-over-year changes. |

| **Top 10 Counties** | Ranks counties by total natural gas consumption for the selected period and sector. |

| **Residential vs. Non-Residential** | Compares historical consumption across residential and non-residential categories. |

| **County Map** | Uses darker shading to identify counties with higher natural gas consumption; tooltips show consumption and county share. |


**Interactive controls:** Year range and sector selections allow viewers to explore consumption patterns across relevant views. County-level information is also available through the map's tooltips.

# Dashboard Views

Top 10 Counties

<img width="952" height="416" alt="Screenshot 2026-11-22 193357" src="https://github.com/user-attachments/assets/75a6095d-d73c-43b0-b0c2-bbcfb4bec2ba" />

Residential V/s Non-Residential

<img width="953" height="410" alt="Screenshot 2026-11-22 194113" src="https://github.com/user-attachments/assets/90e80d75-d7f9-484f-a7e2-258b366b7bca" />


County Map

<img width="956" height="533" alt="Screenshot 2026-11-22 193338" src="https://github.com/user-attachments/assets/98c3f843-99d1-42b8-9af5-e74c0a39b4a5" />


Satewide Consumption Trend

<img width="952" height="418" alt="Screenshot 2026-11-22 194150" src="https://github.com/user-attachments/assets/c397a17d-cc67-485d-84cb-a5307d7da7b9" />

# Key Findings
1. Los Angeles leads overall county consumption. Across the 1990–2024 selection shown in the dashboard, Los Angeles records approximately 102,181.4 MM therms, representing 24.1% of the mapped county consumption total in that view.
2. The leading county varies by sector. Los Angeles leads in commercial, industrial, residential, and transportation/communications/utilities categories, while Kern leads in agriculture and water pumping, and mining.
3. Statewide consumption fluctuates over time. Annual levels show increases and decreases across 1990–2024 rather than a steady directional trend. For example, the dashboard tooltip displays 11,967.3 MM therms in 2023, a 2.2% year-over-year increase.
4. Non-residential consumption exceeds residential consumption in each year displayed on the residential versus non-residential chart.

# Findings reflect the dashboard's depicted selections and source data. Changing the year or sector filters can change county rankings and totals.
# Tools and Skills
- Microsoft Excel: Data preparation, normalization, missing-value checks, data type validation.
- Tableau: Data visualization, geographic mapping, calculated measures, interactive filters, and dashboard development.
- Analytical techniques: Time-series comparison, geographic analysis, sector segmentation, ranking, and year-over-year percentage change.

## Repository Contents

```text
california-natural-gas-analysis/
├── README.md
├── images/
│   ├── dashboard-preview.png
│   ├── county-map.png
│   ├── top-10-counties.png
│   ├── residential-vs-nonresidential.png
│   └── statewide-trend.png
├── dashboard/            # Add your Tableau packaged workbook (.twbx)
└── data/                 # Optional: add redistributable source .xlsx files

```

## Attribution

Data source: **California Energy Commission, Energy Consumption Data Files**. All analysis, visualization design, and interpretations in this repository are part of an independent portfolio project.
