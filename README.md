# 📊 FMCG Data Engineering Pipeline using Databricks

## 🔹 Project Overview
This project implements an end-to-end data engineering pipeline for an FMCG use case where a parent company (Atlikon) acquires a child company (SportsBar). The objective is to consolidate data from both companies into a unified Lakehouse architecture for analytics and decision-making.

The pipeline is built using Databricks and follows the Medallion Architecture (Bronze, Silver, Gold) to ensure data quality, scalability, and efficient processing.

---

## 🔹 Tech Stack
- Python
- SQL
- Apache Spark (PySpark)
- Databricks
- Amazon S3
- Power BI / Databricks Dashboard
- Databricks Genie

---

## 🔹 Architecture

The project follows the Medallion Architecture:

### 🥉 Bronze Layer
- Stores raw data from source systems
- No transformations applied
- Acts as a data backup layer

### 🥈 Silver Layer
- Data cleaning and preprocessing
- Handling null values and duplicates
- Standardization and validation

### 🥇 Gold Layer
- Business-ready data
- Fact and dimension tables
- Used for analytics and dashboards

---

## 🔹 Data Modeling

### Dimension Tables:
- Customer Dimension
- Product Dimension
- Pricing Dimension
- Date Dimension

### Fact Table:
- Sales/Transaction Fact Table
- Contains measures like quantity, revenue, price

---

## 🔹 ETL Pipeline

### Full Load
- Initial data load
- Processes entire dataset
- Used for first-time setup or reprocessing

### Incremental Load
- Processes only new or updated records
- Improves performance and efficiency
- Simulates real-world production pipelines

---

## 🔹 Key Features
- End-to-end ETL pipeline using Spark
- Implementation of Medallion Architecture
- Data consolidation from multiple companies
- Full and Incremental data processing
- Dimensional data modeling (Fact & Dimension)
- Scalable and efficient data pipeline design

---

## 🔹 Dashboard & Analytics
- Developed a combined dashboard for parent and child company
- Provides insights into:
  - Sales performance
  - Customer behavior
  - Product analysis
- Integrated Databricks Genie for natural language querying

---

## 🔹 Project Structure
