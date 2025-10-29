---
title: "End-to-End Lakehouse for Ride-Hailing Analytics (Surge & Safety)"
excerpt: "Built a complete Medallion Lakehouse on Databricks using PySpark and MLflow to forecast surge pricing and implement safety anomaly detection on 3M+ NYC taxi records."
collection: portfolio
date: 2025-01-15
# project_repo: https://github.com/YourGitHubUsername/ride-hailing-lakehouse
---

<!-- <img src="/images/lakehouse_architecture_diagram.png" alt="Architecture diagram of the Databricks Medallion Lakehouse pipeline." style="max-width: 100%; height: auto; margin-bottom: 20px;"> -->

## Project Overview

This project delivers a complete, end-to-end **Data Lakehouse solution** on the **Databricks platform** to solve critical business problems for a ride-hailing service (like Uber/Lyft): predicting demand (for surge pricing) and ensuring passenger safety (anomaly detection). The pipeline processes the massive NYC TLC taxi dataset, demonstrating scalable, production-ready data engineering and MLOps principles.

### Key Technical Workflow & Skills

| Category | Skills / Technologies |
| :--- | :--- |
| **Architecture** | Medallion Lakehouse (Bronze, Silver, Gold), Databricks Delta Lake |
| **Data Processing** | PySpark, Spark SQL, Haversine Distance UDF, Data Cleaning/Filtering |
| **Machine Learning** | Prophet (Time Series Forecasting), Isolation Forest (Anomaly Detection) |
| **MLOps & Tracking** | MLflow for Experiment Tracking and Model Lifecycle Management |

## Core Achievements & Deliverables

* **Lakehouse Architecture:** Developed a complete **Medallion Architecture (Bronze, Silver, Gold)** pipeline on Databricks to process the **3.06 million record NYC TLC taxi dataset** (Jan 2023).
* **Data Quality & ETL:** Engineered a robust ETL pipeline using **PySpark and Spark SQL**, transforming raw data by filtering **~90,000 geospatial and data-quality anomalies** (e.g., zero fares, outside NYC trips) into a clean Silver table.
* **Feature Engineering:** Created essential features like `trip_duration` and implemented a **Haversine distance UDF** to calculate accurate trip distance from raw latitude/longitude points.
* **Surge Forecasting (ML):** Trained and logged a **Prophet forecasting model** on Gold layer time-series data to predict hourly ride demand **7 days out**, achieving a **12.5% MAPE** and providing a direct source for dynamic pricing.
* **Safety Anomaly Detection (ML):** Implemented an **Isolation Forest anomaly detection model** to automatically identify and flag the top **1% of anomalous trips**, creating a mechanism for detecting potential fraud or safety issues.
* **MLOps & Versioning:** Managed the complete machine learning lifecycle using **MLflow**, tracking over 15 experiments, logging model parameters, and saving artifacts to ensure reproducibility.
* **Final Product:** Delivered a final **Databricks Dashboard** visualizing 5,000+ geospatial pickup hotspots and the 7-day surge forecast, providing a unified, actionable view for business operations.

