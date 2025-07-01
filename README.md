# task6 sales_trend_analysis_using_aggregations

This task focuses on analyzing **monthly sales trends** using SQL on a retail dataset. The main goal is to find out how revenue and order volume change over time.

## Files

- **Online Sales Data.csv** – The main dataset containing transaction records.
- **task6 sql script.sql** – SQL file with all queries for analysis.
- **output tables.zip** – The results of SQL queries in table format.

## Tools & Technologies

- **Database**: MySQL Workbench
- **Language**: SQL
- **Functions Used**: `EXTRACT()`, `SUM()`, `COUNT(DISTINCT)`, `GROUP BY`, `ORDER BY`, `WHERE`

## Dataset Overview

The dataset (`Online Sales Data.csv`) includes the following fields:

- `Transaction ID` (order identifier)
- `Date` (order date)
- `Product Category`, `Product Name`
- `Units Sold`, `Unit Price`, `Total Revenue`
- `Region`, `Payment Method`


## SQL Concepts Used

- `EXTRACT(YEAR FROM order_date)`
- `EXTRACT(MONTH FROM order_date)`
- `SUM()` to calculate total revenue
- `COUNT(DISTINCT transaction_id)` to count unique orders
- `GROUP BY` to group data by year and month
- `ORDER BY` to sort results by time
- `WHERE` to filter data for specific time periods


## Insights

- **Highest revenue** was recorded in **November and December**, showing seasonal peaks.
- **Order volume** remained steady, with slight increases during festive months.
- **Regions like North and West** generated the most revenue consistently.
- **Clear seasonality** observed, especially in Q4 (Oct–Dec).

