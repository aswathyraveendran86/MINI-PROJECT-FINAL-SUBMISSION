# MINI-PROJECT-FINAL-SUBMISSION
Superstore sale analysis visualisation in powerbi# Superstore Sales Analysis

 Project Overview

This Power BI project focuses on analyzing Superstore sales data to understand sales performance, profitability, product performance, and discount impact.
The project uses Microsoft Excel, Power Query, and Power BI for data cleaning, transformation, analysis, and visualization.Three interactive dashboards were developed to provide insights into overall sales performance, regional and category-wise profitability, product quantity sold, and the relationship between discounts and profit.The dashboards include KPI cards, charts, slicers, and interactive filters to support data-driven business decisions.

 Dataset Information

 Superstore Sales Dataset
 Total Records: 9,994 rows
 Tools Used for Preparation: Microsoft Excel and Power Query
 Visualization Tool: Microsoft Power BI
 
 1. Data Preparation (Excel & Power Query)

  -The Superstore sales dataset was initially inspected in Microsoft Excel and then imported into Power Query for data cleaning and transformation.
  -Checked the dataset structure and column names.
  - Verified that the dataset contained 9,994 rows and 21 columns.
  - Reviewed the data before performing cleaning operations.

2. Data Cleaning Using Power Query

  The following data cleaning operations were performed:

  - Assigned appropriate data types to columns.
  - Removed completely identical duplicate records.
  -Deleted empty rows from the dataset.
  -Removed unnecessary leading and trailing spaces from text values.
  - Standardized text formatting using the Capitalize Each Word transformation.
  -Improved consistency in text columns.
  - Checked column quality to identify valid values, errors, and empty values.

3.Data Transformation

Created the following calculated columns using Power Query:
- Sales Category: Categorized sales values.
- Discount Category: Grouped discount values into categories.

4. Additional Analysis Tables

Prepared additional analysis tables 
- State-wise Profit Analysis.
- Category-wise Profit Analysis.
- Average Sales Analysis.

5. Final Data Preparation in Power BI

After cleaning and transformation, the prepared dataset was used for further analysis and dashboard development in Microsoft Power BI.
The cleaned Superstore sales dataset was imported into Microsoft Power BI Desktop for data modeling, calculations, and visualization.

 1. Data Modeling
- Imported the cleaned sales dataset into Power BI.
- Reviewed the data using Data View and Model View.
- Prepared the dataset for analysis and report development.

 2. DAX Measures

Created the following DAX measures to calculate key business performance indicators.

Using this DAX Formulas
Total Sales =SUM(Sales)
Total Profit =SUM(Profit)
Total Orders =DISTINCTCOUNT(Order ID)
Total Quantity =SUM(Quantity)
Average Discount =AVERAGE(Discount)
Profit Margin % =DIVIDE([Total Profit], [Total Sales], 0)
Average Order Value =DIVIDE([Total Sales], [Total Orders], 0)
Total Customers =DISTINCTCOUNT(Customer ID)
Average Profit =AVERAGE(Profit)
Minimum Sales =MIN(Sales)
Discount Profit =CALCULATE(SUM(Profit), Discount > 0)

3. Data Visualization
Used Power BI visualizations to analyze sales, profit, quantity, customer, product, category, and regional performance.

4. Dashboard Pages
Three interactive dashboards were developed in Power BI to analyze different aspects of Superstore sales performance.

 1. Sales Analysis Dashboard

This dashboard provides an overview of overall sales performance.
Key Performance Indicators Cards:
- Total Sales
- Total Profit
- Total Orders
- Total Customers

Visualizations:
- Category-wise Sales Analysis
- State-wise Profit Analysis
- Region-wise Sales Analysis
- Monthly Sales Trend
- Segment-wise Sales Analysis

Slicers:
- City
- Year
- Month

2. Sales & Profit Performance Dashboard
This dashboard focuses on analyzing sales and profitability across different dimensions.
Key Performance Indicators:
- Average Profit
- Total Customers
- Profit Margin %

Visualizations:
- Category and Sub-Category-wise Profit Analysis
- Year-wise Sales and Profit Analysis
- Segment-wise Profit Distribution
- State-wise Sales Performance using Map

Slicers:
- Country
- State
- Year
- Month

3. Discount & Profit Analysis Dashboard.
This dashboard analyzes the impact of discounts on sales, quantity, and profitability.

Key Performance Indicators in Cards:
- Average Discount
- Discount Profit
- Total Quantity Sold
- Minimum Sales

Visualizations:
- Category-wise Sales, Quantity and Average Discount
- Sub-Category-wise Average Discount
- Product-wise Quantity Sold
- Shipping Mode-wise Sales and Profit Performance

Slicers:
- Country
- Year
- Category
- Product Name
Interactive filters and slicers were used to explore the data across different categories and dimensions.
Findings

The analysis of the Superstore sales dataset revealed the following findings:
1. Sales and Profit Insights
- Total sales reached approximately $2 million.
- Total profit was approximately $286K.
- The business generated around 5K distinct orders.
- The dashboard provides an overview of sales and profit performance across different regions, categories, and customer segments.
2. Product and Category Insights
- Sales and quantity vary across the three major product categories: Furniture, Office Supplies, and Technology.
- Product-wise quantity analysis helps identify differences in product demand.
- Sub-category-wise discount analysis provides insights into discount distribution.
3. Discount and Profit Insights
- The average discount was approximately 15.62%.
- The total quantity sold was approximately 38K.
- The net profit from transactions with discounts greater than zero was approximately -$34.59K.
- This highlights the importance of monitoring discount strategies and their relationship with profitability.
 4. Shipping and Regional Insights
- Sales and profit performance vary across different shipping modes.
- State-wise and region-wise visualizations help compare geographical business performance.
- Interactive slicers allow users to explore performance across different locations and time periods.

Conclusion

The Superstore Sales Analysis project demonstrates how data cleaning, transformation, DAX calculations, and interactive Power BI dashboards can be used to analyze business performance.The project provides insights into sales trends, profitability, product demand, regional performance, and discount-related profit.
The analysis can support better decision-making, especially in sales monitoring, product performance evaluation, and discount management.

Tools Used :
- Microsoft Excel
- Power Query
- Microsoft Power BI Desktop


### 5. Final Data Preparation

After cleaning and transformation, the prepared dataset was used for further analysis and dashboard development in Microsoft Power BI.
