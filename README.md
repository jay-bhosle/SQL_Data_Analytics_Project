# SQL Data Analytics Project (Maven Fuzzy Factory)

## Overview
This repository contains an end-to-end SQL analytics workflow for the **Maven Fuzzy Factory** e-commerce dataset. The project builds a relational schema, loads raw CSV extracts, performs data-quality checks, creates cleaned tables, and answers key business questions around traffic, conversion, and revenue performance.

## Tools & Technologies
- **SQL (MySQL syntax)** for schema design, data cleansing, and analytical queries.
- **CSV data ingestion** using `LOAD DATA LOCAL INFILE`.
- **MySQL database engine** to manage relational storage, indexes, and query execution.
- **CSV data ingestion** using `LOAD DATA LOCAL INFILE` for reproducible imports.
- **Relational modeling** across sessions, pageviews, orders, order items, refunds, and products.
- **Data quality checks** executed through SQL queries (counts, null checks, duplicates, orphan detection).

## Data Sources
- Website sessions and pageviews
- Orders, order items, and refunds
- Product catalog

<img width="1920" height="1080" alt="Screenshot (37)" src="https://github.com/user-attachments/assets/298498a9-578a-408c-a55f-55a45b4b3889" />
<img width="1920" height="1080" alt="Screenshot (36)" src="https://github.com/user-attachments/assets/369e0480-d7dc-42ef-9e22-422af7414683" />
<img width="1920" height="1080" alt="Screenshot (35)" src="https://github.com/user-attachments/assets/c75aaf97-86c2-4c17-8bbf-438acdf580b1" />
<img width="1920" height="1080" alt="Screenshot (34)" src="https://github.com/user-attachments/assets/c76b5912-5abf-4665-86ff-5a9b86ab4f26" />
<img width="1920" height="1080" alt="Screenshot (33)" src="https://github.com/user-attachments/assets/01360417-6d0d-46bb-8010-fd3d3e679112" />
<img width="1920" height="1080" alt="Screenshot (32)" src="https://github.com/user-attachments/assets/018a648b-a999-446c-bd60-3627f3dcd53a" />
<img width="1920" height="1080" alt="Screenshot (31)" src="https://github.com/user-attachments/assets/d7f95ad5-050d-40e9-99ac-46ec00afed83" />
<img width="1920" height="1080" alt="Screenshot (30)" src="https://github.com/user-attachments/assets/777e0642-cf10-4dfb-a488-e37e389ac9e5" />
<img width="1920" height="1080" alt="Screenshot (29)" src="https://github.com/user-attachments/assets/e812b48a-1c09-4598-8de9-6a3018d147ad" />
<img width="1920" height="1080" alt="Screenshot (28)" src="https://github.com/user-attachments/assets/36b4f881-51a7-4beb-8f81-9a5b540699df" />


## Achievements
- **Designed and created** a normalized database schema for all core e-commerce entities.
- **Designed and created** a normalized schema covering traffic, orders, product catalog, and refunds.
- **Ingested raw CSV files** and enabled local file loading for reproducible data setup.
- **Validated data quality** with row counts, null checks, duplicate detection, and orphan-record checks.
- **Built cleaned tables** with deduplication and integrity filters for downstream analysis.
- **Built cleaned tables** with deduplication and integrity filters for reliable analytics.
- **Implemented KPI queries** for:
  - Session and order trends (monthly/quarterly)
  - Session-to-order conversion rates
  - Channel performance and conversion
  - Revenue per order and revenue per session
  - Average order value (AOV)
  - Product-level revenue and refund insights

## Results & Insights (Produced by Queries)
The SQL script generates analytics outputs that enable:
- **Trend analysis** of traffic and order volume over time.
- **Conversion funnel monitoring** (sessions → orders) by month and quarter.
- **Channel performance comparison** across paid, organic, and direct traffic.
- **Revenue efficiency metrics** including revenue per order and per session.
- **Merchandise performance insights** to identify top products and refund patterns.

## How to Run
1. Create a MySQL database and ensure `local_infile` is enabled.
2. Update CSV file paths in `SQL Project.sql` to match your local environment.
3. Run the SQL script to build tables, clean data, and execute analytics queries.

---
