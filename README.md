# 📊 Market-wise Sales and Revenue Dashboard
This project presents a dynamic sales analytics dashboard created using Power BI and SQL to analyze and visualize market-wise revenue, sales quantity, top customers, and top products across different timeframes. The dashboard enables data-driven decisions by showcasing trends and identifying opportunities for growth and optimization.

# 🎯 Objective
Analyze revenue and sales quantity by market

Identify top-performing products and customers

Understand sales trends over time

Use SQL for data extraction and Power BI for business insights

# 🧰 Tools Used
Power BI Desktop – for interactive dashboards

SQL Server / MySQL – for querying and transforming raw data

DAX (Data Analysis Expressions) – for creating KPIs and calculated measures

Excel/CSV – as the source data format

# 🛠️ Data Processing
Data Source & SQL Manipulation
Data was extracted using SQL queries with joins and filters

Example queries used to join market, customer, and product data

Cleaning & Transformation
Removed null values in market and product columns

Renamed columns for clarity (e.g., SalesAmount → Revenue)

Removed records with zero revenue or quantity

Formatted date fields and added calculated columns

Data Model
Flat table structure (single table with fields like market, customer, product, order date, revenue, and quantity)

No complex relationships needed

# 📊 Key Visuals and KPIs
Total Revenue: ₹984.81M

Total Sales Quantity: 2M units

Revenue by Market: Delhi NCR leads with ₹519.51M

Sales Quantity by Market: Delhi NCR leads with 988K units

Revenue Trend Over Time: Peaks in early 2018 and mid-2019

Top 5 Customers: Electricalsara Stores dominates with ₹413.33M

Top 5 Products: Includes a product with a missing name (data issue)

# 🔍 Key Insights
Delhi NCR contributes over 50% of total revenue and sales

Electricalsara Stores is the top customer—target for loyalty strategies

A major product entry is unnamed ("Blank")—suggests a data quality issue

Revenue peaks indicate seasonal trends or successful campaigns

# 💡 Recommendations
Fix Data Quality Issues: Address missing product names in source data

Focus Market Strategy: Prioritize high-performing regions like Delhi NCR

Customer Loyalty: Launch targeted offers for top customers

Sales Forecasting: Leverage historical data to predict high-demand periods

# ✅ Conclusion
The Power BI dashboard effectively visualizes revenue and sales data, helping stakeholders monitor trends, identify gaps, and make strategic decisions. SQL ensures clean, structured data, while Power BI offers dynamic, interactive reporting.

