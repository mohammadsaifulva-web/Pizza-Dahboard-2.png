🍕 Domino's Pizza Sales Performance Dashboard

An interactive, end-to-end Power BI sales analytics dashboard built to evaluate sales performance, customer preferences, and key business drivers for a Domino's Pizza dataset.

📌 Project Overview

This project provides actionable business insights by transforming raw transactional data into high-level business intelligence visualizations. The dashboard helps store managers and executives identify peak sales hours, best-selling pizzas, revenue distribution by categories, and strategic operational trends.

📸 Dashboard Preview

📊 Key Features & Visual Insights

Executive KPI Header: Real-time visibility into Core Business Metrics:

Total Revenue: €162.72K

Total Orders: 6K

Total Pizzas Sold: 11K

Average Order Value (AOV): €25.66

Sales Distribution Analysis:

Revenue by Pizza Category (Donut Chart): Breaks down market share across Classic, Supreme, Chicken, and Veggie categories.

Top Performing Pizzas (Bar Chart): Ranks individual pizzas by revenue generated (e.g., The BBQ Chicken Pizza, The Thai Chicken Pizza).

Time-Based Trend Analysis:

Monthly Revenue Trends (Column Chart): Tracks monthly financial growth from January to July.

Hourly Order Distribution (Line Chart): Identifies rush hours during operational days.

Day of Week Revenue Impact (Area Chart): Measures revenue generation across weekdays to assist in shift management and inventory forecasting.

🛠️ Tech Stack & Skills Demonstrated

Business Intelligence Tool: Power BI Desktop

Data Processing: Power Query (ETL - Data Cleaning, Transformation, Column Creation)

Data Modeling: Star Schema / Relational Data Model

Calculations & DAX: Custom Measures for Key Performance Indicators

UI/UX Design: Custom branding palette (Domino's Navy #002D62, Crimson Red #E31837, White Background)

🧮 DAX Measures Used

Here are some of the primary DAX measures implemented in this project:

// Total Revenue
Total Revenue = SUM(dominos_pizza_sales[total_price])

// Total Orders
Total Orders = DISTINCTCOUNT(dominos_pizza_sales[order_id])

// Total Pizzas Sold
Total Pizza Sold = SUM(dominos_pizza_sales[quantity])

// Average Order Value
Average Order Value = [Total Revenue] / [Total Orders]


📁 Repository Structure

Pizza-Dashboard/
│
├── dominos_pizza_sales.csv         # Raw Sales Dataset
├── Domino_Pizza_Sales.pbix         # Power BI Master File
├── Pizza Dashboard 2.jpg           # Dashboard Screenshot
└── README.md                       # Documentation File


👤 Author

Saiful Islam

Data Analyst / Power BI Specialist
