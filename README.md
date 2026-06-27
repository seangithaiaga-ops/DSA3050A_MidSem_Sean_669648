# DSA3050A_MidSem_Sean_669648

## Student Information
- **Name:** Sean Nderitu Githaiga
- **Student ID:** 669648
- **Course:** DSA 3050A — Business Intelligence and Data Visualizations

## Dataset Information
- **Dataset:** DataCo Smart Supply Chain Dataset
- **Source:** https://www.kaggle.com/datasets/shashwatwork/dataco-smart-supply-chain-for-big-data-analysis
- **Original Rows:** 180,519
- **Rows after cleaning:** 180,000
- **Columns:** 57 (after transformations)

## Business Problem
DataCo Global is experiencing challenges in monitoring overall supply chain performance across its global markets. Management lacks a centralized view of sales revenue, profit margins, delivery performance, and customer demand patterns across product categories and regions. As the BI Analyst, the task is to clean and transform the raw dataset and build an interactive dashboard to support data-driven decision-making.

## Power Query Transformations Performed

### Section A — Basic Data Cleaning
- Renamed unclear columns
- Changed data types for date, decimal, and whole number columns
- Removed duplicate records based on Order Id
- Removed blank rows
- Trimmed and cleaned text columns
- Replaced inconsistent values in Delivery Status column
- Removed unnecessary columns

### Section B — Intermediate Transformations
- Merged Customer First Name and Last Name into Full Name
- Split Full Name back into First and Last Name columns
- Split Shipping Date into date components
- Extracted Shipping Year, Month, Quarter and Day
- Created Shipping Date Formatted custom column
- Created Revenue Per Unit custom column
- Created Profit Category conditional column
- Extracted Order Year and Order Month from Order Date
- Filtered rows using two conditions
- Sorted data by Order Date ascending
- Added Transaction ID index column

### Section C — Advanced Transformations
- Group By with multiple aggregations — Sales Summary query
- Reference Query — Regional Sales Summary
- Created a Date Table in Power Query
- Created Delivery Performance business categories using nested conditional logic
- Used Column Profiling to identify data quality issues

## Visuals Created
- 4 KPI Cards — Total Sales, Total Profit, Total Orders, Avg Discount Rate
- Bar Chart — Sales by Category
- Column Chart — Orders by Market
- Line Chart — Sales Trend Over Time
- Pie Chart — Sales by Customer Segment
- Table — Order Details
- Matrix — Profit by Category and Market
- Map — Sales by Country
- Donut Chart — Orders by Shipping Mode
- Line and stacked column chart — Order Date, Order Month by Sales

## Business Insights
1. A significant proportion of orders are flagged as late deliveries, particularly in Fashion and Sports categories, suggesting logistical inefficiencies impacting customer satisfaction.
2. Europe and Latin America generate the highest sales volumes, but high sales do not always translate to high profit, indicating discount rates may be too aggressive in these markets.
3. The Consumer segment accounts for the largest share of orders, but the Corporate segment generates higher profit margins per order, suggesting that targeting corporate clients more aggressively could improve overall profitability.

---
