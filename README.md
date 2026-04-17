# Interactive Sales Performance Dashboard | Tableau | KPI Analysis | Trend & Profitability Insights 
## Executive Summary:
This project presents an interactive Sales Performance Dashboard built in Tableau to analyze business performance across sales, profit, and quantity metrics. The dashboard enables multi-dimensional analysis across time, product categories, and geographic regions, with a focus on comparing current year (CY) vs previous year (PY) performance.
Advanced calculated fields and table calculations were used to generate KPIs, trend analysis, and performance indicators. The analysis reveals overall growth in sales, profit, and quantity, with sales showing the strongest increase, while profit growth indicates potential margin pressure.
The dashboard provides stakeholders with a clear, interactive view of business performance to support data-driven decision-making in sales strategy and operational planning.
## Business Problem:
A retail lacks clear visibility into year-over-year performance, product-level profitability, and regional sales trends. The objective of this analysis is to evaluate sales performance, identify underperforming products and regions, and generate data-driven insights to improve profitability and support strategic decision-making.
## Methodology:
**Dashboard Preparation:** Monetary fields(sales, profits and discount) were standardized using calculated fields and formulas to ensure accurate data types.

**Data Modelling:** Relationships were created between tables to allow for cross-dimensional analysis

**KPI Modelling:** Calculated fields were created for evaluating KPIs.

**Dashboard Design:** : Built an interactive Tableau dashboard with KPI cards, sparklines, bar charts, and line charts for executive reporting. 
## Key Calculations & Metrics:
## Dashboard:
## Skills:
* Data cleaning and transformation (data type standardization, currency formatting, string-to-numeric conversion)
* Data modeling using relationships (fact and dimension tables)
* Parameter-driven analysis for dynamic year selection (CY vs PY)
* Calculated fields using conditional logic (IF/THEN) and aggregations
* Table calculations (WINDOW_AVG, WINDOW_MAX, WINDOW_MIN)
* KPI calculations and performance metrics development (Sales, Profit, Quantity, % Change)
* Year-over-Year (YoY) analysis and trend analysis
* Interactive dashboard development (filters, parameters, drill-down)
* Data visualization (bar charts, line charts, KPI cards, sparklines)
* Business insights and performance analysis using Tableau
## Results & Recommendations:
Overall, the analysis revealed strong year-over-year (YoY) growth across all key metrics. Sales increased by 20.4%, while quantity sold rose by 26.8%, indicating a significant expansion in customer demand and transaction volume. However, profit grew at a lower rate of 14.24%, suggesting that increased sales did not translate proportionally into profitability.
The monthly trend analysis (via sparklines and line charts) showed consistent upward movement in sales and quantity throughout the current year, with some fluctuations that may indicate seasonal demand patterns. This highlights opportunities for better demand forecasting and inventory planning.
At the product level, the dashboard identified clear disparities in performance across subcategories. Some product segments consistently performed above average, contributing significantly to overall revenue, while others underperformed, dragging down profitability.
A key observation from the KPI comparison is the gap between sales growth and profit growth, which points to potential margin compression. This may be influenced by higher discounts, increased operational costs, or a shift toward lower-margin products.
**Recommendations**
Based on the insights generated from the dashboard, the following actions are recommended:
1. Improve Profit Margins:
   The disparity between sales growth and profit growth should be addressed. This can be achieved by:
*	Reviewing discount strategies to ensure they are not eroding margins 
*	Identifying high-cost products or operations and optimizing them 
*	Promoting higher-margin products more aggressively 
2. Optimize Product Portfolio
Focus on product subcategories that consistently perform above average and contribute the most to profit. At the same time:
*	Reassess underperforming products 
*	Consider discontinuing or repositioning low-performing items 
*	Bundle or promote weaker products strategically to improve sales 


## Next Steps:
Next Steps

To build on the insights generated from the Sales Performance Dashboard and further enhance decision-making, the following next steps are recommended:

**1. Conduct Deeper Profitability Analysis:**
While overall profit increased, its slower growth compared to sales suggests margin pressure. 
The next step is to:

1.Analyze profit at a more granular level (product, region, customer segment)
2.Investigate the impact of discounts on profitability
3.Identify high-revenue but low-profit products

2. Incorporate Cost Data for Margin Analysis
The current dashboard focuses on sales and profit, but adding detailed cost components would provide better visibility into:

Cost of goods sold (COGS)
Operational and logistics costs
True profit margins by product and region

This will enable more precise margin optimization strategies.

3. Enhance Customer-Level Insights
Introduce customer segmentation to better understand purchasing behavior:

Identify high-value and repeat customers
Analyze buying patterns across regions and product categories
Develop targeted retention and upselling strategies

4. Add Forecasting Capabilities


