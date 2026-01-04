# Databricks × DBT End-to-End Data Engineering Project

A comprehensive, production-grade data engineering solution demonstrating best practices for building scalable data pipelines using Databricks, DBT, and the Medallion Architecture (Bronze-Silver-Gold). Worked with this project to learn Databricks and Delta Live Tables in depth. 

## Project Overview

This project showcases an end-to-end data engineering workflow built from scratch, combining industry-leading tools and practices. It implements the complete data lifecycle—from raw data ingestion through transformation to analytics-ready datasets—using modern cloud-native technologies.

**Key Learnings:**
Mastered Databricks cluster management and Apache Spark for distributed computing. Implemented the Medallion Architecture across three layers (Bronze→Silver→Gold) for clean data transformation. Built declarative pipelines using Delta Live Tables with data quality checks. Integrated DBT for SQL-based transformations and testing. Optimized performance through partitioning and caching strategies. Applied Git version control best practices for scalable data engineering workflows.

- Setting up Databricks clusters and workspace configuration
- Building scalable ETL pipelines with PySpark
- Implementing the Medallion Architecture (Bronze → Silver → Gold)
- Data transformation using DBT and Spark SQL
- Data quality testing and validation
- Performance optimization and best practices
- Real-world schema design patterns

## Bronze Ingestion Job Screenshot
<img width="1566" height="554" alt="Bronze Ingestion" src="https://github.com/user-attachments/assets/5d3f0591-2617-4999-aeb7-4191053f9a55" />

## Silver Transformation with Idempotency

| Initial Run | Second run Proving Idempotency |
|---|---|
| <img width="1575" height="836" alt="Silver Pipeline" src="https://github.com/user-attachments/assets/6372ecb7-e767-455a-ba9a-9c8f5735c174" /> | <img width="1598" height="832" alt="Silver 2nd run" src="https://github.com/user-attachments/assets/ca0d5595-ec85-4f12-a06a-2eb01c27777a" /> |



## Key Features

### Data Transformations
- Deduplication and data quality checks
- Type conversions and standardization
- Null value handling and validation
- Slowly Changing Dimensions (SCD Type 2) - (Under Dev)
- Star schema dimensional modeling - (Under Dev)

### Testing & Quality
- Schema validation tests
- Custom data quality checks
- Referential integrity testing - (Under Testing)

### Performance Optimization
- Partition pruning and bucketing
- Materialized views for repeated aggregations - (Learning)
- Optimal file format selection (Parquet/Delta)

### Governance & Security
- Unity Catalog integration
- Row-level and column-level access control
- Data lineage tracking
- Audit logging
