# Blinkit Sales Analysis Project

## Project Overview

This project focuses on analyzing **Blinkit grocery sales data** to uncover insights related to product performance, outlet characteristics, and sales trends. The goal is to demonstrate **data cleaning, analysis, and visualization skills** using real-world retail data.

The project follows a complete **data analytics lifecycle**:

* Data Cleaning (Excel)
* Data Analysis (Python – Pandas)
* Data Visualization (Power BI)

## Dataset Information

* **Dataset Size:** ~8,500 records
* **Domain:** Retail / Quick Commerce (Grocery Sales)
* **Source:** Simulated / Public Retail Dataset (Blinkit-style data)

### Columns Description

| Column Name               | Description                                  |
| ------------------------- | -------------------------------------------- |
| Item_Identifier           | Unique ID for each product                   |
| Item_Weight               | Weight of the product                        |
| Item_Fat_Content          | Fat content category (Low Fat / Regular)     |
| Item_Visibility           | Percentage of display area allocated         |
| Item_Type                 | Product category                             |
| Item_MRP                  | Maximum Retail Price of the item             |
| Outlet_Identifier         | Unique ID for each outlet                    |
| Outlet_Establishment_Year | Year the outlet was established              |
| Outlet_Size_Cleaned       | Size of the outlet (Small / Medium / Large)  |
| Outlet_Location_Type      | Tier classification of outlet location       |
| Outlet_Type               | Type of outlet (Supermarket / Grocery Store) |
| Item_Outlet_Sales         | Total sales of the item in that outlet       |

## Tech Stack Used

* **Excel** – Data cleaning & preprocessing
* **Python** – Data analysis using Pandas
* **Power BI** – Interactive dashboards & data visualization

## Data Cleaning (Excel)

The dataset contained multiple data quality issues which were handled using Excel:

* Removed duplicates
* Handled missing values (Item_Weight, Outlet_Size)
* Standardized inconsistent values (e.g., `Low Fat`, `low fat`, `LF`)
* Created cleaned categorical columns
* Ensured correct data types for analysis

## Data Analysis (Python – Pandas)

Python was used to perform exploratory data analysis and derive insights:

* Sales distribution across item types
* Impact of outlet size and location on sales
* Relationship between MRP and sales
* Outlet performance comparison
* Year-wise outlet establishment analysis

### Key Python Libraries:

```python
import pandas as pd
import numpy as np
```

## Power BI Dashboard

An **interactive Power BI dashboard** was created to visualize key insights.

### Dashboard Highlights:

* Total Sales & Average Sales KPIs
* Sales by Item Type
* Sales by Outlet Size & Location
* Outlet Type performance comparison
* MRP vs Sales analysis
* Year-wise outlet establishment trend

> Filters included for Outlet Type, Location Type, and Item Type to enable dynamic analysis.

## Key Insights

* Medium-sized outlets generated the highest sales
* Tier 3 locations contributed significantly to total revenue
* Items with moderate MRP showed better sales performance
* Supermarket Type 1 outlets outperformed grocery stores
* Certain item categories consistently drove higher revenue

## Business Use Case

This analysis can help:

* Identify high-performing products and outlets
* Optimize inventory planning
* Improve outlet expansion strategy
* Enhance data-driven decision making in quick commerce businesses

## Future Improvements

* Add predictive sales forecasting
* Perform customer segmentation
* Automate data cleaning using Python
* Deploy dashboard on Power BI Service

## Author

**Prajwal Kawalekar**
Data Analyst | Python | SQL | Power BI | Excel
