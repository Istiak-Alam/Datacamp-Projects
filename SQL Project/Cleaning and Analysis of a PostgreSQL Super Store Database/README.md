# 🛒 Cleaning and Analysis of a PostgreSQL Super Store Database

![Super Store Data Analysis](Project_Image.jpeg) <!-- Replace with your own project screenshot or results visual -->

[![DataCamp Project](https://img.shields.io/badge/DataCamp-Project-blue?logo=datacamp&logoColor=white)](https://www.datacamp.com/datalab/w/535c833b-13e4-450d-a857-fef2d6b1ca47/edit)
[![PDF Report](https://img.shields.io/badge/Report-PDF-orange?logo=adobeacrobatreader&logoColor=white)](Cleaning%20and%20Analysis%20of%20a%20PostgreSQL%20Super%20Store%20Database.pdf)
[![Portfolio](https://img.shields.io/badge/Portfolio-istiak--data--analyst-brightgreen)](https://www.datacamp.com/portfolio/istiak-data-analyst)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-istiak--data--analyst-blue?logo=linkedin)](https://www.linkedin.com/in/istiak-data-analyst/)

This repository contains my **DataCamp portfolio project** focusing on **data cleaning and business analysis** for a simulated PostgreSQL Super Store database.  
The project tackles **data type corrections, multi-table joins, and advanced SQL analytics** to uncover **top-performing products by sales and profit** inside each category.

---

## 📄 Project Report

- **Full summary, methodology, and business insights:**  
  [Cleaning and Analysis of a PostgreSQL Super Store Database.pdf](Cleaning%20and%20Analysis%20of%20a%20PostgreSQL%20Super%20Store%20Database.pdf)

---

## 💻 Code & Live Analysis

- **Jupyter Notebook:**  
  [notebook.ipynb](notebook.ipynb)  
  > *Click here for a GitHub preview or download to run locally in Jupyter.*

- **Live & interactive project on DataCamp:**  
  [View on DataCamp](https://www.datacamp.com/datalab/w/535c833b-13e4-450d-a857-fef2d6b1ca47/edit)

---

## 📊 Project Overview

### **Goals**
- Clean raw PostgreSQL Super Store tables (text-based dates, incorrect numeric types)
- Join related tables for orders, products, returns, and salespeople
- Identify **top 5 products by sales** in each main category, while also reviewing total profits
- Present results in business-ready ranked tables

### **Key Skills Demonstrated**
- SQL data type conversion (`CAST`, `::numeric`, `::date`)
- Multi-table joins (INNER JOIN across orders, products, returns, people)
- Common Table Expressions (CTEs) for modular queries
- Window functions (`RANK()` with `PARTITION BY`) for category-wise rankings

---

## 🗂 Dataset Overview

**Tables:**  
- `orders` – Transactional data (sales, profit, discount, etc.)  
- `returned_orders` – Records of returned items  
- `people` – Salesperson details by region  
- `products` – Product catalog with categories/sub-categories

---

## 📈 Results Snapshot

| Category         | Product Name                                   | Total Sales | Total Profit | Rank |
|------------------|------------------------------------------------|-------------|--------------|------|
| Furniture        | Hon Executive Leather Armchair, Adjustable     | 58,193.48   | 5,997.25     | 1    |
| Office Supplies  | Eldon File Cart, Single Width                  | 39,873.23   | 5,571.26     | 1    |
| Technology       | Apple Smart Phone, Full Size                   | 86,935.78   | 5,921.58     | 1    |

📌 **Key Insight:**  
Top sellers are not always the most profitable—profitability analysis is essential alongside sales volume tracking.

---

## 📥 How to Use

1. **Read the PDF** for executive summary, process, and insights.
2. **Review `notebook.ipynb`** for full SQL queries and data cleaning steps.
3. **Open DataCamp link** for an instantly runnable version in your browser.

---

## 📚 My DataCamp Portfolio

See more of my SQL, data cleaning, and business analytics projects:  
🔗 [https://www.datacamp.com/portfolio/istiak-data-analyst](https://www.datacamp.com/portfolio/istiak-data-analyst)

---

## 📧 Contact

Questions, collaboration, or feedback?  
📩 Reach out via [DataCamp](https://www.datacamp.com/portfolio/istiak-data-analyst) or connect on [LinkedIn](https://www.linkedin.com/in/istiak-data-analyst/)

---

*Thank you for reviewing my Super Store Data Cleaning & Analysis project!*  
