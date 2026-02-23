# Walmart_Sales_Data_Analysis_End_To_End

Walmart Sales Analysis: End-to-End SQL + Python Project
Project Overview

This project presents a complete end-to-end data analysis workflow built to generate actionable business insights from Walmart sales data. The solution combines Python for data preparation, SQL for advanced querying, and a structured analytical approach to solve real-world business problems.

Project Workflow
1. Environment Setup

Tools Used: Visual Studio Code (VS Code), Python, MySQL, PostgreSQL

Objective: Establish a well-organized project workspace to streamline development and data processing.

2. Kaggle API Configuration

Download the Kaggle API token from your Kaggle account settings.

Save the kaggle.json file inside the local .kaggle directory.

Use the following command to download datasets directly into the project:

kaggle datasets download -d <dataset-path>
3. Acquire Walmart Sales Dataset

Source: Kaggle Walmart Sales Dataset

Storage: Save the dataset inside the data/ folder for structured access and management.

Dataset Link:
https://www.kaggle.com/najir0123/walmart-10k-sales-datasets

4. Install Dependencies & Load Data

Install required Python packages:

pip install pandas numpy sqlalchemy mysql-connector-python psycopg2

Load the dataset into a Pandas DataFrame to begin analysis and transformation.

5. Initial Data Exploration

Perform exploratory analysis to understand the dataset structure and identify potential issues.

Key functions used:

.info() — Review data types and missing values

.describe() — Generate summary statistics

.head() — Preview sample records

6. Data Cleaning & Preparation

Remove duplicate records to ensure data accuracy

Address missing values appropriately (drop or impute where necessary)

Standardize data types (dates → datetime, prices → float)

Clean and format currency fields

Validate dataset integrity after cleaning

7. Feature Engineering

Create additional calculated fields to enhance analytical capabilities:

Compute Total Amount = unit_price × quantity

Add new derived columns to support aggregation and business reporting

These enhancements simplify downstream SQL analysis.

8. Database Integration (MySQL & PostgreSQL)

Establish database connections using SQLAlchemy

Create tables dynamically

Insert cleaned data into both MySQL and PostgreSQL

Validate successful data transfer using test queries

9. SQL-Based Business Analysis

Execute advanced SQL queries to answer key business questions, including:

Revenue trends by branch and product category

Identification of top-performing categories

Sales breakdown by city, time, and payment method

Customer purchase behavior analysis

Profit margin comparison across branches

Peak sales periods and seasonal patterns

Each query is documented with its purpose, logic, and business interpretation.


Requirements

Python 3.8+

PostgreSQL

Required Python Libraries:

pandas

numpy

sqlalchemy

mysql-connector-python

psycopg2

Kaggle API Key


Key Insights

High-performing product categories and revenue-driving branches

Most preferred payment methods

Profitability trends across locations

Customer purchase timing patterns

Branch-level performance comparison

Future Improvements

Integrate with Power BI or Tableau for interactive dashboards

Expand dataset with external business data

Automate the ETL pipeline for real-time updates

Deploy as a data analytics portfolio project with live demo



Acknowledgments

Data Source: Kaggle Walmart Sales Dataset

Inspired by real-world retail analytics and supply chain optimization cases
