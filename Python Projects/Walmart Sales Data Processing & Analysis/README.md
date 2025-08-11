# Walmart Sales Data Processing & Analysis

**Author:** ISTIAK ALAM  
**Affiliation:** DataCamp Real World Project  

---

## 📌 Project Overview

This project focuses on preparing, cleaning, and analyzing Walmart weekly grocery sales data, integrating economic indicators and holiday effects. Through merging, transformation, and aggregation steps, the project provides actionable datasets and managerial insights about sales patterns—essential for inventory planning, business intelligence, and forecasting.

---

## 📄 Project Files and Links

- **Technical Report:** [`Walmart Sales Data Processing & Analysis.pdf`](Walmart%20Sales%20Data%20Processing%20%26%20Analysis.pdf)
- **Project Notebook:** [`notebook.ipynb`](notebook.ipynb)
- **DataCamp Project Link:** [Open in DataCamp](https://www.datacamp.com/datalab/w/800f9534-efc2-4199-ad11-2de33c171824/edit)
- **DataCamp Portfolio:** [istiak-data-analyst Portfolio](https://www.datacamp.com/portfolio/istiak-data-analyst)

---

## 📊 Key Dataset Features

- **Store_ID** — Identifier for each Walmart store  
- **Date** — Week of sale  
- **Dept** — Department number  
- **Weekly_Sales** — Actual sales for each store-department-week  
- **IsHoliday** — Indicator whether the week contains a major public holiday  
- **CPI** — Consumer Price Index  
- **Unemployment** — Regional unemployment percentage  

---

## 🛠 Methodology

- Data extracted from a PostgreSQL database and Parquet file
- Merged on `Store_ID`, `Date`, and `Dept` to combine sales and external data
- Cleaned, filtered, and selected key columns
- Transformed weekly data to add a `Month` column, enabling trend analysis
- Aggregated to create monthly summaries
- Saved final cleaned (`clean_data.csv`) and aggregated (`agg_data.csv`) datasets

---

## 📷 Visualization

### Histogram of Weekly Sales

![](Histogram%20of%20Weekly%20Sales.png)

This histogram shows the distribution of weekly sales—useful for identifying normal patterns, outliers, and the sales range across Walmart stores and departments.

---

## 📈 Results Overview

- Clean, merged datasets ready for deeper BI, analysis, or modeling.
- Sales spikes clearly linked to holiday periods.
- Monthly sales metrics provide high-level trend visibility for managers.

---

## 🚀 Next Steps

- Apply forecasting models to predict high-volume weeks and optimize logistics.
- Analyze department/store-type trends for tailored strategies.
- Study promotion and external factor (e.g., CPI, unemployment) impacts more closely.

---

## 📂 Repository Structure

├── Walmart Sales Data Processing & Analysis.pdf
├── notebook.ipynb
├── Histogram of Weekly Sales.png
├── clean_data.csv
├── agg_data.csv
├── README.md
└── data/ # Raw datasets if included


---

## 📝 Conclusion

This project demonstrates the end-to-end pipeline for retail data cleaning, enrichment, and exploratory analysis.  
By using clean datasets and clear visualizations, it enables data-driven decisions for Walmart’s sales operations and provides a foundation for future analytics or predictive modeling work.
