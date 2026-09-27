# Sales Data Analytics | Azure SQL & Power BI

**Author: Pranav VVS**

## Project Overview

An end-to-end data analytics project focused on analyzing T-shirt sales data using Microsoft Azure, Azure SQL Database, Power Query, and Power BI.

The project demonstrates the process of importing raw sales data into a cloud-based SQL database, performing data cleaning and transformation, creating analytical metrics, and developing an interactive Power BI report.

## Technology Stack

- Microsoft Azure
- Azure SQL Database
- Microsoft SQL Server
- SQL / T-SQL
- Power Query
- Power BI
- DAX

## Data Pipeline

CSV Dataset  
↓  
Azure SQL Database  
↓  
SQL Data Cleaning  
↓  
Power Query Transformation  
↓  
Calculated Metrics  
↓  
Power BI Dashboard

## Data Preparation

The dataset was imported into an Azure SQL database and connected to Power BI for further analysis.

Data preparation included:

- Handling missing and invalid values
- Removing records where both original price and sales price were unavailable
- Converting price fields from text to numeric data types
- Cleaning price-related fields
- Creating derived analytical fields

## Calculated Metrics

The analysis includes the following metrics:

- Original Price
- Sales Price
- Discount
- Cost Price
- Profit
- Profit Percentage

These metrics were used to analyze pricing, discount patterns, brand-level performance, and profitability.

## Power BI Analysis

The Power BI report provides analysis of:

- Brand-wise average discount
- Brand-wise profitability
- Sales price patterns
- Cost and profit analysis
- Top brands based on selected business metrics

## Project Files

| File | Description |
|---|---|
| `TshirtsMen.pbix` | Power BI report containing the data model, transformations, calculations, and visualizations |
| `Men+Tshirt.csv` | Source dataset used for the analysis |

## Key Skills Demonstrated

- SQL data preparation and transformation
- Azure SQL database integration
- Power Query data cleaning
- Data modeling
- DAX calculations
- Business data analysis
- Power BI dashboard development
- Data visualization

## Project Outcome

This project demonstrates an end-to-end data analytics workflow, combining cloud-based data storage, SQL-based data preparation, Power Query transformations, analytical calculations, and Power BI visualization to derive business insights from sales data.
