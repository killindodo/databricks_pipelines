# databricks_pipelines

Enterprise Data Pipeline: Medallion Architecture on Databricks
Project Overview :-
Designed and deployed a robust, end-to-end ELT (Extract, Load, Transform) data pipeline inside Databricks Free Edition utilizing the Medallion Architecture to process large-scale application event streams. 
The system leverages distributed computing architectures to ensure scalability, reliability, and data integrity.

Key Technical Implementations:

1. Bronze Layer (Raw Ingestion): Ingested raw event streams directly into Delta tables to preserve immutable transaction histories.
2. Silver Layer (Data Enrichment): Developed data-cleansing jobs using distributed SQL queries to enforce schema integrity, drop null-value records, and handle duplicate rows using SELECT DISTINCT.
3. Gold Layer (Analytical Serving): Applied business logic aggregations (grouping by categorical dimensions and aggregating failure event metrics) to serve optimized data models for BI reporting.


Tech Stack Used: > Apache Spark, PySpark, Spark SQL, Databricks Delta Lake.
