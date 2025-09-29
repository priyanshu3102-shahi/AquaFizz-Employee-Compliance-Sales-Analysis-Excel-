# AquaFizz — Employee Compliance & Sales Analysis

**Type:** Excel dashboard & analysis  
**Short:** Employee timing compliance + sales/profit analysis and dashboard.

## Overview
This Excel project checks employee compliance with benchmark working hours and analyzes sales/profit behaviour across products, customers, and cities. Final deliverable: an interactive Excel dashboard.

## Datasets (included)
- `workers_timing.csv` — entry/exit times per employee (columns: employee_id, date, entry_time, exit_time)
- `orders.csv` — (order_id, customer_id, beverage, cost_price, selling_price, date)
- `customers.csv` — (customer_id, name, city, other fields)

## Files
- `AquaFizz_Dashboard.xlsx` — the interactive Excel workbook + dashboards.
- `Workers Timing_final.xlsx`- the dataset with checked employee compliance in accordence with benchmark hours
- `data/` — CSV versions of the above data for reproducibility.
- `README.md`

## What I did
- Checked employee compliance with benchmark hours (per-day/per-month).
- Calculated profit per sale and identified highest profit-margin beverages.
- Top customers and cities by revenue.
- Monthly profit trends & visualization.
- Final dashboard exported in Excel.

## How to view
- Open `AquaFizz_Dashboard.xlsx` in Excel (2016+ recommended).
- If any macros are used, enable macros (only if you trust the file).
- Use the dashboard tabs and slicers to filter by date / beverage / city.

## Notes
- `data/` contains sample CSVs — raw data with PII must not be uploaded publicly. If real data is sensitive, replace with anonymized samples or host privately.
