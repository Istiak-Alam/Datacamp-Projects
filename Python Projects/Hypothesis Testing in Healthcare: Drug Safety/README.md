# Hypothesis Testing in Healthcare: Drug Safety

## Project Overview

This project analyzes data from a randomized controlled trial (RCT) conducted by GlobalXYZ to evaluate the safety of a new pharmaceutical drug compared to placebo. The investigation focuses on whether the drug increases the risk or severity of adverse effects, and explores demographic and clinical predictors of safety outcomes. This notebook presents hypothesis testing and evidence-based visualizations, enabling transparent and reproducible drug safety review.

---

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset Overview](#dataset-overview)
- [Key Insights](#key-insights)
- [Visualization](#visualization)
- [How to Run](#how-to-run)
- [Project Report](#project-report)
- [Links](#links)
- [License](#license)
- [Acknowledgements](#acknowledgements)

---

## Dataset Overview

**Source:**  
Modified from the [Hbiostat drug safety dataset](https://hbiostat.org/data/)  
Provided file: `drug_safety.csv`

| Column           | Description                                            |
|------------------|--------------------------------------------------------|
| sex              | Gender of participant (male/female)                    |
| age              | Age of participant                                     |
| week             | Week of testing                                        |
| trx              | Treatment group (Drug/Placebo)                         |
| wbc              | White blood cell count                                 |
| rbc              | Red blood cell count                                   |
| adverse_effects  | Presence of at least one adverse effect (yes/no)       |
| num_effects      | Total adverse effects experienced by the individual     |

---

## Key Insights

- **Adverse effects are significantly more common and severe in the drug group** compared to placebo.
- **Statistical testing (z-test, Mann-Whitney U)** confirms increased risk and event counts for the drug.
- **Visualizations** highlight group differences and demographic patterns.
- **Stakeholder Recommendation:** Regulatory labeling and patient risk communications should advise carefully about elevated adverse event risk, especially for older or female patients.

---

## Visualization

### Drug vs Placebo: Proportion with ≥1 Adverse Effect

![Drug vs Placebo](Drug%20vs%20Placebo.png)
*Visual comparison of the proportion of trial participants with at least one adverse effect in each treatment arm.*

---

## How to Run

1. Clone or download this repository.
2. Ensure `drug_safety.csv` is in the directory.
3. Open and execute `notebook.ipynb` in Jupyter.
4. Review the statistical outputs and generated plots for detailed results and supporting evidence.

---

## Project Report

- [Full PDF Report](Hypothesis%20Testing%20in%20Healthcare_%20Drug%20Safety.pdf)

---

## Links

- [DataCamp Project Notebook](https://www.datacamp.com/datalab/w/410845a4-fda8-4c9d-a57a-9992a3b260a9/edit)
- [Dataset Source](https://hbiostat.org/data/)

---

## License

This project is released under the MIT License.

---

## Acknowledgements

- Dataset adapted from Vanderbilt University Department of Biostatistics ([Hbiostat](https://hbiostat.org/data/))
- Analysis and reporting by [Your Name]

---
