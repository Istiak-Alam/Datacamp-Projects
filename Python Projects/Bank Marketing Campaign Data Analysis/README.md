# Bank Marketing Campaign Analysis

## Project Overview

This project analyzes direct marketing campaigns conducted by a Portuguese bank, aiming to determine which client attributes and campaign features most influence term deposit subscription rates. The analysis uses a historical dataset of client interactions and campaign outcomes to uncover actionable insights for marketing optimization and customer targeting.

---

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset Overview](#dataset-overview)
- [Key Insights](#key-insights)
- [Visualizations](#visualizations)
- [How to Run](#how-to-run)
- [Links](#links)
- [License](#license)
- [Acknowledgements](#acknowledgements)

---

## Dataset Overview

**Features included:**
- `age`: Client's age
- `marital`: Marital status (e.g., married)
- `education`: Education level (e.g., basic.4y, high_school)
- `credit_default`: Whether client is in credit default
- `mortgage`: Presence of a mortgage
- `number_contacts`: Contacts during campaign
- `contact_duration`: Duration (seconds) of last contact
- `previous_campaign_contacts`: Past campaign contacts
- `previous_outcome`: Outcome of past campaigns
- `campaign_outcome`: Target variable (yes/no)
- `month`, `day`, `year`: Last contact timing
- `cons_price_idx`: Consumer price index
- `euribor_three_months`: 3-month Euribor rate

**Data source:**  
[UCI Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing)

---

## Key Insights

- **Client age**, education, and marital status show distinct response patterns to marketing.
- Success rates are higher for clients previously contacted with positive outcomes.
- Longer contact duration and more frequent contact increase the chance of subscription.
- Economic indicators, such as lower Euribor rates, influence campaign effectiveness.

---

## Visualizations

### Client Age Distribution

![Client Age Distribution](Client%20Age%20Distribution.png)
*Distribution of client ages targeted during the bank’s marketing campaign.*

<!-- Add additional visualizations by copying similar blocks and updating filenames/captions -->

---

## How to Run

1. **Clone or download** this repository.
2. Open `notebook.ipynb` in Jupyter or your preferred notebook environment.
3. Run all cells to see the complete analysis, data cleaning, and visualizations.
4. Examine generated plots and summary tables for actionable insights.

---

## Links

- [Project File](https://github.com/Istiak-Alam/Datacamp-Projects/blob/main/Python%20Projects/Bank%20Marketing%20Campaign%20Data%20Analysis/notebook.ipynb)
- [Full Report (PDF)](https://github.com/Istiak-Alam/Datacamp-Projects/blob/main/Python%20Projects/Bank%20Marketing%20Campaign%20Data%20Analysis/Bank%20Marketing%20Campaign%20Data%20Analysis.pdf)

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## Acknowledgements

Dataset from UCI Machine Learning Repository; analysis and code by [Your Name].

---



