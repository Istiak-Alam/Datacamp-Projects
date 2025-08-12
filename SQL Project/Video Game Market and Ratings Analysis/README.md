# 🎮 Video Game Market & Ratings Analysis

## 📌 Overview
This project analyzes **the top 400 video games** released since 1977, combining:
- **Global sales data**
- **Critic ratings** (Metacritic)
- **User ratings** (Metacritic)

The aim is to uncover:
- The **"Golden Age"** of video games — years that achieved the highest critical and audience ratings.
- The highest-selling games and most dominant publishers/platforms.
- The relationship between commercial success and critical acclaim.

The work demonstrates **advanced SQL querying skills** (joins, aggregations, set operations, filtering) and transforms raw data into insights valuable for both **business stakeholders** and **technical recruiters**.

---

## 🔗 Project Links
- **Full DataCamp Project:** [View on DataCamp](https://www.datacamp.com/datalab/w/012111ff-9d0a-4318-854d-7c375191c10c/edit)
- **Portfolio (Istiak – Data Analyst):** [My DataCamp Portfolio](https://www.datacamp.com/portfolio/istiak-data-analyst)

---

## 📂 Project Files
| File Name | Description |
|-----------|-------------|
| `notebook.ipynb` | Main analysis notebook with SQL queries, joins, aggregations, and visualizations |
| `Video Game Market and Ratings Analysis.pdf` | Full professional & technical report (objectives, methods, findings, recommendations) |

---

## 📊 Dataset & Tables
The project uses an SQL database (limited to 400 rows for scope) containing:

**`game_sales`**
| Column | Description |
|--------|-------------|
| name | Video game title |
| platform | Platform (Wii, PC, DS, etc.) |
| publisher | Publisher name |
| developer | Developer studio |
| games_sold | Copies sold (millions) |
| year | Year released |

**`reviews`**
| Column | Description |
|--------|-------------|
| name | Video game title |
| critic_score | Metacritic critic average |
| user_score | Metacritic user average |

**`users_avg_year_rating`** – average user score per release year  
**`critics_avg_year_rating`** – average critic score per release year

---

## ⚙️ How to Run
1. Open the notebook in Jupyter or DataCamp’s DataLab.
2. Connect to the SQL database with the video game tables.
3. Run queries in sequence to generate:
   - Top-selling games
   - Critic vs. user score trends
   - Golden Age year comparison
4. Review visual outputs inside the notebook.

---

## 📈 Key Insights

### **Top 3 Best-Selling Games**
1. *Wii Sports* (Wii) – 82.90M  
2. *Super Mario Bros.* (NES) – 40.24M  
3. *Counter-Strike: Global Offensive* (PC) – 40.00M  

**Nintendo dominates sales**, holding 7 out of the top 10 spots.

---

### **Golden Age of Gaming**
- **1998** — Outstanding consensus (Avg. Critic: 9.32 / Avg. User: 9.40)  
- **2004–2010** — High-scoring era for both critics & players.  
- **Critic vs. User Gaps:** Some years (e.g., 1997, 2010) show users rating far higher than critics.

---

## 💼 Business & Technical Value

**Business Impact:**
- Identifies historically strong release years and franchises for potential remakes or sequels.
- Reveals publisher/platform dominance patterns for strategic planning.

**Technical Impact:**
- SQL joins and aggregations to merge multi-table data.
- Year-on-year comparative analysis.
- Data storytelling for both technical and non-technical stakeholders.

---

## 📜 License
MIT

---

## 👤 Author
**Istiak — Data Analyst**  
- [My DataCamp Portfolio](https://www.datacamp.com/portfolio/istiak-data-analyst)