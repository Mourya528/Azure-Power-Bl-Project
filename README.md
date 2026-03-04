# Azure SQL + Power BI Analytics Project

## Overview

This project demonstrates an end-to-end analytics workflow using
Microsoft Azure SQL Database and Power BI. The goal of the project is to
store raw product data in the cloud, clean it using SQL, and create
interactive dashboards in Power BI to generate business insights.

The dataset contains information about men's shirt products including
brand names, product titles, original prices, and sale prices. The data
was uploaded into Azure SQL Database, cleaned using SQL queries, and
then connected to Power BI Desktop for analysis and visualization.

## Project Architecture

Data Source → Azure SQL Database → Data Cleaning (SQL) → Power BI →
Interactive Dashboard

## Dataset

The dataset contains the following columns:

-   Brand -- Clothing brand name\
-   Title -- Product title or description\
-   Original_Price -- Listed price of the product\
-   Sale_Price -- Discounted selling price

Some records contained NA values and formatting inconsistencies which
were handled during the data cleaning stage.

## Data Cleaning Steps

Data preparation was performed using SQL and Power Query:

-   Removed special characters from price columns\
-   Converted text values such as NA into proper missing values\
-   Standardized price formats\
-   Verified numeric fields for calculations

## Calculated Metrics (DAX)

Additional business metrics were created in Power BI using DAX:

-   Discount % -- Difference between original and sale price\
-   Profit % -- Estimated profit margin\
-   Cost Price -- Derived using sale price and profit percentage

These calculations allow deeper analysis of product pricing and
profitability.

## Dashboard Insights

The Power BI dashboard includes multiple visualizations:

-   Top 5 brands by average discount %\
-   Top 5 brands by highest profit %\
-   Top 5 brands by number of product varieties\
-   Top 5 brands by average sales price\
-   Bottom 5 brands by profit %

These visualizations help identify pricing strategies, brand
performance, and profitability trends.

## Tools & Technologies

-   Microsoft Azure SQL Database
-   SQL (Data Cleaning & Transformation)
-   Power BI Desktop
-   Power Query
-   DAX (Data Analysis Expressions)

## Key Skills Demonstrated

-   Cloud database management (Azure SQL)
-   SQL-based data cleaning
-   Data modeling and transformation
-   DAX calculations
-   Business intelligence dashboard development
-   Data visualization and insights generation

## Files Included

-   Men+Tshirt.csv -- Source dataset\
-   Clothing_Visualization.pbix -- Power BI report\
-   README.md -- Project documentation

## Author

Mourya Teja\
Azure \| SQL \| Power BI \| Data Analytics
