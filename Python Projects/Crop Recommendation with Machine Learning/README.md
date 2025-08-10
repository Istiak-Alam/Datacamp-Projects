# Crop Recommendation with Machine Learning

## Project Overview

This project predicts the optimal crop to sow on a given field, using a machine learning model trained on basic soil chemistry measurements—Nitrogen (N), Phosphorous (P), Potassium (K), and pH. By analyzing these soil metrics, we help farmers make data-driven planting decisions that maximize yield and efficiency.

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

**Features:**
- `N`: Nitrogen content (soil)
- `P`: Phosphorous content (soil)
- `K`: Potassium content (soil)
- `ph`: Soil pH value
- `crop`: Optimal crop label (target; categorical)

**Source:**  
`soil_measures.csv` (included in this repository)

---

## Key Insights

- The model achieves high crop prediction accuracy with only four soil features.
- Nitrogen, pH, and other soil elements each contribute—feature importance makes it clear which are most influential.
- Visual analytics reveal which crops are most frequently optimal, and identify potential class imbalance.

---

## Visualizations

### Soil Feature Distributions

![Distribution of Soil Features](Distribution%20of%20Soil%20Features.png)
*Displays the distribution of Nitrogen, Phosphorous, Potassium, and pH across all sampled fields.*

---

### Crop Recommendation Frequency

![Crop Frequency](Crop%20Frequency.png)
*Shows how often each crop was recommended as optimal in the dataset. Useful for understanding class balance.*

---

### Feature Importance in Crop Prediction

![Feature Importance](Feature%20Importance.png)
*Bar plot displaying the relative importance of each soil property in predicting crop suitability, as determined by the trained machine learning model.*

---

## How to Run

1. Clone or download this repository.
2. Ensure `soil_measures.csv` is present in the project directory.
3. Open and execute `notebook.ipynb` in Jupyter.
4. All results—including model accuracy and these visualizations—are reproducible within the notebook.

---

## Links

- [Full Report (PDF)](https://github.com/Istiak-Alam/Datacamp-Projects/blob/main/Python%20Projects/Crop%20Recommendation%20with%20Machine%20Learning/Crop%20Selection%20with%20Machine%20Learning%20%E2%80%93%20Project%20Rep.pdf)
- [Source Notebook](https://github.com/Istiak-Alam/Datacamp-Projects/blob/main/Python%20Projects/Crop%20Recommendation%20with%20Machine%20Learning/notebook.ipynb)
- [My Datacamp Project](https://www.datacamp.com/datalab/w/a6979821-4f32-48eb-ac58-2d4a0d9e969f/edit)

---

## License

This project is licensed under the MIT License.

---

## Acknowledgements

Data and project template based on the DataCamp Machine Learning soil crop project. Analysis and code by [ISTIAK ALAM].

---


