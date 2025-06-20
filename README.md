### 📊 COVID-Era Food Price Impact Analysis
# 🔍 Project Overview

The COVID-Era Food Price Impact Analysis project investigates how the pandemic influenced global food prices, using over 1 million records sourced from open datasets. The goal was to process, clean, and analyze these large datasets to uncover price trends, supply chain fluctuations, and inflation indicators that emerged during the crisis.

This end-to-end project includes data ingestion via Azure, transformation using Python, and visualization through Looker, providing actionable insights to support policy makers and crisis planners in better understanding the economic impact of COVID-19.
🛠️ Tools & Technologies
Category	Tools Used
Programming	Python (Pandas, NumPy, Matplotlib)
Cloud	Azure Data Factory, Azure Blob Storage
Data Processing	Azure Data Lake, Python
Data Visualization	Looker
Data Format	CSV, Parquet
Documentation & Collaboration	Git, GitHub, Markdown
⚙️ Pipeline Architecture

Data Sources (Global Food Price Datasets)
        ↓
Azure Blob Storage (Raw Data)
        ↓
Azure Data Factory (ETL Pipelines)
        ↓
Python Data Cleaning & Transformation
        ↓
Processed Data to Azure Data Lake (Parquet Format)
        ↓
Looker Dashboard for Visualization & Analysis

📈 Key Features

    Ingested 1M+ global food price records into Azure.

    Implemented an automated ETL pipeline to clean and transform raw data for downstream analytics.

    Used Python for handling missing data, outlier detection, and calculating inflation-related metrics.

    Converted processed data to Parquet for efficient querying and storage.

    Developed an interactive Looker dashboard for tracking:

        Food price fluctuations by country and commodity

        Monthly inflation trends across different regions

        COVID-specific anomalies and cost surges

🔎 Insights & Impact

    Identified a 25% global surge in food prices during the peak pandemic period (2020–2021), primarily in staple categories like rice, wheat, and pulses.

    Discovered correlation between lockdown timelines and regional price spikes using time-series visualizations.

    Analysis contributed to a research paper focused on inflation resilience and food supply chain vulnerabilities in global health crises.

    Project demonstrates real-world use of cloud-based data engineering pipelines to deliver actionable insights for public policy and crisis mitigation.

📁 Project Structure

covid_food_price_analysis/
├── data/
│   ├── raw/              # Original datasets (CSV)
│   └── processed/        # Cleaned datasets (Parquet)
├── notebooks/
│   └── data_cleaning.ipynb
├── dashboards/
│   └── looker_dashboard_sample.png
├── scripts/
│   └── etl_pipeline.py
├── reports/
│   └── inflation_trend_report.pdf
├── README.md

📌 What I Learned

    Scalable ETL orchestration using Azure Data Factory

    Data transformation best practices with Python and Pandas

    Using Parquet for performance-optimized data storage

    Designing user-centric dashboards in Looker

    Applying data analytics to real-world socio-economic crises
