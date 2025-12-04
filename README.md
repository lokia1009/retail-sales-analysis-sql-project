# Retail Sales Analysis SQL Project

## Project Overview

**Project Title**: Retail Sales Analysis  
**Database**: `sql_project_p1`

This project focuses on building and analyzing a structured retail sales database using SQL, involving data cleaning, exploratory analysis, and business queries to uncover insights on customer demographics, sales trends, and product performance. Advanced SQL techniques like window functions, aggregations and CTEs were used to support data-driven decisions in a retail context.

## Objectives

1. **Set up a retail sales database**: Create and populate a retail sales database with the provided sales data.
2. **Data Cleaning**: Identify and remove any records with missing or null values.
3. **Exploratory Data Analysis (EDA)**: Perform basic exploratory data analysis to understand the dataset.
4. **Business Analysis**: Use SQL to answer specific business questions and derive insights from the sales data.

## Project Structure
### Database Setup

- **Database Creation**: The project starts by importing data from local CSV file and creating a database named `sql_project_p1`.
- **Table Creation**: A table named `retail_sales` is created to store the sales data. The table structure includes columns for transaction ID, sale date, sale time, customer ID, gender, age, product category, quantity sold, price per unit, cost of goods sold (COGS), and total sale amount.
- **Data Quality**: Some columns are in the wrong format (e.g., sale_date as text, sale_time as text), and the dataset contains duplicates and NULL values.


### 1. Data Cleansing
- **1)Data Formatting**: Reformatted inconsistent date and time values into standard SQL formats.
- **1)Duplicates Handling**: Identified and Removed the duplicate rows.
- **1)NULLs Handling**: Identified NULL values in the dataset and delete the records with missing data.

### 2. Exploratory Data Analysis

- **Dimension Exploration**: Analyzed key categorical dimensions such as gender, customer IDs, and product categories using distinct value checks.
- **Date & Time Exploration**: Explored sales timeline by identifying date ranges and time distribution patterns.
- **Measure Column Exploration**: Evaluated numerical metrics like quantity, price, COGS, and total sales for basic statistical insights.
- **Magnitude Analysis**: Assessed overall performance through customer counts, category-wise revenue, and sales distribution.
- **Ranking Analysis**: Ranked customers and weekly sales to identify top and bottom performers.

### 3. Advanced Data Analysis

- **Sales & Revenue Analysis**: Analyzed overall sales performance through monthly revenue summaries, peak sales days and hours, revenue trends, and top customer contributions to understand key drivers of business growth.
- **Profitability & Cost Analysis**: Evaluated business profitability by analyzing gross profit and profit margins across categories, detecting loss-making transactions, and tracking revenue trends using rolling 7-day calculations.
- **Customer Behavior Analysis**: Examined customer purchasing patterns by identifying high-value customers, analyzing gender- and age-based spending, performing RFM segmentation, and classifying repeat vs. one-time buyers.
- **Category Performance Analysis**: Assessed category performance by measuring month-over-month growth, identifying categories with the highest average selling price, and determining gender-wise category popularity.
- **Time-Series & Seasonality Analysis**: Identified key time-series trends by analyzing day-type performance, week-over-week growth, and recurring seasonal revenue patterns.

## 4. Visualization & Dashboards

- **Retail Performance Dashboard**: Built an interactive Power BI dashboard using a matrix visual to present year, quarter, and month-level insights with smooth drill-down capabilities.
- **Dynamic Filtering with Slicers**: Integrated slicers for snapshot day, category, gender, and age group to enable flexible, user-driven exploration of sales and profit data.
- **Category & Demographic Insights**: Displayed detailed metrics—orders placed, quantity sold, revenue, profit, and loss—segmented by category and gender within a single, optimized matrix view.
- **Time-Based Analysis View**: Structured visuals to reveal sales patterns across years, quarters, and months, helping identify seasonality and demand cycles.
- **Dashboard Optimization Techniques**: Improved performance by using only slicers and matrix visuals, avoiding heavy or complex visuals, reducing page load time, minimizing visual clutter, and ensuring faster rendering for a seamless user experience.
- **Comprehensive KPI Presentation**: Presented all essential KPIs in a single consolidated matrix for clearer comparison and efficient decision-making.

## Conclusion

This project provides a clear end-to-end analysis of retail sales data using SQL and Power BI, turning raw data into meaningful insights on sales trends, customer behavior, profitability, and category performance. The final dashboard delivers an easy, interactive way to understand business performance and support better decision-making.

