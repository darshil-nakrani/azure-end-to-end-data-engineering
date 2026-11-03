# End-to-End Azure Data Engineering Project

## Project Overview

This project demonstrates an end-to-end data engineering solution built using Microsoft Azure services. It covers the complete data engineering lifecycle, including data ingestion, storage, transformation, analytics, and visualization.

Data is fetched from a GitHub repository using Azure Data Factory pipelines and stored in Azure Data Lake Storage Gen2. Azure Databricks and PySpark are used for data processing and transformation. The processed data is queried using Azure Synapse Analytics Serverless SQL Pool, and Power BI is used to develop interactive dashboards.

The project follows the **Medallion Architecture (Bronze, Silver, and Gold)** to organize and manage data across different processing stages.

## Technologies & Tools

| Technology | Purpose |
|---|---|
| GitHub | Dataset source and version control |
| Azure Data Factory | Data ingestion and pipeline orchestration |
| Azure Data Lake Storage Gen2 | Cloud data storage |
| Azure Databricks | Data processing and transformation |
| PySpark | Distributed data processing |
| Azure Synapse Analytics | SQL-based analytics and querying |
| Serverless SQL Pool | Querying data stored in the data lake |
| Power BI | Data visualization and dashboards |
| Service Principal | Authentication and access management |

## Key Features

- End-to-end cloud-based data engineering workflow.
- Automated data ingestion from GitHub using Azure Data Factory.
- Dynamic pipelines using ForEach activities.
- Medallion Architecture implementation.
- Data transformation using Azure Databricks and PySpark.
- SQL querying using Azure Synapse Serverless SQL Pool.
- External tables and SQL views for structured data access.
- Service Principal authentication for secure resource access.
- Interactive dashboards using Power BI.

## Project Architecture

![Azure Data Engineering Architecture](architecture/architecture.png)

## Project Workflow

The project follows an end-to-end data engineering workflow:

1. **Data Source:** CSV datasets are maintained in a GitHub repository.
2. **Data Ingestion:** Azure Data Factory connects to GitHub and ingests datasets using dynamic pipelines and ForEach activities.
3. **Data Storage:** Raw data is stored in Azure Data Lake Storage Gen2.
4. **Data Transformation:** Azure Databricks and PySpark are used to clean, process, and transform the data.
5. **Medallion Architecture:** Data is organized into Bronze, Silver, and Gold layers.
6. **Data Querying:** Azure Synapse Analytics Serverless SQL Pool is used to query data through OPENROWSET, external tables, and SQL views.
7. **Data Visualization:** Power BI connects to the processed data to create interactive dashboards and reports.

## Screenshots

Project implementation screenshots will be added here.

## Author

**Darshil Nakrani**
