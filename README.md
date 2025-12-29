📊 E-Commerce SQL Analysis (Online Retail Dataset)
🔍 Project Overview

This project performs an end-to-end SQL analysis of an online retail dataset to uncover insights related to sales performance, customer behavior, product contribution, and seasonality.

The goal of this project is to demonstrate practical SQL skills, real-world data handling, and the ability to translate business questions into data-driven insights.

🧰 Tools & Technologies

SQL (SQLite)

Online SQL editors: SQLiteOnline / DB Fiddle

Dataset: Online Retail (transaction-level data)

GitHub for version control and portfolio presentation

📁 Repository Structure
ecommerce-sql-analysis/
│
├── README.md

├── queries.sql

└──  screenshots/

   ├── 01_executive_summary_metrics.png
   
   ├── 02_monthly_sales_query.png
   
   ├── 03_monthly_sales_output.png
   
   ├── 04_peak_sales_months.png
   
   ├── 05_top_products.png
   
   ├── 06_top_customers.png
   
   ├── 07_customer_segmentation.png
   
   └── 08_high_sales_low_margin_proxy.png
   


📌 Business Questions Addressed
1️⃣ Executive Summary Metrics

What is the total sales revenue?

How many unique customers and orders exist?

2️⃣ Sales Trend & Seasonality

How do monthly sales trend over time?

Which months are peak sales periods?

3️⃣ Product Performance

Which products generate the highest revenue?

Are there high-sales products that may indicate low-margin risk?

⚠️ Note: The dataset does not include Profit or Cost columns.
Therefore, proxy metrics such as average unit price and revenue per order were used to flag potential margin risks.

4️⃣ Customer Analysis

Who are the top customers by lifetime revenue?

What is the split between one-time vs repeat customers?

How much revenue is contributed by repeat customers?

🧠 Key Insights

Sales show clear monthly seasonality, with identifiable peak months.

A small set of products contributes a significant portion of total revenue.

Repeat customers form a smaller portion of users but contribute a disproportionately high share of revenue.

Certain high-volume products exhibit low average unit prices, indicating possible margin pressure and the need for pricing or cost review.

🧪 Data Handling & Assumptions

Inconsistent date formats in InvoiceDate were handled using string parsing functions.

Rows with missing CustomerID were excluded from customer-level analysis.

Profitability analysis was performed using proxy measures due to lack of cost/profit data.

All assumptions are explicitly documented to reflect real-world analytical constraints.

▶️ How to Reproduce This Analysis

Load the dataset into a SQLite environment.

Run the queries in slq queries sequentially.

Review outputs (screenshots included for reference).

👤 Author

Jahanvi Shrivastava
Aspiring Business / Data Analyst
GitHub: https://github.com/jahanvi2912
