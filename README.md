# Sales Trend Analysis

## Repository Name
`sales-trend-analysis`

## Objective
The goal of this task is to analyze monthly revenue and order volume using SQL queries. This analysis helps in understanding sales trends over time and provides actionable insights for business decisions.

## Tools Used
- PostgreSQL / MySQL / SQLite
- Python (optional, for visualization)
- Jupyter Notebook 
## Files in Repository
| File Name | Description |
|-----------|-------------|
| `sales_trend_analysis.sql` | SQL script containing all queries for monthly revenue and order volume analysis |
| `monthly_revenue.csv` | Exported results table showing revenue and order volume by month |
| `README.md` | This file describing the task, methodology, and files |
| `screenshots/` | Optional folder containing screenshots of output tables or graphs |

## Methodology
1. Connected to the database using SQL/MySQL/PostgreSQL.
2. Extracted month and year from the `order_date` column using `EXTRACT(MONTH FROM order_date)` and `EXTRACT(YEAR FROM order_date)`.
3. Aggregated data to calculate:
   - Total monthly revenue
   - Total monthly order volume
4. Exported the results as a CSV file.

## Results
- The analysis provides a monthly breakdown of revenue and order volume.
- Key insights can be drawn regarding peak sales months and order trends.

