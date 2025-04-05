# Azure Olympics Data Engineering Project

## 🚀 Overview
This project is a complete end-to-end Azure Data Engineering workflow using tools like Azure Data Factory, Azure DevOps, Databricks, PySpark, Delta Live Tables, and Spark Structured Streaming. It includes real-time ingestion, transformation, orchestration, CI/CD implementation, and big data analytics using a Medallion Architecture.

## 🔑 Key Features
- Real-Time ETL Pipelines – Using ADF and Spark Streaming.
- CI/CD with Azure DevOps – Automated deployment with Git integration.
- Delta Lake & Time Travel – Efficient storage with Delta tables.
- Data Orchestration – Managed via Databricks Workflows.
- Dynamic Notebooks & Utilities – Implemented using Databricks Utilities.
- Structured Streaming & CDC – For continuous and incremental processing.

## 🛠️ Technologies Used
- Azure Data Factory (ADF) – Real-time and batch data ingestion.
- Azure DevOps – CI/CD pipelines and Git integration.
- Azure Data Lake Storage Gen2 – Scalable storage for structured/unstructured data.
- Azure Databricks with Unity Catalog – Secure and scalable Spark-based processing.
- PySpark – For large-scale transformations and analytics.
- Delta Live Tables – For simplified and reliable pipelines.
- Spark Structured Streaming – For real-time data ingestion.

## 🏗️ Data Architecture
The architecture follows a modern Medallion Architecture:
1. Bronze Layer – Raw data ingested from GitHub using Azure Data Factory.
2. Silver Layer – Cleaned and transformed using PySpark in Databricks.
3. Gold Layer – Aggregated and analytics-ready data with Delta Live Tables.
4. Streaming Layer – Real-time CDC and streaming data handled by Spark Structured Streaming.
5. Orchestration – Using Databricks Workflows and integrated with Azure DevOps for CI/CD.
![image](https://github.com/user-attachments/assets/10cfc478-3342-4e4c-a7f2-6e954e992ce1)


## 📁 Data Sources
- GitHub Repositories – Public datasets ingested via ADF.
- Olympic Dataset – Sample data processed through medallion layers.

## 🔄 Key Components in Action
- 🧪 Data Ingestion – Azure Data Factory pulls datasets dynamically from GitHub.
- 🔁 Transformation – PySpark handles complex logic for cleaning and enrichment.
- 💾 Storage – Delta Lake stores data efficiently across bronze, silver, and gold layers.
- 🚀 Automation – DevOps pipelines enable CI/CD across environments.
- ⚙️ Orchestration – Databricks Workflows streamline notebook scheduling and execution.
- 📊 Streaming & CDC – Spark Structured Streaming enables real-time updates and Change Data Capture.

---

Happy Learning! 🏅

