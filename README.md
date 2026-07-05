# Financial-KPI-Dashboard

Financial-KPI-Dashboard is a data-analysis and forecasting project focused on HDFC Bank financial performance. The repository combines cleaned financial statement data, KPI calculations, forecasting workflows, scenario analysis, and dashboard-ready outputs for reporting and analysis.

## Project overview

This project is organized around a complete end-to-end workflow:

- Extract and clean raw financial statement data from balance sheet, income statement, and cash flow sources.
- Calculate core financial KPIs and performance metrics.
- Build forecast models and scenario-based projections.
- Prepare CSV and Excel outputs for dashboard use, including Power BI-ready files.

## Repository structure

- [dashboard/](dashboard/) — dashboard assets, KPI data, Excel files, and Power BI-ready datasets.
- [data/](data/) — raw and processed financial data used throughout the analysis.
- [notebooks/](notebooks/) — Jupyter notebooks for each stage of the workflow.
- [reports/](reports/) — generated reports and exported outputs.

## Notebook workflow

The analysis is split into the following notebooks:

1. [notebooks/01_data_extraction_cleaning.ipynb](notebooks/01_data_extraction_cleaning.ipynb) — loads and cleans raw financial data.
2. [notebooks/02_kpi_calculation.ipynb](notebooks/02_kpi_calculation.ipynb) — computes business and financial KPIs.
3. [notebooks/03_forecasting.ipynb](notebooks/03_forecasting.ipynb) — builds forecast models.
4. [notebooks/04_scenario_modelling.ipynb](notebooks/04_scenario_modelling.ipynb) — evaluates scenarios and sensitivity assumptions.

## Data sources

The repository includes:

- Raw financial statement files in [data/raw/](data/raw/)
- Cleaned processed datasets in [data/processed/](data/processed/)
- Dashboard and forecasting datasets in [dashboard/](dashboard/)

## Getting started

1. Clone the repository.
2. Create and activate a Python environment.
3. Install the required dependencies from [requirements.txt](requirements.txt).
4. Open the notebooks in [notebooks/](notebooks/) and run them in sequence.

## Outputs

The project produces:

- Cleaned financial datasets for analysis.
- KPI metrics and forecast tables.
- Dashboard-ready CSV/Excel files.
- Power BI-compatible files for visualization.

## Notes

The repository name is aligned with the GitHub repository naming convention as Financial-KPI-Dashboard.