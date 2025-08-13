# 🏭 Statistical Process Control for Manufacturing Parts

![Manufacturing SPC Illustration](manufacturing.jpg)

[![DataCamp Project](https://img.shields.io/badge/DataCamp-Project-blue?logo=datacamp&logoColor=white)](https://www.datacamp.com/datalab/w/78f4b57b-f9f4-4e40-8bc6-b6d04d5b89d7/edit)
[![PDF Report](https://img.shields.io/badge/Report-PDF-orange?logo=adobeacrobatreader&logoColor=white)](Statistical%20Process%20Control%20for%20Manufacturing%20Parts.pdf)
[![Portfolio](https://img.shields.io/badge/Portfolio-istiak--data--analyst-brightgreen)](https://www.datacamp.com/portfolio/istiak-data-analyst)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-istiak--data--analyst-blue?logo=linkedin)](https://www.linkedin.com/in/istiak-data-analyst/)

This repository presents my **DataCamp portfolio project** implementing Statistical Process Control (SPC) in a manufacturing environment using advanced SQL. The analysis automates quality monitoring for part measurements, detects out-of-control conditions, and flags process improvement opportunities.

---

## 📄 Project Report

- **Comprehensive Technical & Business Summary:**  
  [Statistical Process Control for Manufacturing Parts.pdf](Statistical%20Process%20Control%20for%20Manufacturing%20Parts.pdf)

---

## 💻 Code & Live Analysis

- **Interactive Jupyter Notebook:**  
  [notebook.ipynb](notebook.ipynb)  
  > *Open this file in GitHub for a quick code preview, or download/run in Jupyter for full interactivity.*

- **Try the project on DataCamp (live, no setup needed):**  
  [DataCamp Project Link](https://www.datacamp.com/datalab/w/78f4b57b-f9f4-4e40-8bc6-b6d04d5b89d7/edit)

---

## 📊 Project Overview

### **Goal**
- Monitor part measurements using SPC (UCL/LCL) directly in SQL.
- Provide real-time alerts for out-of-range items and operators.
- Drive actionable improvements for process quality and efficiency.

### **Key Skills Demonstrated**
- SQL window functions, rolling aggregation, conditional logic
- End-to-end SPC methodology in a database context
- Clear data storytelling for plant managers and data teams

---

## 🗂 Dataset & Logic

**Table:** `manufacturing_parts`  
- `item_no`, `length`, `width`, `height`, `operator`

**Core SQL:** Calculates rolling mean, stddev, UCL/LCL (window size n=5), and flags alerts:

---

## 📈 Results Highlight

| Operator | Row No. | Height | Avg Height | UCL   | LCL   | Alert |
|----------|---------|--------|------------|-------|-------|-------|
| Op-5     | 5       | 22.17  | 20.43      | 21.98 | 18.88 | ✅    |
| Op-14    | 34      | 19.99  | 20.86      | 21.68 | 20.03 | ✅    |
| Op-6     | 5       | 20.79  | 20.42      | 20.86 | 19.98 | ❌    |

📌 Items with "✅" alert are outside control, signaling need for operator/machine check.

---

## 📚 My DataCamp Portfolio

See more of my data projects and credentials:  
🔗 [https://www.datacamp.com/portfolio/istiak-data-analyst](https://www.datacamp.com/portfolio/istiak-data-analyst)

---

## 📧 Contact

Questions/feedback/collaboration:  
📩 Message me via [DataCamp](https://www.datacamp.com/portfolio/istiak-data-analyst) or [LinkedIn](https://www.linkedin.com/in/istiak-data-analyst/)

---

*Thank you for reviewing my SPC project! Insights and improvement suggestions are welcome.*
