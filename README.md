# Power-BI-Project
Eklavya Ecommerce Sales Dashboard - Power BI Project
====================================================

📌 Project Overview:
--------------------
The Eklavya Ecommerce Sales Dashboard is an interactive Power BI dashboard designed 
to analyze and visualize ecommerce sales data. It helps track performance, 
understand customer behavior, and identify top-selling products and regions.

🎯 Objectives:
--------------
- Monitor and track sales KPIs
- Identify high-performing products and regions
- Analyze customer purchase patterns
- Assist business decisions with data-driven insights

🔧 Tools Used:
--------------
- Power BI Desktop
- Microsoft Excel / CSV (Data Source)
- DAX (Data Analysis Expressions)
- Power Query (Data Cleaning & Transformation)

📊 Key Features:
----------------
- KPI Cards: Total Revenue, Orders, Profit, Average Order Value
- Time Series Charts: Monthly & Quarterly Sales
- Product Analysis: Top Categories and Products
- Regional Sales: Geo Map for regional insights
- Customer Insights: New vs Returning Customers
- Profit Margins: Product-wise and region-wise profitability

📁 Folder Structure:
--------------------
Eklavya-Ecommerce-Sales-Dashboard/
│
├── Data/
│   └── ecommerce_sales_data.csv
│
├── Dashboard/
│   └── Eklavya_Ecommerce_Dashboard.pbix
│
├── Images/
│   └── dashboard_preview.png
│
├── README.txt
└── LICENSE

📐 DAX Measures (Examples):
---------------------------
- Total Revenue:
  Total Revenue = SUM(Sales[Revenue])

- Average Order Value:
  AVERAGE = [Total Revenue] / [Total Orders]

- Profit Margin %:
  Profit Margin = DIVIDE([Total Profit], [Total Revenue], 0)

💡 Insights Gained:
-------------------
- Q4 had the highest revenue due to festive promotions.
- Electronics and Fashion are the top-performing categories.
- North America has the highest revenue; Asia has the best profit margin.
- Returning customers contribute over 35% of total sales.

📌 Future Improvements:
------------------------
- Add real-time data integration
- Forecasting using Azure Machine Learning
- Add customer satisfaction metrics
- Publish report on Power BI Service with auto-refresh

🙌 Created by: Eklavya Gupta
-----------------------------
Connect with me:
- LinkedIn: https://www.linkedin.com/in/eklavyagupta1112/
- Email: rocking.eklavya.11@gmail.com
