# RetailBank - Customer Transaction Analytics

Cloud-native data engineering solution for the HCL AI-Cloud Data Engineering Hackathon.

## Objective

Build an automated AWS data pipeline that ingests retail banking data, performs data quality and cleansing, creates a curated analytical model, processes incremental Day 2 data, and generates business KPIs.

## Technology Stack

- Amazon S3
- AWS Glue
- AWS Glue Data Quality
- Amazon Athena
- AWS Step Functions
- AWS Lambda
- Amazon CloudWatch
- AWS IAM
- Python / PySpark
- SQL

## Pipeline

Source Files → S3 Raw → Glue ETL & Data Quality → Curated Athena → KPI Analytics

Invalid records → S3 Quarantine

## Project Status

🚧 In development
