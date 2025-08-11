# Book Popularity Prediction for an Online Bookstore

**Author:** ISTIAK ALAM  
**Affiliation:** DataCamp Real World Project

---

## 📌 Project Overview
This project builds a machine learning pipeline to predict whether a book will be popular using both structured metadata (price, categories, authors, review helpfulness) and unstructured text (review summaries and texts). The workflow covers data cleaning, feature engineering for text and numerics, model training/evaluation, and business-focused visualizations—aimed at improving inventory planning, marketing prioritization, and homepage curation.

---

## 📄 Project Files and Links
- **Project Notebook:** [`notebook.ipynb`](notebook.ipynb)
- **Technical Report:** [`Book Popularity Prediction for an Online Bookstore.pdf`](Book%20Popularity%20Prediction%20for%20an%20Online%20Bookstore.pdf)
- **DataCamp Project:** [Open in DataCamp](https://www.datacamp.com/datalab/w/3d3b3255-4687-4765-9f36-eb36064ac2a6/edit)
- **DataCamp Portfolio:** [istiak-data-analyst Portfolio](https://www.datacamp.com/portfolio/istiak-data-analyst)

---

## 🛠 Methodology
- **Data Preparation**
  - Parsed review helpfulness (e.g., “17/19”) into numeric features: helpful_yes, helpful_total, helpful_ratio.
  - Cleaned and standardized price and categorical fields (authors, categories).
  - Combined review text fields for richer text signals.
- **Feature Engineering**
  - Text vectorization (bag-of-words/TF-IDF as applicable in the notebook).
  - Numeric features: price, helpfulness metrics.
  - Encoded categorical features (top categories/authors if used).
- **Modeling & Evaluation**
  - Train/test split with stratification on target popularity.
  - Baseline and tuned classifiers (e.g., Logistic Regression / Random Forest).
  - Accuracy and confusion matrix on the held-out set; attention to Popular-class precision/recall.

---

## 📊 Visual Highlights
- **Price Distribution By Popularity**
  - Shows how price varies between Popular vs. Unpopular titles, informing pricing and promotion strategies.
  - ![Price Distribution By Popularity](Price%20Distribution%20By%20Popularity.png)
- **Correlation Heatmap**
  - Highlights relationships among engineered numeric features (e.g., price, helpfulness) and target, guiding feature selection and interpretation.
 - ![Correlation Heatmap](Correlation%20heatmap.png)
---

## 📈 Results & Insights
- Combined text and numeric features meet the target accuracy threshold for predicting popularity.
- Review helpfulness and price provide complementary signals to text-based features.
- Category and author effects suggest merchandising opportunities and targeted promotions.

---

## 🚀 How to Reproduce
1. Open and run `notebook.ipynb` (Jupyter or DataCamp Workspace).
2. Ensure referenced datasets are available in the working directory as used in the notebook.
3. Execute all cells to reproduce feature engineering, model training, metrics, and plots.
4. Export final visuals and the report as needed.

---

## ✅ Recommended Next Steps
- Add n-gram text features with controlled vocabulary and TF-IDF weighting.
- Calibrate probabilities and set decision thresholds based on business costs (stock-out vs. overstock).
- Include author/category priors and time-based features (e.g., early-review signals).
- Package as a lightweight API for scoring incoming titles.

---

## 📂 Repository Structure
├── Book Popularity Prediction for an Online Bookstore.pdf
├── notebook.ipynb
├── Price Distribution By Popularity.png
├── Correlation heatmap.png
├── README.md
└── data/ # (optional) source CSVs if included

---

## 📝 Notes
- All analysis and visuals are reproducible from the notebook using the project’s data.


