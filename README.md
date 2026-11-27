# ⚡ ChargeSmart — EV Charging Network Analytics

![Status](https://img.shields.io/badge/Status-In%20Progress-orange)
![Python](https://img.shields.io/badge/Python-3.11-blue)
![SQL](https://img.shields.io/badge/SQL-DuckDB-yellow)
![Tableau](https://img.shields.io/badge/Visualization-Tableau-blue)

## Project Overview

ChargeSmart is an end-to-end data analytics project focused on EV charging network usage, operational reliability, and revenue opportunities.

Using real-world operational data from ChargePlace Scotland, this project aims to transform charging transaction records and infrastructure performance data into actionable business insights.

## Business Problem

EV charging network operators need to understand how effectively their existing infrastructure is being utilized before investing in additional charging capacity.

Differences in charging demand, equipment reliability, and financial performance can create operational inefficiencies and potential revenue opportunities.

This project investigates these challenges to support data-driven maintenance, resource allocation, and infrastructure investment decisions.

## Project Objectives

- Identify charging demand patterns across locations and time periods.
- Evaluate charging point usage and operational reliability.
- Identify underperforming charging infrastructure.
- Analyze recorded transaction amounts and energy consumption.
- Compare reliability across manufacturers and local authorities.
- Estimate potential revenue opportunities using scenario-based modeling.
- Develop interactive Tableau dashboards to support business decision-making.

## Dataset

**Source:** ChargePlace Scotland — Monthly Charge Point Performance Reports

**Initial reporting period:** October 2026

The project integrates two datasets:

| Dataset | Description |
|---|---|
| Charging Sessions | Charging transactions, timestamps, session duration, energy consumption, and transaction amounts |
| Charge Point Performance | Charging point reliability, manufacturer, owner, and geographical information |

Official source: https://chargeplacescotland.org/monthly-charge-point-performance/

Additional monthly datasets will be incorporated after schema and data quality validation.

Dataset download instructions are available in [data/README.md](data/README.md).

## Technology Stack

| Technology | Application |
|---|---|
| Python | Data processing and analysis |
| Pandas and NumPy | Data cleaning and transformation |
| Matplotlib and Seaborn | Exploratory data visualization |
| DuckDB and SQL | Data integration and business analysis |
| SciPy | Statistical analysis |
| Tableau | Interactive dashboards |
| Git and GitHub | Version control and project documentation |

## Repository Structure

```text
ChargeSmart-EV-Analytics/
├── data/
│   ├── raw/
│   ├── processed/
│   ├── README.md
│   └── data_dictionary.md
├── notebooks/
├── sql/
├── src/
├── tableau/
│   └── screenshots/
├── reports/
│   └── figures/
├── .gitignore
├── requirements.txt
└── README.md
```

Raw and processed datasets are excluded from version control.

## Analytical Methodology

1. Data collection and understanding
2. Data cleaning and validation
3. Data integration
4. Feature engineering
5. Exploratory data analysis
6. SQL business analysis
7. Statistical hypothesis testing
8. Revenue opportunity modeling
9. Tableau dashboard development
10. Business recommendations

## Analytical Limitations

Revenue opportunity estimates will be based on explicitly documented assumptions and will not be presented as verified revenue losses.

True charger occupancy utilization requires additional information about charger capacity and availability. Dataset definitions and limitations will be validated throughout the analysis.
