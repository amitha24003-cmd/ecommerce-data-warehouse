# E-commerce Data Warehouse

## Overview
An end-to-end e-commerce data warehouse implementation using Databricks, PySpark, Delta tables, and SQL. The project uses a Bronze–Silver–Gold architecture to ingest, clean, transform, and prepare data for sales analysis.

## Architecture
**Source CSVs → Bronze → Silver → Gold → Denormalised SQL View → Sales Insights Dashboard**

## Key Features
- Data ingestion and cleaning
- Dimension and fact table creation
- Sales measure calculations
- SQL joins and denormalised view creation
- Dashboard analysis by month, category, weekday/weekend, and hour

## Project Files
- `dim_bronze.ipynb`
- `dim_silver.ipynb`
- `dim_gold.ipynb`
- `fact_bronze.ipynb`
- `fact_silver.ipynb`
- `fact_gold.ipynb`
- `denormalise_final_table.txt`

## Dashboard Findings
- Net amount declined in September and recovered in October 2025.
- Electronics contributed the highest net amount by category.
- Weekday net amount was higher than weekend net amount in the displayed dashboard.

## Tools
Databricks | PySpark | Delta Tables | SQL
