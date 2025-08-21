# amazon-sales-data-pipeline
Amazon Sales analytics pipeline using Kaggle, dbt, Snowflake, and Power BI

- Overview

This project demonstrates the full data pipeline and analytics process for Amazon sales data.
Starting from finding raw data on Kaggle, the project covers cleaning, transforming, and modeling the data into a structured warehouse in Snowflake, then building insightful dashboards in Power BI.

- Project Workflow

- Data Source

Dataset from Kaggle (Amazon Sales Data).

Connected directly from Kaggle to Google Colab without downloading manually.

- Data Preparation

Cleaned and transformed data using Python (Pandas).

- Designed a star schema with:

3 Dimension tables (Customer, Product, Date).

1 Fact table (Sales).

Data Warehouse (Snowflake)

Loaded the transformed tables directly into Snowflake (cloud data warehouse).

Set primary keys and foreign keys to establish relationships.

Used dbt for data modeling and transformations.

- Visualization (Power BI)

Connected Power BI to Snowflake.

Built interactive dashboards for:

Sales performance.

Customer insights.

Product trends.

Automation

Snowflake ensures centralized and up-to-date data.

Power BI connected to Snowflake with scheduled refresh / DirectQuery for automated updates.

- Tech Stack

Python (Google Colab) – Data cleaning & preparation.

Snowflake – Cloud data warehouse.

dbt – Data modeling & transformations. (i only connected snowflake with dbt an i didnt really use it all of my work was using python)

Power BI – Visualization & dashboards.

- Dashboards & Insights

Total Sales & Revenue trends.

Top-selling products and categories.

Customer demographics and behavior.

Seasonal and monthly sales analysis.

- How to Use

Clone this repository.

Check the Amazon_Sales.ipynb file for data cleaning and transformations in Colab.

Check the amazon_sales.sql file for Snowflake data models.

View the dashboards in Power BI (final project.pbix).

(Optional) Connect Power BI to your Snowflake instance for live reports.

- Results

End-to-end automated pipeline.

Clean star-schema database in Snowflake.

Interactive dashboards powered by Power BI.
