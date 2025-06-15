# Sales-data-analysis-and-visualization-using-powerbi

📈 Sales Data Analysis & Visualization Dashboard

 Project Overview
 
This project is a Sales Performance Dashboard built in Power BI to provide real-time insights into sales performance, gross margins, regional contributions, and pricing trends across different product categories and months. The primary goal was to enable sales managers, regional directors, and C-suite stakeholders to monitor KPIs, identify margin gaps, and improve product and pricing strategies.
Designed with a clean, intuitive layout and filterable drill-downs, the dashboard empowers users to ask better questions, discover root causes, and take action faster.

🛠️ Tools and Technologies Used

•	Power BI Desktop – Dashboard development, DAX calculations, and visualization
•	DAX (Data Analysis Expressions) – To calculate KPIs like Gross Margin %, Net Sales, Discounts, and Trends
•	Excel / CSV – Used as the sales data source
•	Hierarchical Filters & Bookmarks – For drill-through and seamless region/category exploration

❓ Key Business Questions Addressed

1.	What are the monthly and quarterly gross sales, discounts, and net sales?
2.	How is the Gross Margin % trending over time by product, sub-category, and region?
3.	Which regions and categories are driving the highest and lowest sales performance?
4.	Are unit price and unit cost aligned with expected margins over time?
5.	Where are the opportunities to optimize pricing or cut discounts?

🔄 Methodology

1. Data Preparation
2. 
•	Loaded raw sales data containing metrics like gross sales, discounts, units sold, and cost per unit.

•	Performed basic cleaning to handle missing regions or invalid numeric values.

4. KPI Modeling (DAX)

Calculated key metrics such as:

•	Gross Sales = SUM(Sales[Gross_Sales])

•	Discount % = SUM(Sales[Discount_Amount]) / SUM(Sales[Gross_Sales])

•	Net Sales = Gross Sales - Discounts

•	Gross Margin % = (Net Sales - Cost) / Net Sales

5. Interactive Dashboard Pages

🔹 Sales KPIs Overview

•	Monthly slicers and regional filters

•	KPI tiles for Gross Sales, Net Sales, Discounts, and Gross Margin %

•	Line charts for monthly trend of Gross Margin %

•	Bar charts comparing Net Sales by Category and Gross Margin % by Sub-Category

🔹 City-Level Gross Margin Drill-down

•	Visualized gross margin by city (e.g., Maceió, Recife, Natal) to highlight high- and low-margin regions

•	Identified key gaps like São Luís having only ~31.77% gross margin, much lower than others

🔹 Product Size Profitability

•	Focused analysis on product size-level performance

•	Compared gross margin % across formats (e.g., 120 Tablets, Capsules, Small/XL sizes)

•	Flagged underperforming sizes like “30 Serving” (~37.72%) for possible pricing or bundling changes

💡 Key Insights & Business Impact

•	🔍 Gross Margin % ranged from 31% to over 60%, depending on product and region—indicating significant room for pricing optimization.

•	💸 Regions like Southeast contributed the most to sales ($294.91K) but showed margin variability—implying pricing inconsistencies.

•	🧾 Protein categories dominated Net Sales, but Carbs categories offered higher margin stability.

•	📊 Average Unit Price rose steadily from Feb to Sept, while costs remained flat—signaling a positive pricing trend.

•	🚨 Identified discount-heavy periods (e.g., Feb/March) that led to reduced Gross Margin % despite high sales.

These insights give sales leaders and analysts an early-warning system and data-backed strategies for pricing, promotions, and regional sales allocation.

The dashboard supports drill-downs, tooltips, and dynamic filtering to help both analysts and executives navigate effortlessly.

🧠 What This Project Demonstrates

•	My ability to design business-friendly, visually intuitive dashboards.

•	Strong grasp of sales KPIs, pricing dynamics, and gross margin concepts.

•	Hands-on expertise in Power BI modeling and DAX.

•	Storytelling with data, enabling cross-functional teams to understand performance at a glance.

•	Business impact thinking: every visual is connected to a decision or insight.

