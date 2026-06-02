# Edmonton Crime Analysis

End-to-end analysis of 12 months of incident-level crime data from the Edmonton Police Service. Spatial-joins ~290k geocoded incidents to neighbourhood boundaries, normalizes against census population for per-capita rates, surfaces patterns with SQL window functions, and visualizes findings in an interactive Power BI dashboard.

**Status:** in progress

## Data sources
- Incidents: Edmonton Police Service Community Safety Data Portal — Occurrences (rolling 365-day window)
- Neighbourhood boundaries: City of Edmonton Open Data Portal — City of Edmonton Neighbourhoods (`65fr-66s6`)
- Population: City of Edmonton Open Data Portal — 2016 Census, Population by Age Range Neighbourhood/Ward (`phd4-y42v`)

## Tech stack
Python (pandas, GeoPandas), SQLite, Power BI

## Project structure
- `data/` — raw and processed datasets (not tracked; see Data sources above)
- `notebooks/` — Jupyter notebooks for loading, cleaning, spatial join, modeling, analysis
- `sql/` — SQL queries against the SQLite database
- `powerbi/` — Power BI report file
- `visualizations/` — exported charts and dashboard screenshots

## Findings
_To be added._