# NCD Risk Factor Analysis — NHANES 2017-2018

![Python](https://img.shields.io/badge/Python-3.10-blue) ![scikit-learn](https://img.shields.io/badge/scikit--learn-logistic%20regression-orange) ![NHANES](https://img.shields.io/badge/Data-CDC%20NHANES-green) ![Health Equity](https://img.shields.io/badge/Focus-Health%20Equity-red)

**Logistic regression analysis of diabetes, hypertension, and obesity risk factors using NHANES 2017-2018 — with odds ratios, forest plot visualization, and racial health equity analysis.**

> Author: Afriyie Karikari Bempah, PharmD | [LinkedIn](https://linkedin.com/in/afriyiekarikaribempah) | [GitHub](https://github.com/akbempah1)

---

## Overview

This project analyzes NCD risk factors in a nationally representative US sample using four NHANES 2017-2018 modules. It builds a logistic regression model for diabetes prediction, calculates odds ratios with confidence intervals, and visualizes racial health disparities across three major NCDs.

---

## Key Findings

| Finding | Implication |
|---|---|
| **Age OR = 4.67** | Strongest predictor — dominant non-modifiable risk factor |
| **BMI OR = 1.79** | Primary modifiable target for diabetes prevention |
| **Balanced LR AUC = 0.822** | Strong performance with just 6 features |
| **Hypertension gap: 41% vs 30.7%** | Non-Hispanic Black patients bear disproportionate cardiovascular burden |
| **Obesity gap: 40.4% vs 13.8%** | Largest racial disparity — nearly 3x difference |
| **Diabetes uniform across races** | Racial disparities in diabetes less pronounced than in hypertension/obesity |

---

## Technical Approach

- **4-module NHANES merge** — Demographics, Blood Pressure, BMI, Diabetes
- **Logistic regression** — standard and class-weight-balanced versions
- **Odds ratios with 95% CI** — forest plot visualization
- **Health equity analysis** — prevalence by race/ethnicity across 3 NCDs
- **ROC comparison** — standard vs balanced model

## Skills Demonstrated

- Multi-file SAS data loading and merging
- Logistic regression with class imbalance handling
- Odds ratio calculation and interpretation
- Forest plot visualization
- Health equity framing of epidemiological findings

---

## African Market Relevance

NCD burden is rising rapidly in Sub-Saharan Africa. Ghana's NCD prevalence mirrors the trajectory of US minority populations 20 years ago. This analytical framework applies directly to community health screening and primary care NCD management in resource-limited settings — a core use case for Aduru Analytics.

---

## How to Run

```bash
git clone https://github.com/akbempah1/ncd-risk-factor-analysis.git
```

Download NHANES 2017-2018 files from CDC:
- [DEMO_J.XPT](https://wwwn.cdc.gov/Nchs/Nhanes/2017-2018/DEMO_J.XPT)
- [BPX_J.XPT](https://wwwn.cdc.gov/Nchs/Nhanes/2017-2018/BPX_J.XPT)
- [BMX_J.XPT](https://wwwn.cdc.gov/Nchs/Nhanes/2017-2018/BMX_J.XPT)
- [DIQ_J.XPT](https://wwwn.cdc.gov/Nchs/Nhanes/2017-2018/DIQ_J.XPT)

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
jupyter notebook ncd_risk_analysis.ipynb
```

---

## Portfolio Series

- [Project 1 — Medicare Drug Spending](https://github.com/akbempah1/medicare-drug-spending-analysis)
- [Project 2 — FDA Adverse Events](https://github.com/akbempah1/fda-adverse-events-analysis)
- [Project 3 — Hospital Readmissions](https://github.com/akbempah1/hospital-readmissions-prediction)
- [Project 4 — Pharma Portfolio](https://github.com/akbempah1/pharma-stock-portfolio-analysis)
- [Project 5 — Credit Risk Scoring](https://github.com/akbempah1/credit-risk-scoring)
- [Project 6 — Africa Disease Burden](https://github.com/akbempah1/africa-disease-burden-analysis)
- [Project 7 — Malaria Prediction](https://github.com/akbempah1/malaria-prediction-africa)
- [Project 8 — Pharmacy Sales Forecasting](https://github.com/akbempah1/pharmacy-sales-forecasting)
- **Project 9 — NCD Risk Factor Analysis** ← you are here
