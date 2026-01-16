# Databricks End-to-End Retail Lakehouse Project

## 📌 Overview
This project demonstrates an end-to-end data pipeline using Databricks Lakehouse. 
It ingests raw sales data, transforms it through Bronze, Silver, and Gold layers, 
and performs analytics using SQL.

## 📊 Architecture
The pipeline follows a Medallion architecture:
- **Bronze Layer**: Raw data ingestion
- **Silver Layer**: Data cleaning & transformation
- **Gold Layer**: Aggregated analytics tables

## 🚀 Technologies
- Databricks
- PySpark
- Delta Lake
- Databricks SQL
- Workflows

## 🧠 Pipeline Steps
1. Ingest raw CSV into Bronze Delta table  
2. Clean & transform into Silver layer  
3. Aggregate data into Gold layer  
4. Run SQL analytics  
5. Schedule notebooks using Workflows

