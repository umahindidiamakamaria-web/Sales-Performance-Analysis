# Sales-Performance-Analysis
# Project Overview

The Sales Performance Dashboard is an interactive business intelligence project developed using Microsoft Power BI to analyze sales performance across regions, product categories, individual products, payment methods, and salespeople.

The dashboard provides a consolidated view of key performance indicators (KPIs), monthly revenue trends, product demand, and salesperson revenue contribution. Interactive slicers allow users to explore the data and examine sales performance from different perspectives.

The goal of this project is to transform sales data into meaningful business insights that support data-driven decision-making, identify growth opportunities, and highlight areas requiring further investigation.

# Project Objectives
	•	Monitor overall sales performance using key performance indicators.
	•	Compare revenue across different regions.
	•	Identify high-demand product categories.
	•	Analyze the top ten products by revenue.
	•	Examine monthly revenue trends and fluctuations.
	•	Evaluate revenue contribution by payment method.
	•	Compare salesperson performance based on revenue generated.
	•	Provide actionable recommendations to support business decisions.

# Tools and Technologies
	•	Microsoft Power BI: Dashboard development and data visualization.
	•	Power Query: Data cleaning and transformation.
	•	DAX Measures: Total Revenue = SUMX(Sales, Sales[Quantity] * Sales[UnitPrice]),
   Total Orders = DISTINCTCOUNT(Sales[OrderID]),
   Total Quantity Sold = SUM(Sales[Quantity]),
   Average Unit Price = AVERAGE(Sales[UnitPrice]),
   Avg Revenue per Order = DIVIDE([Total Revenue], [Total Orders])
	•	Interactive Slicers: Filtering by city, region, and payment type.

# Key Performance Indicators (KPIs)
The dashboard tracks five key metrics:
KPI | Purpose
Total Revenue | Measures total revenue generated from sales.
Total Orders| Measures the number of orders recorded.
Average Unit Price| Shows the average unit selling price.
Total Quantity Sold| Measures the total number of units sold.
Average Revenue per Order| Measures the average revenue generated per order.

# Key Insights

1. Overall Sales Performance:
The business generated approximately $438,636 in revenue from 369 orders, with an average revenue per order of approximately $1,190.

Insight: These metrics provide an overview of revenue generation, order activity, and average order value.

2. Regional Revenue Performance:
The North region generated approximately $144K, followed by the East at $108K, the South at $95K, and the West at $91K.

Insight: The North was the highest-revenue region, while the West recorded the lowest revenue among the four regions.

3. Product Category Performance:
Beverages led the product categories, with approximately 5.2K units sold. Dried Fruit & Nuts and Baked Goods & Mixes followed, with approximately 2.0K units each.

Insight: Beverages was the leading category by sales volume, making it an important category to monitor when planning inventory and evaluating customer demand.

5. Top Products by Revenue:
Coffee generated approximately $75K, followed by Curry Sauce at $73K and Mozzarella at $33K.

Insight: Coffee and Curry Sauce were the highest-revenue products in the displayed analysis.

5. Monthly Revenue Trend:
Monthly revenue fluctuated throughout the period, reaching approximately $67K in December, the highest value displayed.

Insight: The trend highlights changes in revenue over time and provides an opportunity to investigate seasonal patterns and periods of stronger or weaker sales.

6. Revenue by Payment Type:
Credit cards accounted for approximately 59.31% of revenue, checks contributed 30.01%, and cash accounted for 10.67%.

Insight: Credit cards represented the largest share of revenue among the payment methods displayed.

7. Revenue by Salesperson:
Nancy Freehafer generated approximately $105K in revenue, followed by Anne Larsen at $95K and Andrew Cencini at $67K.

Insight: Nancy Freehafer was the leading salesperson by revenue in the displayed results.

# Business Recommendations
Based on the dashboard findings, the following actions are recommended:
•	Regional growth: Investigate the factors driving the North’s strong revenue and identify opportunities to improve performance in the West.
•	Inventory planning: Monitor demand for Beverages and other high-volume categories to help maintain appropriate stock levels.
•	Product strategy: Review the revenue and profitability of Coffee, Curry Sauce, and other leading products.
•	Sales trend analysis: Investigate the factors behind monthly revenue fluctuations and prepare for periods of increased demand.
•	Payment optimization: Maintain reliable credit card processing while monitoring transaction costs across payment methods.
•	Salesperson evaluation: Compare revenue, order volume, and average revenue per order to gain a more complete understanding of individual sales performance.


# Dashboard Features
	•	Five KPI cards for monitoring overall sales performance.
	•	Six visualizations covering product categories, regions, top products, monthly trends, payment types, and salesperson revenue.
	•	Interactive slicers for City, Region, and Payment Type.
	•	A consistent navy-blue, teal, and white design.
	•	Visual summaries that help users identify sales patterns and performance differences.

# Project Structure
A suggested repository structure is:
Sales-Performance-Dashboard/
│
├── README.md
├── Sales_Performance_Dashboard.pbix
└── images/
    └── sales-performance-dashboard.png

# Conclusion

The Sales Performance Dashboard demonstrates how Microsoft Power BI can transform sales data into meaningful business insights. By analyzing regional revenue, product category demand, top-performing products, monthly trends, payment preferences, and salesperson revenue, the dashboard provides a practical view of business performance and highlights opportunities for further investigation.

This project demonstrates practical skills in data visualization, KPI monitoring, business intelligence, and analytical thinking.
