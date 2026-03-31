# Bright-Coffee-Shop-Final

🌟 Bright Coffee Shop — Sales Analysis Case Study (2026)
A full end‑to‑end analytics project built using Miro, Databricks, Excel, and Canva.

📌 Project Overview
This project is a complete data analysis workflow designed to help Bright Coffee Shop understand its sales performance and identify actionable opportunities for revenue growth. The business recently appointed a new CEO who wants to improve product performance and scale revenue.
My role as a Junior Data Analyst was to explore transactional data, process it using Databricks, visualize insights in Excel, and communicate findings through a structured presentation.
Rather than simply running calculations, this project focuses on thinking like an analyst — planning the data flow, shaping messy data into useful information, and designing insights that support strategic decision‑making.

🧭 Project Workflow
This project was completed using a multi‑tool approach:
1. Planning & Architecture — Miro
I began by mapping out the entire data journey using a custom Miro diagram, highlighting:

Data source (Excel transaction file)
ETL workflow in Databricks
Storage and transformation steps
Output pathways into Excel and visualization tools
The final reporting and storytelling structure

The goal was to establish clarity early so that every subsequent step aligned with a business problem.

2. Data Engineering & Cleaning — Databricks
The raw Excel file was converted to CSV and loaded into Databricks for processing.
Key transformation steps included:

Fixing inconsistent numeric formats (e.g., converting "3,1" to 3.1)
Creating a transaction_time_bucket (30‑minute or 3‑hour intervals)
Calculating total_amount = unit_price × transaction_qty
Grouping sales by:

Product type
Product detail
Time interval
Quantity sold


Writing SQL queries to extract trends and summarize revenue metrics

This stage ensured that all analysis was built on clean, reliable, and well‑structured data.

3. Data Analysis — Excel
After exporting processed data from Databricks, I used Excel for:

Pivot tables exploring sales by product type, time of day, and total revenue
Charts highlighting:

Peak sales intervals
Best‑selling products
Performance gaps


Trend exploration using filters and slicers

Excel was chosen deliberately here because business stakeholders often prefer flexible, familiar tools for exploring insights.

4. Reporting & Visual Storytelling — Canva
The final insights were transformed into a clean, business‑ready slide deck using Canva.
The presentation included:

Key findings
Visual dashboards
Revenue highlights
Low‑performing product categories
Actionable recommendations
Strategic next steps for the CEO

The goal was to turn technical results into a clear business story.

🔑 Key Insights Delivered
Some of the major insights uncovered include:

Identification of the highest revenue‑generating products
Recognition of slow-performing product categories
Determination of peak sales time intervals, enabling operational adjustments
Analysis of quantity sold per product, highlighting inventory needs
Seasonal and time‑based sales trends

These insights were designed to directly support business decisions such as staffing, stock levels, marketing timing, and product promotions.
