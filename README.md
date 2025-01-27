# SQL-Server-to-Databricks-Data-Pipeline


# Description 
This project leverages Azure Data Factory (ADF) and Databricks to create an efficient and automated data pipeline.

Data Ingestion: ADF is responsible for daily automated extraction of data from SQL Server. This ensures timely and consistent data availability for subsequent processing.
Data Transformation: Extracted data is then seamlessly passed to Databricks for advanced transformations. Databricks, with its powerful Spark engine, enables complex data manipulation, cleaning, enrichment, and feature engineering.
Data Orchestration: ADF acts as the central orchestration layer, managing the entire data flow. It triggers the data extraction, schedules Databricks jobs, monitors the pipeline execution, and handles any potential errors or failures.
Benefits:

Automation: Automates the entire data pipeline, reducing manual effort and improving efficiency.
Scalability: Leveraging Databricks provides excellent scalability to handle large datasets and complex transformations.
Flexibility: ADF offers flexibility in scheduling, data movement, and integration with other Azure services.
Improved Data Quality: Enables data cleansing, transformation, and enrichment to improve data quality for downstream applications.
