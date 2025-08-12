# Fraud Detection Model Monitoring

## Overview

This repository analyzes and monitors feature drift in Poundbank’s fraud detection model, using both historical and production transaction data. The project demonstrates best practices for maintaining robust machine learning systems under changing business conditions. Feature drift is detected and ranked, actionable steps are recommended, and results are documented to guide real-world anti-fraud strategy.

## Project Links

- **Full Datacamp Project:** [View on DataCamp](https://www.datacamp.com/datalab/w/d5b3b4b1-54f2-4639-a525-4826f75a28c7/edit)
- **Portfolio:** [istiak-data-analyst on DataCamp](https://www.datacamp.com/portfolio/istiak-data-analyst)

## Project Files

| File                        | Description                                              |
|-----------------------------|----------------------------------------------------------|
| `notebook.ipynb`            | Main analysis notebook performing drift detection         |
| `Fraud Detection Model.pdf` | Professional & technical report of project findings      |
| `DataLab plot.png`          | Visualization — feature drift or transaction analysis    |
| `DataLab plot (1).png`      | Visualization — additional drift or performance charts   |

## Data

- `reference.csv`: Historic labeled transactions (“gold standard” set)
- `analysis.csv`: Recent production transactions monitored for drift

**Key Features Used:**
- `timestamp`, `time_since_login_min`, `transaction_amount`, `transaction_type`
- `is_first_transaction`, `user_tenure_months`, `is_fraud`, `predicted_fraud_proba`, `predicted_fraud`

## Getting Started

### Requirements

- Python 3.8+
- Key packages: `pandas`, `numpy`, `matplotlib`, `nannyml`, `scikit-learn`, `jupyter`

To install dependencies:

pip install pandas numpy matplotlib nannyml scikit-learn jupyter

text

### Running the Analysis

Open and run all cells in the main notebook:

jupyter notebook notebook.ipynb

text

All outputs and plots will be generated in the notebook or as PNG files.

## Results & Visualizations

- Significant drift detected in all key customer behavior features between historic and production data.
- Greatest drift found in:
  - **`time_since_login_min`** (change in login/payment behavior)
  - **`transaction_amount`** (variation in scam/legitimate payment sizes)
- Visual summaries included:
  - ![Feature Drift Plot](DataLab%20plot.png)
  - ![Additional Drift Visualization](DataLab%20plot%20(1).png)

## Key Report

A comprehensive technical and business report is included:

- [`Fraud Detection Model.pdf`](Fraud%20Detection%20Model.pdf): Contains executive summary, methodology, drift ranking, business/technical impact analysis, and detailed recommendations.

## Project Structure

/notebooks/ # Analysis notebook(s)
notebook.ipynb
/data/ # Input datasets (not distributed here for privacy)
/outputs/ # Visualizations and PDF report
DataLab plot.png
DataLab plot (1).png
Fraud Detection Model.pdf
README.md # This file

text

## Business & Technical Value

- **Business Impact:** Enables rapid response to emerging fraud threats, protecting bank assets and customer trust.
- **Technical Impact:** Shows how unsupervised model monitoring can preserve accuracy and reduce ongoing risk as data evolves.

## Further Information

Please refer to the full PDF report or execute the notebook for detailed findings and decision support.

## License

MIT

## Author & Contact

- [Istiak (Data Analyst)](https://www.datacamp.com/portfolio/istiak-data-analyst)