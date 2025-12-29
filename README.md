# E-Commerce SQL Analysis — Online Retail

## Project overview
This project analyzes the Online Retail dataset using SQL (SQLite) to extract business insights about sales, product performance, customer value, and seasonality. The analysis includes data cleaning (handling inconsistent InvoiceDate), KPI creation, and strategic flags for the business.

## Tools
- SQLite (sqliteonline.com / db-fiddle)
- SQL (aggregation, CASE, string parsing)
- Screenshots of queries & outputs included

## Key business questions answered
1. What are the executive metrics (total sales, customers, orders)?
2. How do monthly sales trend over time?
3. Which months are peak sales months?
4. What are the top products by revenue?
5. Who are the top customers by lifetime revenue?
6. How many customers are one-time vs repeat?
7. Which high-sales products may have low margin risk? (proxy analysis because Profit column is not provided)

> **Note:** This dataset does not include a Profit or Cost column. Where direct profit is required, I used **proxy metrics** (average unit price and revenue per order) and explicitly document assumptions.

## Files
- `queries.sql` — all final SQL queries (commented).
- `screenshots/` — query and result screenshots.
- `dataset/online_retail_sample.csv` — small sample (optional).

## Key insights (summary)
- Monthly seasonality identified; peak months are shown in screenshots.
- Top products and top customers identified for retention and inventory decisions.
- Repeat customers contribute a significant portion of revenue.
- Using avg unit price & revenue per order, certain high-sales SKUs are flagged for margin review.

## How to reproduce
1. Load the dataset into SQLite (or use the exported SQL file).
2. Run queries from `queries.sql` in order. Relevant queries include data cleaning (create `clean_retail` view), KPI queries, product/customer aggregations, and proxy margin analysis.

## Contact / Repo author
- [Your Name] — (use the name you put on GitHub)
- Link to portfolio/resume: (optional)

