# AzureProjectWithCICD

This project implements an end-to-end data engineering pipeline
using a Bronze–Silver–Gold architecture on Azure.

## Architecture Overview
- Stage 1: CSV ingestion from HTTP-based source to Bronze layer (Parquet)
- Stage 2: Data transformation from Bronze to Silver layer (Delta)
- Stage 3: Aggregated analytics-ready data in Gold layer (Delta)

## Technologies Used
- Azure Data Factory
- Azure Data Lake Gen2
- Azure Devops
- Azure Databricks
- Delta Lake
- PySpark

## Documentation
- Stage 1: docs/01_stage1_csv_to_bronze.md
- Stage 2: docs/02_stage2_bronze_to_silver.md
- Stage 3: docs/03_stage3_silver_to_gold.md

This repository is structured to demonstrate practical
data engineering concepts and best practices.
