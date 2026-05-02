# Data Quality Check with a FAIR Dataset Using Tableau Prep

## Simran Amesar - 100007050

## Overview
Air Quality dataset contains 2019 urban air quality data from the WHO Global Health Observatory, covering 50 cities across 30 countries. It includes annual average concentrations of PM2.5, PM10, and NO2.

## Cleaning Summary
- Removed duplicate records (London, Berlin)
- Standardised country names (fixed lowercase entries)
- Dropped redundant columns (`Data Source`, `Last Updated`)
- Renamed fields for consistency (e.g. `PM2_5_ug_m3`)
- Added flags to indicate missing values

The dataset is cleaned for better usability and follows FAIR principles:
- **Findable & Accessible**: Simple structure and clear naming
- **Interoperable**: Compatible with SQL, Python, Tableau
- **Reusable**: Documented and free of duplicates
