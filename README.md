Databricks-14-Days-AI-Challenge:

This repository documents my hands-on journey through the 14 Days AI Challenge, focused on building an enterprise-grade Databricks Lakehouse architecture for large-scale ecommerce data ingestion, transformation, and using AI capabilities of Databricks.

The project demonstrates: - Real-world data engineering workflows - Unity Catalog + Volumes based ingestion - Bronze → Silver → Gold architecture - Apache Spark (PySpark) fundamentals - Preparation for NLP, Sentiment Analysis & Power BI integration

📌 Project Objectives
Build a Lakehouse architecture using Databricks\
Ingest large ecommerce datasets (5GB+)\
Use Unity Catalog + Volumes for governed storage\
Practice Apache Spark transformations\
Prepare data for NLP, sentiment analysis & BI\
Maintain Git-based version control using Databricks Repos + GitHub

🏗️ Architecture Overview (Lakehouse Pattern)
Source (CSV / ZIP files)
        ↓
Bronze Layer (Raw data in Volumes)
        ↓
Silver Layer (Cleaned & validated data)
        ↓
Gold Layer (Aggregations, KPIs, Features)
        ↓
BI / NLP / ML Models
