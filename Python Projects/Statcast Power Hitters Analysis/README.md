# Statcast Power Hitters Analysis — Aaron Judge vs. Giancarlo Stanton

## 📌 Overview

This project analyzes **Major League Baseball Statcast data** to compare two of the game’s premier power hitters — **Aaron Judge** and **Giancarlo Stanton** — during the 2015–2017 seasons.  
Granular pitch-by-pitch data uncovers insights into home run production, pitch zone performance, and pitcher velocity profiles. The notebook demonstrates proficiency in data wrangling, exploratory analysis, and visualization for sports analytics.

---

## 🔗 Project Links

- **Full DataCamp Project:** [View on DataCamp](http://datacamp.com/datalab/w/52b0f13f-f745-4d91-a421-25ce12246a8f/edit)
- **Portfolio:** [istiak-data-analyst on DataCamp](https://www.datacamp.com/portfolio/istiak-data-analyst)

---

## 📂 Project Files

| File Name                              | Description                                                                 |
|----------------------------------------|-----------------------------------------------------------------------------|
| `notebook.ipynb`                       | Main Jupyter notebook with data analysis and Statcast visualizations        |
| `Statcast Power Hitters Analysis.pdf`  | In-depth professional/technical project report with findings and methods    |
| `Plot 2D Strike Zone Histograms.png`   | Visualization of home run frequency by strike zone for each player          |
| `Compare Pitch Velocity.png`           | Plot comparing pitch velocity faced by Judge and Stanton                    |

---

## 📊 Dataset

- **judge.csv** — All pitches thrown to Aaron Judge (2015–2017)
- **stanton.csv** — All pitches thrown to Giancarlo Stanton (2015–2017)

**Key variables include:**
- `pitch_type`, `zone`, `events` (e.g., home_run)
- `release_speed`, `launch_angle`, `launch_speed`
- `game_date`, `game_year`, and descriptive/statistical columns

---

## ⚙️ Requirements

- Python 3.8+
- Install dependencies:
pip install pandas matplotlib seaborn


---

## ▶️ How to Run

1. Clone the repository and navigate to the folder:

2. Start the Jupyter Notebook:
jupyter notebook notebook.ipynb


3. Run all cells to generate the full analysis and visual outputs.

---

## 📈 Key Visualizations

### 1. 2D Strike Zone Home Run Histograms
![Strike Zone Home Run Histogram](Plot%202D%20Strike%20Zone%20Histograms.png)

### 2. Pitch Velocity Comparison
![Pitch Velocity Comparison](Compare%20Pitch%20Velocity.png)

---

## 📌 Key Insights

- **Both Judge and Stanton create home run “hot zones” in the strike zone, but each has unique strengths and weaknesses.**
- Stanton faced a consistently higher average pitch velocity — yet both hitters maintained elite power production.
- Visualization and custom mapping functions enable precise “zone” analysis for modern scouting.

---

## 💼 Business & Technical Value

**Business Impact:**
- Enables targeted pitching strategies and refined scouting reports for elite hitters.
- Supports data-driven decisions in player evaluation and coaching.

**Technical Highlights:**
- Demonstrates the ability to handle and visualize granular multi-dimensional sports data.
- Employs custom strike zone mapping and high-impact statistical graphics using Python.

---

## 📜 License

MIT

---

## 👤 Author

**Istiak — Data Analyst**  
[My DataCamp Portfolio](https://www.datacamp.com/portfolio/istiak-data-analyst)