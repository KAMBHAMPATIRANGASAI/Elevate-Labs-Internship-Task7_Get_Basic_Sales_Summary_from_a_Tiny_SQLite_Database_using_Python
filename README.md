# Elevate-Labs-Internship-Task7_Get_Basic_Sales_Summary_from_a_Tiny_SQLite_Database_using_Python

# Task 7: Basic Sales Summary from SQLite Database

## Overview
This repository completes Task 7 for the Data Analyst Internship. It creates a small SQLite database, queries sales data for total quantity and revenue per product, prints the summary, and visualizes revenue in a bar chart.

## Files
- task7_sales.ipynb: Jupyter Notebook with all code (DB creation, query, print, plot).
- sales_data.db: The SQLite database file.
- sales_chart.png: Saved bar chart.

## How to Run
1. Open task7_sales.ipynb in Jupyter Notebook.
2. Run all cells (note: Run the insertion cell only once to avoid data duplication).
3. Outputs: Printed summary and bar chart.

## Notes
- SQL Query: SELECT product, SUM(quantity) AS total_qty, SUM(quantity * price) AS revenue FROM sales GROUP BY product.
- Libraries: sqlite3, pandas, matplotlib.
