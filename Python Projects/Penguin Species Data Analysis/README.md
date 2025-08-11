# Penguin Species Data Analysis

**Author:** ISTIAK ALAM  
**Affiliation:** DataCamp Real World Project  

---

## 📌 Project Overview

This project analyzes penguin biometric measurements to explore patterns in features such as **culmen length**, **culmen depth**, **flipper length**, and **body mass**, along with gender data.  
By performing **data cleaning**, **feature engineering**, **normalization**, and **visualization**, the dataset is prepared for further analytical tasks such as species or gender classification.

---

## 📊 Dataset Description

The dataset contains the following numerical and categorical features:

- **culmen_length_mm** – Beak length in millimeters  
- **culmen_depth_mm** – Beak depth in millimeters  
- **flipper_length_mm** – Flipper length in millimeters  
- **body_mass_g** – Body mass in grams  
- **sex_FEMALE, sex_MALE** – One‑hot encoded gender columns  

---

## 🛠 Methodology

1. **Data Cleaning**
   - Checked for and handled any missing values.
   - Verified measurement ranges for accuracy.

2. **Feature Engineering**
   - One‑hot encoded gender into binary columns (`sex_FEMALE`, `sex_MALE`).

3. **Normalization**
   - Standardized all numeric features (z-score normalization).

4. **Exploratory Data Analysis (EDA)**
   - Created meaningful plots to reveal underlying patterns in the data.

---

## 📷 Visualizations

### 1. Histograms for Each Feature
![](Histograms%20for%20Each%20Feature.png)

### 2. Pairplot Colored by Gender
![](Pairplot%20Colored%20by%20Gender.png)

### 3. Correlation Heatmap
![](Correlation%20Heatmap.png)

---

## 📄 Project Files and Links

- **Project Notebook:** [`notebook.ipynb`](notebook.ipynb)
- **Technical Report (PDF):** [`Penguin Species Data Analysis.pdf`](Penguin%20Species%20Data%20Analysis.pdf)
- **DataCamp Project Link:** [View on DataCamp](https://www.datacamp.com/datalab/w/93a3029c-3fbf-4ef4-8482-d312be8d8faa/edit)
- **DataCamp Portfolio:** [istiak-data-analyst Portfolio](https://www.datacamp.com/portfolio/istiak-data-analyst)

---
## 📈 Results Summary

- **Distinct Patterns:** Biometric feature distributions reveal variability among subsets of penguins.
- **Gender Differences:** Certain measurements (e.g., body mass, flipper length) show variation between male and female penguins.
- **Feature Relationships:** Correlation analysis shows moderate to strong relationships between certain measurements.

---

## 🚀 Next Steps

- Apply machine learning models for **species classification** or **gender prediction**.
- Investigate environmental or location-based influences on measurements.
- Enhance visual exploration with **PCA** or **clustering** methods.

---

## 📂 Repository Structure

├── notebook.ipynb # Jupyter Notebook with analysis
├── Histograms for Each Feature.png
├── Pairplot Colored by Gender.png
├── Correlation Heatmap.png
├── README.md # Project documentation
└── data/ # Dataset 

---

## 📝 Conclusion

This project demonstrates how structured EDA and preprocessing can prepare biological datasets for predictive analysis.  
The visualizations clearly highlight feature distributions, gender-based differences, and inter-feature relationships, laying the foundation for further modeling work.

-[View Report]()