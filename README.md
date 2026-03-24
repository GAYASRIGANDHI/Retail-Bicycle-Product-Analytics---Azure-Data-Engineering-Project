# 🚀 Retail Bicycle Product Analytics Pipeline using Azure

## 📌 Overview

This project demonstrates an end-to-end Azure Data Engineering pipeline built to analyze bicycle product performance using the Adventure Works dataset.

The goal is to design a scalable and efficient data pipeline that ingests, transforms, and analyzes retail data to generate business insights.

---

## 🎯 Objectives

* Analyze bicycle product sales and revenue
* Identify top-performing products
* Understand customer and regional trends
* Build a scalable data pipeline using Azure

---

## 🛠 Tech Stack

* Azure Data Factory (ADF)
* Azure Data Lake Storage Gen2 (ADLS)
* Azure Databricks (PySpark)
* SQL

---

## 📂 Dataset

* Adventure Works dataset (sample data)
* Source: Kaggle
* Domain: Retail (Bicycle sales, customers, products)

---

## 🏗 Architecture

Bronze → Silver → Gold architecture

* **Bronze Layer**: Raw data ingestion from source
* **Silver Layer**: Data cleaning and transformation
* **Gold Layer**: Aggregated data for analytics

---

## ⚙️ Project Workflow

1. Data ingestion using Azure Data Factory
2. Storage in ADLS Gen2 (Bronze layer)
3. Data transformation using PySpark (Silver layer)
4. Aggregation and analytics (Gold layer)
5. Pipeline orchestration and scheduling using ADF

---

## 📊 Key Analysis

* Revenue by bicycle product
* Sales trends over time
* Region-wise performance
* Customer purchase behavior

---

## ✨ Features

* End-to-end data pipeline
* Incremental data loading
* Data quality checks
* Cost-optimized design

---

## 📁 Project Structure

* data/ → sample dataset
* pipelines/ → ADF pipeline files
* notebooks/ → Databricks code
* sql/ → SQL queries
* architecture/ → architecture diagram

---

## 🚀 Outcome

Built a scalable and cost-efficient Azure data pipeline to analyze retail bicycle product performance and generate actionable insights.

---

## 📌 Future Enhancements

* Real-time data processing using streaming
* Power BI dashboard integration
* Advanced analytics and forecasting
