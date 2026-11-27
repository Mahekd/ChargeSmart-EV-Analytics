# Data Documentation

## Data Source

- **Provider:** ChargePlace Scotland
- **Source:** Monthly Charge Point Performance Reports
- **URL:** https://chargeplacescotland.org/monthly-charge-point-performance/
- **Initial reporting period:** October 2026
- **File format:** Microsoft Excel (.xlsx)
- **Data type:** Real-world operational data

## Datasets

| Filename | Description |
|---|---|
| sessions_2026_10.xlsx | Charging session records for October 2026 |
| charge_points_2026_10.xlsx | Monthly charging point reliability and infrastructure information |

## Data Directory Structure

- `raw/`: Original datasets downloaded from the official source.
- `processed/`: Cleaned and transformed datasets generated during analysis.

## Reproduction Instructions

1. Visit the official ChargePlace Scotland data portal.
2. Locate the October 2026 monthly reports.
3. Download the Charging Sessions and Charge Point Report files.
4. Rename the files according to the naming convention above.
5. Place both files inside `data/raw/`.

## File Naming Convention

`dataset_name_YYYY_MM.xlsx`

## Data Handling Policy

- Raw datasets will remain unchanged.
- Cleaning and transformation will be performed programmatically.
- Processed datasets will be stored separately.
- Raw and processed datasets are excluded from version control.
- Dataset definitions and analytical limitations will be documented in `data_dictionary.md`.

## Future Data Collection

Additional monthly reports will be incorporated after validating their schema consistency and data quality.