# 🚀 AWS Data Pipeline – ETL with PySpark, Glue & S3

### 🧩 Overview
This project demonstrates a scalable **ETL pipeline** built on **AWS** using **S3, Glue, PySpark, and Athena**.  
It simulates a real-world use case of processing raw CSV data into analytics-ready tables.

---

### 🏗️ Architecture
- **Data Source:** Sample CSV files (customer transactions)
- **Storage:** AWS S3 (raw → curated layers)
- **Processing:** AWS Glue (PySpark jobs)
- **Querying:** AWS Athena
- **Orchestration:** AWS Step Functions

---

### ⚙️ Workflow
1. Raw data ingested to `s3://data-pipeline/raw/`
2. Glue ETL job cleans & transforms using PySpark
3. Output saved to `s3://data-pipeline/curated/`
4. Athena used for querying processed data

---

### 📊 Technologies
AWS S3 · AWS Glue · PySpark · Athena · Step Functions · IAM · CloudWatch

---

### 📈 Key Learnings
- Building cost-efficient ETL pipelines on AWS
- Handling schema evolution using Glue Catalog
- Implementing data quality checks and logs

