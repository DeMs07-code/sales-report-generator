# Sales Report Generator

Python script that cleans sales data from a CSV file and generates an Excel report with summaries and a chart.

## Features
- Generates sample sales data (CSV)
- Removes empty and duplicate rows
- Calculates totals per product and per day
- Exports an Excel report with 3 sheets (Data, Summary, By Day)
- Adds a bar chart of sales per product

## Tech
Python, pandas, openpyxl

## How to run
1. Install dependencies: `pip install pandas openpyxl`
2. Run: `python report.py`
3. Open the generated `reporte.xlsx`

## Output
An Excel file with the cleaned data, summary tables and a chart.
