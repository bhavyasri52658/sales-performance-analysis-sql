# Sales Performance Analysis Using SQL

## Project Overview

This project analyzes sales data using PostgreSQL to identify revenue trends, top-performing products, category performance, regional sales patterns, and salesperson performance.

The objective is to transform sample sales records into meaningful business insights using SQL.

## Tools Used

- PostgreSQL
- SQL
- pgAdmin
- GitHub

## Dataset

The dataset contains 20 sample sales records covering January to May 2026.

The sales table includes:
- Sale ID
- Product name
- Product category
- Region
- Salesperson
- Quantity
- Unit price
- Sale date
- Sale status

Cancelled sales are excluded from revenue calculations.

## SQL Concepts Used

- SELECT, WHERE, and ORDER BY
- GROUP BY and aggregate functions
- CASE-independent filtering and conditional aggregation
- Common Table Expressions (CTEs)
- Date functions and DATE_TRUNC
- LAG() for previous-month comparisons
- RANK() for salesperson rankings
- Window functions and running totals
- KPI calculations

## Business Questions Answered

1. What is the total revenue from completed sales?
2. Which products generate the most revenue?
3. Which category performs best?
4. Which region generates the most revenue?
5. Who is the top-performing salesperson by revenue?
6. How does monthly revenue change?
7. What is the month-over-month revenue growth?
8. Which products sell the most units?
9. What percentage of sales are cancelled?
10. What is the average completed sale value?
11. How do categories perform across regions?
12. What is the cumulative revenue over time?

## Key Findings

- Total sales records: 20
- Completed sales: 18
- Cancelled sales: 2
- Total completed revenue: ₹649,500
- Average completed sale value: ₹36,083.33
- Cancellation rate: 10%
- Highest-revenue product: Laptop, generating ₹300,000
- Highest-revenue category: Electronics, generating ₹517,500
- Highest-revenue region: South, generating ₹252,000
- Top salesperson: Ananya, generating ₹272,000
- Highest monthly revenue: January, at ₹175,000
- March revenue increased by 37.95% compared with February.

These findings are based on the sample dataset and do not represent real business performance.

## Project Structure

```text
sales-performance-analysis-sql/
├── sales_performance_analysis.sql
└── README.md
```

## How to Run

1. Open PostgreSQL using pgAdmin or another compatible SQL editor.
2. Create or select a database.
3. Open `sales_performance_analysis.sql`.
4. Execute the script in order.
5. Review the results of each query.

If the tables already exist, use a fresh database or remove the existing `sales_data` table before rerunning the complete script.

## Skills Demonstrated

This project demonstrates practical SQL skills in revenue analysis, data aggregation, regional comparisons, salesperson performance analysis, month-over-month growth calculations, ranking, and KPI reporting.

## Author

Bhavya
