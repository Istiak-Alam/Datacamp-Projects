# Power BI Project: AdventureWorks Cohort & Performance Dashboard

## Company Overview

Adventure Works is a large, multinational manufacturing company specializing in bicycles, parts, and accessories across North America, Europe, and Asia. The company employs 500 staff and leverages regional sales teams and modern analytics to drive strategic decisions for global commercial markets.

---

## Live Dashboard
 
*(Portfolio demo access – contact istiak36@gmail.com if private.)*

📄 [Download Full Report: Cohort & Performance Dashboard.pdf](./Cohort%20&%20Performance%20Dashboard.pdf)

---

## Project Overview

This Power BI dashboard delivers actionable insights from AdventureWorks' Internet sales and customer data (AdventureWorksDW database), empowering sales and marketing users with rapid cohort, product, customer, and territory analysis. Designed for multi-dimensional slicing and in-depth trend analysis, it reveals revenue, profit, churn, and operational drivers for strategic growth.

---

## Features

- **Executive KPIs:** Instantly view revenue, profit, order count, return rate, and customer metrics.
- **Sales & Profit Trends:** Track monthly, quarterly, and annual business performance against targets.
- **Product Analytics:** Deep dive into category, SKU, and top product profitability/return trends.
- **Customer Segmentation:** Visualize cohorts, churn, retention, revenue per customer, and demographic insights.
- **Geographic Performance:** Map territory-wise orders and revenue across global regions.
- **AI-Driven KPIs:** Use "Key Influencers" to uncover order/profit drivers, high-yield segments, and retention risks.

---

## Dashboard Snapshots

![Executive Dashboard](./images/Executive%20Dashboard.PNG)  
*Top-level KPIs and performance overview.*

![Product Dashboard](./images/Product%20Dashboard.PNG)  
*Product-level analysis: category, return, and profit by SKU.*

![Customer Dashboard](./images/Customer%20Dashboard.PNG)  
*Customer churn, cohort, and LTV (lifetime value) segmentation.*

![Map Visual](./images/Map%20Visual.PNG)  
*Territory/region order and revenue coverage.*

![AI Visual](./images/AI%20Visual.PNG)  
*Key influencer visual powered by Power BI AI analytics to highlight business drivers.*

---

## Insights

- $24.91M in revenue, $10.46M profit, 25K orders, and a 2.17% return rate over the analysis period.
- Most sales come from accessories and bikes; Water Bottle 30oz is both the top-selling and most returned product.
- 77.97% churn rate marks a growth opportunity through engagement and loyalty programs.
- Customers under 63, with income $10K–$90K, and in professional roles are most likely to place high numbers of orders.
- US and UK are lead regions; expansion potential is highlighted in Asia/Australia.
- Monthly revenue/profit trends support target benchmarking and operational planning.

---

## How to Use

1. Open the dashboard to filter by cohort, region, product category, customer segment, and more.
2. Use charts, maps, and AI insight visuals featured above for presentations and business reviews.
3. Download the full PDF report for a detailed write-up and recommendations.

---

## About

**Author:** Istiak Alam  
**Portfolio:** [istiak-alam.github.io](https://istiak-alam.github.io)  
**LinkedIn:** [linkedin.com/in/istiak-data-analyst](https://www.linkedin.com/in/istiak-data-analyst/)  
**Email:** istiak36@gmail.com

---

*All images must be placed in the `/images` folder for correct rendering. Place "Cohort & Performance Dashboard.pdf" in your repo root for download functionality.*

---

## Technical Implementation

**Data Source:**  
- AdventureWorksDW Internet Sales and related dimension tables (CSV/SQL).

**Modeling:**  
- Tabular star schema in Power BI Desktop, optimized for fast ad-hoc analytics.

**ETL:**  
- Power Query for field standardization, joining, cleansing, KPI calculations, and date/territory harmonization.

**Performance Optimization:**  
- Import mode, reduced column set, query folding, calculated fields in DAX only as needed.

**DAX / Advanced Analytics:**  
- CALCULATE, SUMX, VAR, RANKX, cohort & churn calculations, and Power BI AI "Key Influencer" visual.

**KPIs:**  
- Revenue, Profit, Order/Return counts, Churn/Retention, Avg. Revenue per Customer, Lifetime Value, Region Share, Top/Bottom SKUs.

**Validation:**  
- Cross-checked against summary tables and spot-validated with underlying raw data.

**End Users:**  
- Executives, sales, marketing, analysts, and management.

**Collaboration:**  
- Published to Power BI Service for secure access; report and images used in leadership briefings and business case portfolios.

---

