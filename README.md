# Data Warehouse and Analytics Project

Welcome to the **Data Warehouse and Analytics Project** repository! 🚀

This project demonstrates the design and implementation of a modern **data warehouse and analytics solution using SQL Server**, covering the complete data pipeline from raw source data to actionable business insights.

The project follows a **Medallion Architecture** consisting of Bronze, Silver, and Gold layers, and uses an **ELT approach** to ingest, clean, transform, and model data into a business-ready **Star Schema**.

The goal of this project is to demonstrate practical skills in **data warehousing, SQL development, data transformation, dimensional modeling, and analytics**, following industry best practices.



## Data Architecture

![Data Architecture](docs/data_architecture.png)

The project follows a **Medallion Architecture** consisting of three main layers:

* **Bronze Layer:** Stores raw data as-is from the source systems, preserving the original data for traceability and reprocessing.
* **Silver Layer:** Cleans, validates, and transforms the raw data to prepare it for analytical use.
* **Gold Layer:** Contains business-ready data organized into a **Star Schema** with fact and dimension tables for reporting and analytics.


## 📖 Project Overview

This project involves:

1. **Data Architecture**: Designing a modern data warehouse using **Medallion Architecture**, consisting of **Bronze, Silver, and Gold** layers.
2. **ELT Pipelines**: Extracting and loading data from source systems, then transforming it within the data warehouse.
3. **Data Modeling**: Developing **fact and dimension tables** organized into a **Star Schema** for efficient analytical querying.
4. **Analytics & Reporting**: Creating **SQL-based reports and analytical queries** to generate actionable business insights.



## 🛠️ Important Links & Tools

The tools and resources used in this project are freely available:

* **Datasets**: CSV files used as the source data for the data warehouse.
* **SQL Server Express**: Database engine used to build and host the data warehouse.
* **SQL Server Management Studio (SSMS)**: Used to develop, execute, and manage SQL scripts and databases.
* **GitHub**: Used for version control and project documentation.
  

## 🚀 Project Requirements

### Building the Data Warehouse (Data Engineering)

#### Objective

Develop a modern **data warehouse using SQL Server** to consolidate sales data from multiple source systems, enabling efficient analytical reporting and supporting data-driven decision-making.

#### Specifications

* **Data Sources:** Import sales data from two source systems, **ERP and CRM**, provided as CSV files.
* **Data Quality:** Identify, cleanse, and resolve data quality issues before loading the data into the analytical layer.
* **Data Integration:** Integrate data from both source systems into a unified, user-friendly data model optimized for analytical queries.
* **Architecture:** Implement a **Medallion Architecture** with Bronze, Silver, and Gold layers.
* **Data Modeling:** Build a **Star Schema** consisting of fact and dimension tables in the Gold layer.
* **Processing Approach:** Use an **ELT approach**, loading raw data first and performing transformations within SQL Server.
* **Scope:** Focus on the latest available dataset; historical data tracking and historization are not required.


### BI: Analytics & Reporting (Data Analysis)

#### Objective

Develop **SQL-based analytics and reporting** to generate actionable insights into:

* **Customer Behavior**
* **Product Performance**
* **Sales Trends**

These insights provide stakeholders with **key business metrics and data-driven insights**, supporting informed decision-making and a better understanding of business performance.
