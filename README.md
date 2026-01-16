# Databricks End-to-End Retail Lakehouse Project

## Overview
An end-to-end data engineering pipeline built using Databricks Lakehouse architecture.

## Architecture
Bronze → Silver → Gold Delta Lake layers

## Tech Stack
- Databricks
- PySpark
- Delta Lake
- Databricks SQL
- Databricks Workflows

## Pipeline Flow
1. Raw CSV data ingested into Bronze Delta table  
2. Data cleaning and transformation in Silver layer  
3. Aggregated analytics-ready Gold layer  
4. SQL analytics on Gold tables  
5. Pipeline orchestration using Databricks Workflows

## Sample SQL Query
```sql
SELECT * FROM gold_country_sales ORDER BY Revenue DESC;

