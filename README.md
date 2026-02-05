# SQL Data Analytics Project (Maven Fuzzy Factory)

## Overview
This repository contains an end-to-end SQL analytics workflow for the **Maven Fuzzy Factory** e-commerce dataset. The project builds a relational schema, loads raw CSV extracts, performs data-quality checks, creates cleaned tables, and answers key business questions around traffic, conversion, and revenue performance.

## Tools & Technologies
- **SQL (MySQL syntax)** for schema design, data cleansing, and analytical queries.
- **CSV data ingestion** using `LOAD DATA LOCAL INFILE`.
- **Relational modeling** across sessions, pageviews, orders, order items, refunds, and products.

## Data Sources
- Website sessions and pageviews
- Orders, order items, and refunds
- Product catalog

## Achievements
- **Designed and created** a normalized database schema for all core e-commerce entities.
- **Ingested raw CSV files** and enabled local file loading for reproducible data setup.
- **Validated data quality** with row counts, null checks, duplicate detection, and orphan-record checks.
- **Built cleaned tables** with deduplication and integrity filters for downstream analysis.
- **Implemented KPI queries** for:
  - Session and order trends (monthly/quarterly)
  - Session-to-order conversion rates
  - Channel performance and conversion
  - Revenue per order and revenue per session
  - Average order value (AOV)

## Results & Insights (Produced by Queries)
The SQL script generates analytics outputs that enable:
- **Trend analysis** of traffic and order volume over time.
- **Conversion funnel monitoring** (sessions → orders) by month and quarter.
- **Channel performance comparison** across paid, organic, and direct traffic.
- **Revenue efficiency metrics** including revenue per order and per session.

## How to Run
1. Create a MySQL database and ensure `local_infile` is enabled.
2. Update CSV file paths in `SQL Project.sql` to match your local environment.
3. Run the SQL script to build tables, clean data, and execute analytics queries.

---
