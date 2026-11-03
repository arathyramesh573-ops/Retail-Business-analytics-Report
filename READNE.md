🛒 Retail Business Analytics Report (Power BI)
==============================================

📌 Project Overview
-------------------
A Power BI report that analyzes global retail sales, profit, and customer data across 3 interactive pages: Sales, Profit, and Demographics.

🛠️ Tools and Technologies
-------------------------
- Power BI Desktop
- DAX
- Excel
- Git and GitHub

📂 Project Files
----------------
- power_bi_project.pbix – Power BI report file
- global_retail_sales_data.xlsx – Dataset
- RETAIL_ANALYSIS_PROJECT.pdf – Report page screenshots
- README.md – Project documentation

🗃️ Dataset
----------
- Global retail orders from 2011 to 2014
- 51,290 order rows, 25,035 orders, 1,590 customers, and 3,797 products
- Fields include category, segment, region, country, sales, quantity, discount, profit, and order priority

🧩 Data Model
-------------
A star schema with one fact table (sales_table) linked to customer_table, product_table, location_table, and Date_table.
Measures are stored in calculated_table, and parameter tables control Top N and dynamic charts.

📑 Report Pages
---------------
Sales
- Total sales, last year sales, YoY growth, and average sales per order
- Top 5 products by year and monthly sales comparison
- Sales by category, segment, and top 10 countries

Profit
- Total profit, last year profit, YoY growth, and average profit per order
- Monthly profit comparison
- Profit by category, segment, and top 5 products

Demographics
- Total customers, orders, and products, and average sales per state
- Sales and profit by region and top 8 states
- Profit by order priority, top 10 active buyers, and top 10 valuable customers

✨ Features
-----------
- Year, date, and country slicers
- Page navigation buttons
- Year-over-year comparison
- Show and hide slicer panel using bookmarks
- Top N control for states
- Drill-through and tooltip pages

🔍 Power BI Concepts Used
-------------------------
- Star schema data modeling
- Date table and time intelligence with SAMEPERIODLASTYEAR
- DAX measures and user-defined functions
- Parameters, bookmarks, drill-through, and tooltips
- KPI cards, line, bar, column, donut, ribbon, treemap, and shape map visuals

🎯 Project Objectives
---------------------
- Analyze sales and profit over time
- Compare performance with the previous year
- Identify top products, segments, and countries
- Understand customer and regional performance
- Build a portfolio project for GitHub

📊 Analysis
-----------
- Total sales and profit compared with last year
- Top selling and most profitable products
- Sales by segment and country
- Monthly sales and profit trends
- Most valuable states and customers

💡 Key Insights
---------------
- Total sales of $12.64M and total profit of $1.47M (2011 to 2014)
- Technology was the top category by sales
- The Consumer segment contributed about 51% of sales
- The United States was the top country by sales

🚀 How to Run the Project
-------------------------
1. Install Power BI Desktop.
2. Clone this repository.
3. Open power_bi_project.pbix.
4. If prompted, update the data source path to global_retail_sales_data.xlsx.

📁 Project Structure
--------------------
Retail-Business-Analytics-Report/
│
├── power_bi_project.pbix
├── global_retail_sales_data.xlsx
├── RETAIL_ANALYSIS_PROJECT.pdf
└── README.md


👩‍💻 Author
-----------
Arathy Ramesh

Aspiring Data Analyst

⭐ Conclusion
-------------
This project helped me strengthen my skills in Power BI, DAX, and dashboard design. 
It is part of my learning journey toward becoming a Data Analyst.
