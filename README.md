# 🏅 Olympic Data Engineering ETL Pipeline using Azure Databricks

## 📌 Project Overview

This project demonstrates an end-to-end Data Engineering pipeline built using Azure Databricks and PySpark to process Olympic datasets. The pipeline follows the Medallion Architecture (Bronze, Silver, Gold) to transform raw data into analytics-ready datasets.

The goal of this project is to simulate a real-world ETL pipeline for data ingestion, transformation, and storage.

---

## 🏗️ Architecture
This project follows Medallion Architecture (Bronze, Silver, Gold):

!(Olympic_2021/architecture.png)

Bronze Layer → Raw Data Ingestion  
Silver Layer → Cleaned and Transformed Data  
Gold Layer → Analytics Ready Data

---

## ⚙️ Technologies Used

- Azure Databricks
- PySpark
- Spark SQL
- Azure Data Lake Storage
- ETL Pipeline
- Medallion Architecture

---

## 🔄 ETL Pipeline Flow

### Bronze Layer
- Ingested raw Olympic dataset from GitHub
- Stored raw data in its original format

### Silver Layer
- Performed data cleaning
- Handled missing and null values
- Standardized column formats

### Gold Layer
- Created curated, analytics-ready datasets
- Applied business transformations
- Prepared data for reporting and analysis

---

## 📊 Dataset Includes

- Athlete details
- Country information
- Medal counts
- Event details

---

## 🚀 Key Features

✔ End-to-End ETL Pipeline  
✔ Medallion Architecture Implementation  
✔ Data Cleaning and Transformation  
✔ PySpark Data Processing  
✔ Analytics-ready Data  

---

## 📂 Project Structure

```
olympic-data-engineering-project/

notebooks/
etl_pipeline.ipynb

data/
raw/
processed/

images/
architecture.png
```

---

## 📈 Sample Use Case

The final Gold Layer dataset can be used to analyze:

- Medal distribution by country
- Athlete performance trends
- Country-wise Olympic performance

---

## 👨‍💻 Author

Your Name

LinkedIn: https://linkedin.com/in/tanzil-ameen-23370521a/

GitHub: https://github.com/tanzilBoi

---

## ⭐ Project Objective

This project was created to gain hands-on experience in building scalable ETL pipelines using Azure Databricks and PySpark and to understand real-world Data Engineering workflows.
