# 📈 Financial Intelligence Analytics System

A comprehensive end-to-end financial analytics platform that automates the collection, processing, analysis, prediction, visualization, and reporting of stock market data. The system combines **data engineering**, **business intelligence**, **machine learning**, and **automation** to transform raw financial data into actionable insights for investors, analysts, and decision-makers.

## Overview

The **Financial Intelligence Analytics System** is designed to streamline the financial data analysis workflow by integrating multiple components into a single automated pipeline.

The system retrieves historical and live market data, processes and validates the datasets through an ETL pipeline, stores structured data in a SQLite database, applies machine learning models to forecast stock prices, generates interactive dashboards and analytical reports, and automatically distributes professional HTML email reports. It also supports cloud integration for report backup and sharing.

The project demonstrates practical applications of:

* Data Collection and Web Scraping
* ETL (Extract, Transform, Load) Pipelines
* Database Management
* Machine Learning for Financial Forecasting
* Business Intelligence Dashboards
* Automated Report Generation
* Email Automation
* Cloud Storage Integration

By integrating these capabilities into a unified system, the project reduces manual effort, improves reporting efficiency, and provides timely, data-driven insights into financial market performance.

## 🚀 Key Features

* **📊 Automated Financial Data Collection**

  * Retrieves historical stock market data and financial statements.
  * Supports real-time market data acquisition and live streaming.

* **🛠️ End-to-End ETL Pipeline**

  * Cleans, validates, and transforms raw financial datasets.
  * Produces structured datasets ready for analysis and machine learning.

* **🗄️ Database Management**

  * Stores processed financial data in a SQLite database.
  * Enables efficient querying and data persistence.

* **🤖 Machine Learning Price Prediction**

  * Trains predictive models for multiple stocks.
  * Generates future stock price forecasts using historical market data.

* **📈 Interactive Business Intelligence Dashboard**

  * Presents financial metrics through an interactive web dashboard.
  * Displays trends, visualizations, and predictive insights.

* **📑 Automated Report Generation**

  * Produces professional HTML financial reports.
  * Exports consolidated analytical reports in Excel format.

* **📧 Email Reporting Automation**

  * Automatically sends formatted HTML reports to recipients.
  * Supports scheduled and repeatable report distribution.

* **☁️ Cloud Integration**

  * Uploads generated reports to Google Drive for backup and sharing.

* **⚙️ Modular System Architecture**

  * Separates data collection, processing, prediction, reporting, and visualization into independent modules.
  * Promotes maintainability, scalability, and code reusability.

* **📂 Organized Data Pipeline**

  * Maintains structured directories for raw, cleaned, processed, and generated outputs.
  * Simplifies data management throughout the analytics lifecycle.

* **🔄 End-to-End Automation**

  * A single entry-point script (`launch_all.py`) orchestrates the complete workflow from data acquisition to report delivery.

## 🔄 System Workflow

The Financial Intelligence Analytics System follows an end-to-end automated workflow that transforms raw financial market data into actionable insights and professional reports.

<p align="center">
  <img src="assets/system_workflow.png" alt="System Workflow" width="1000">
</p>

### Workflow Overview

1. **System Initialization**

   * The application is launched through `launch_all.py`, which orchestrates the complete workflow.
   * Configuration settings are loaded, and the required services are initialized.

2. **Data Acquisition**

   * Historical stock prices, live market data, and financial statements are collected from external data sources.
   * Multiple data collection modules work together to retrieve the latest available information.

3. **Data Processing (ETL)**

   * Raw datasets are cleaned, validated, standardized, and transformed into structured formats.
   * Processed datasets are prepared for storage, analytics, and machine learning.

4. **Database Storage**

   * Cleaned financial data is stored in a SQLite database for efficient querying and long-term persistence.

5. **Machine Learning**

   * Predictive models analyze historical market trends and generate stock price forecasts.
   * Trained models are stored for future predictions and reuse.

6. **Analytics & Visualization**

   * Interactive dashboards present financial metrics, market trends, and predictive insights.
   * Visualizations help users understand market performance at a glance.

7. **Report Generation**

   * The system generates comprehensive HTML dashboards and Excel reports summarizing financial performance and predictive results.

8. **Report Distribution**

   * HTML reports are automatically delivered via email.
   * Reports can also be uploaded to Google Drive for backup and easy sharing.

### End-to-End Automation

The system integrates data collection, processing, storage, machine learning, visualization, reporting, and distribution into a single automated workflow. This minimizes manual intervention while ensuring timely and consistent financial analysis.

