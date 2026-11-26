 # Online Food Delivery Analysis: Data-Driven Business Insights
An end-to-end data analytics and business intelligence project analyzing **100,000+ online food delivery orders** to uncover revenue drivers, delivery bottlenecks, customer rating trends, and order cancellation patte

# Project Overview
This project covers the complete analytics lifecycle—from raw data cleaning and feature engineering in Python, to relational storage and SQL querying in MySQL, and finally an interactive executive dashboard in Power BI.

# Tech Stack
* **Data Cleaning & EDA:** Python (`Pandas`, `NumPy`, `Matplotlib`, `Seaborn`)
* **Database & SQL Analytics:** MySQL, `SQLAlchemy`, `PyMySQL`
* **Business Intelligence:** Power BI Desktop (DAX, Interactive Slicers, KPI Cards)


# Workflow & Methodology

# 1. Data Cleaning & Feature Engineering (Python)
* Processed 100,000 records, standardized categorical strings, and resolved invalid ratings and profit margins.
* Capped extreme numerical outliers using the **IQR (Interquartile Range)** method.
* Engineered analytical features including `Order_Day_Type` (Weekday vs. Weekend), `Peak_Hour`, `Net_Profit`, and `Delivery_Performance`.

# 2. Database Integration & SQL Analytics (MySQL)
* Loaded the cleaned dataset into a local MySQL database (`food_delivery_db.food_delivery_orders`) via SQLAlchemy and PyMySQL.
* Executed **15 business-focused SQL queries** across customer behavior, revenue and profit drivers, delivery SLA performance, restaurant ratings, and cancellation reasons.

# 3. Executive Dashboard (Power BI)
* Built **7 core DAX measures** to track business health at a glance:
  * **Total Orders** & **Total Revenue**
  * **Avg Order Value (AOV)** & **Profit Margin %**
  * **Avg Delivery Time** & **Avg Delivery Rating**
  * **Cancellation Rate %**
* Designed an interactive 3-zone layout featuring dynamic slicers (`City`, `Cuisine Type`, `Order Day Type`, `Peak Hour`) and cross-filtering visuals.

# Key Business Insights
*Peak Demand & Order Patterns:** Identified high-volume ordering windows across weekdays vs. weekends and peak meal hours to guide delivery fleet allocation.
*Delivery Time vs. Ratings:** Longer delivery times during peak hours strongly correlate with lower customer ratings and higher cancellation rates.
*City & Cuisine Profitability:** Highlighted top-performing cities and high-margin cuisines driving overall net profit.

