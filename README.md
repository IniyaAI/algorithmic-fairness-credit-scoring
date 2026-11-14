# Algorithmic Fairness in Credit Scoring
### An Analysis of Age-Based Disparities in Logistic Regression Error Rates

**Researcher:** Iniya Raghupathi  
**Affiliation:** Walnut Grove High School, Prosper, Texas  
**Research Type:** Independent Quantitative Research  
**Year:** 2026

---

## 1. Overview

This project investigates age-based disparities in machine learning credit scoring models, focusing on differences in prediction error rates between applicants under 30 and applicants aged 30 and above.

Using the UCI German Credit Dataset, this study examines whether excluding age as an explicit predictor eliminates demographic disparities or whether correlated financial variables may continue to encode age-related information.

## 2. Research Objectives

- Investigate differences in credit scoring prediction errors across age groups.
- Evaluate the impact of including versus excluding age as a model predictor.
- Examine the potential influence of proxy variables on algorithmic fairness.
- Assess the statistical significance of observed disparities.

## 3. Dataset

**Dataset:** UCI German Credit Dataset  
**Source:** UCI Machine Learning Repository  
**Sample Size:** 1,000 applicant records

The dataset contains demographic and financial characteristics alongside credit-risk classifications.

Dataset source: https://doi.org/10.24432/C5NC77

## 4. Methodology

Two logistic regression configurations were implemented and compared:

**Model 1: Baseline Model**
- Includes age as an explicit predictor.
- Uses financial and demographic variables to predict credit outcomes.

**Model 2: Age-Excluded Model**
- Removes age as an explicit predictor.
- Examines whether age-related disparities persist through correlated variables.

Both configurations were implemented using Python and NumPy in Google Colab.

## 5. Evaluation Metrics

Model performance and demographic disparities were examined using:

- Confusion matrices
- False Positive Rate (FPR)
- False Negative Rate (FNR)
- Classification accuracy
- Statistical significance testing

## 6. Key Findings

- Identified statistically significant differences in prediction error rates between age groups (p = 0.0031).
- Found that excluding age as an explicit predictor did not eliminate observed disparities.
- Investigated how correlated financial variables may function as proxies for demographic characteristics.

These findings highlight limitations of protected-attribute removal as a standalone approach to algorithmic bias mitigation.

## 7. Technologies

- Python
- NumPy
- Google Colab
- Logistic Regression
- Statistical Analysis

## 8. Repository Structure

```text
algorithmic-fairness-credit-scoring/
│
├── README.md
├── notebooks/
│   └── credit_scoring_analysis.ipynb
│
├── figures/
│   ├── confusion_matrix.png
│   └── error_rate_comparison.png
│
├── paper/
│   └── research_paper.pdf
│
└── LICENSE
```

## 9. Reproducibility

The accompanying Jupyter Notebook documents the computational implementation and analysis.

To reproduce the analysis:

1. Download the repository.
2. Open the notebook in Google Colab.
3. Load the UCI German Credit Dataset.
4. Execute the analysis cells in sequence.

## 10. Research Presentation

This research was presented at a school academic research symposium under the guidance of an AP Research faculty advisor.

## 11. Citation

Raghupathi, I. (2026). *Algorithmic Fairness in Credit Scoring: An Analysis of Age-Based Disparities in Logistic Regression Error Rates*. Zenodo. [DOI to be added after publication]

## 12. Acknowledgments

Research conducted independently under the guidance of Rachel Dunn, AP Research faculty advisor.

---

**Author:** Iniya Raghupathi  
**Year:** 2026
