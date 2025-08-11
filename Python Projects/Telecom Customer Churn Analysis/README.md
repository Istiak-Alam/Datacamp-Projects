# Telecom Customer Churn Analysis

**Author:** ISTIAK ALAM  
**Affiliation:** DataCamp Real World Project  

---

## 📌 Project Overview

This project analyzes customer churn across major Indian telecom providers by combining demographic attributes and usage behavior to identify high‑risk segments and actionable retention strategies. The workflow includes data cleaning, feature engineering, exploratory analysis, and visualization, all packaged in a clear, reproducible notebook and report suitable for recruiters and stakeholders.

---

## 📄 Project Files and Links

- **Project Notebook:** [`notebook.ipynb`](notebook.ipynb)
- **Technical Report:** [`Telecom Customer Churn Analysis.pdf`](Telecom%20Customer%20Churn%20Analysis.pdf)
- **Key Visualization:** ![Churn Rate](Churn%20Rate.png)
- **DataCamp Project:** [Open in DataCamp](https://www.datacamp.com/datalab/w/b2603667-23df-461a-9613-71968c33b4ec/edit)
- **DataCamp Portfolio:** [istiak-data-analyst Portfolio](https://www.datacamp.com/portfolio/istiak-data-analyst)

---

## 🛠 Methodology

- **Data Preparation:**  
  - Loaded demographics and usage datasets and merged on `customer_id`.  
  - Validated schema, handled missing values, and standardized numeric types.

- **Feature Engineering:**  
  - Selected core predictors (e.g., age, estimated salary, calls_made, sms_sent, data_used, telecom_partner).  
  - Created helpful groupings (e.g., age bands) to support business insights.

- **Exploratory Analysis & Visualization:**  
  - Quantified churn rate by partner, usage patterns, and demographic segments.  
  - Produced visual summaries, including churn rates by telecom partner.

- **Model-Ready Output (optional in notebook):**  
  - Clean, structured DataFrame suitable for baseline modeling and further experimentation.

---

## 📊 Key Insight (Example)

- The chart ![Churn Rate](Churn%20Rate.png) highlights which providers experience higher churn, directing where targeted retention efforts may yield the greatest impact.

---

## 🚀 How to Run

1. Open `notebook.ipynb` in Jupyter or DataCamp Workspace.  
2. Run all cells to reproduce the data preparation and visualizations.  
3. Review the PDF report for executive-ready insights.

---

## 📈 Recommended Extensions

- Add feature importance from a baseline model (e.g., Logistic Regression or Random Forest).  
- Create churn heatmaps by geography (state/city) and usage intensity.  
- Implement SHAP/LIME for interpretable, stakeholder-friendly explanations.

---

## 📂 Repository Structure

├── Telecom Customer Churn Analysis.pdf
├── notebook.ipynb
├── Churn Rate (%) by Telecom Partner.png
├── README.md
└── data/ # (optional) input CSVs if included

text

---

## 📝 Notes


- All analyses and visuals are derived from the project’s provided datasets and code.  



