# IPL Historical BI

A data pipeline and Power BI dashboard for historical Indian Premier League analysis.

## Project layout

- `data-engineering/bronze`: raw Cricsheet CSV extracts
- `data-engineering/silver`: cleaned and normalized Parquet data
- `data-engineering/gold`: analytics-ready Parquet data
- `powerbi/ipl_analytics.pbix`: Power BI report workbook

## Setup

1. Create a virtual environment and install dependencies: `pip install -r requirements.txt`.
2. Copy `.env.example` to `.env` and supply the required credentials.
3. Put raw source files in `data-engineering/bronze`.
4. Run the Silver and Gold ETL scripts, then refresh the Power BI report.
