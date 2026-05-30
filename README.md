# Customer Churn Analysis
> Identifying behavioral and contractual patterns that predict customer churn — and translating them into actionable business recommendations.

---

## Business Context

In subscription-based businesses, retaining existing customers is significantly more cost-effective than acquiring new ones. This project analyzes a telecom customer dataset to understand **who churns, why, and what the business can do about it**.

The analysis identified **$139,130/month in revenue at risk** due to churn — equivalent to **$1.67M annualized**.

---

## Key Findings

| Variable | Finding |
|---|---|
| Overall churn rate | 26.5% — 1,869 out of 7,043 customers |
| Revenue at risk | $139,130/month ($1.67M annualized) |
| Contract type | Month-to-month customers churn at **42%** vs 3% for two-year contracts |
| Tenure | 50% of churners leave within the **first 10 months** (early churn pattern) |
| Monthly charges | Churners have a higher median charge ($79) vs retained customers ($64) |

---

## Recommendations

1. **Migrate month-to-month customers to annual contracts** — offering 10–15% discount incentives could significantly reduce the 42% churn rate in this segment
2. **Invest in early retention programs (0–10 months)** — loyalty programs and proactive support during the onboarding window are critical
3. **Review pricing for higher-cost tiers** — customers paying more may not perceive enough value; a service quality review is recommended

---

## Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=flat)
![Seaborn](https://img.shields.io/badge/Seaborn-4c72b0?style=flat)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)

---

## Project Structure

```
customer-churn-analysis/
│
├── customer-churn-analysis.ipynb   # Main analysis notebook
└── README.md                       # Project documentation
```

---

## How to Run

1. Clone the repository
```bash
git clone https://github.com/carolineborgees/customer-churn-analysis.git
cd customer-churn-analysis
```

2. Install dependencies
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

3. Download the dataset from [Kaggle — Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn) and place `WA_Fn-UseC_-Telco-Customer-Churn.csv` in the project root

4. Run the notebook
```bash
jupyter notebook customer-churn-analysis.ipynb
```

---

## Dataset

**IBM Telco Customer Churn** — available on [Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

- 7,043 customers
- 21 features
- Target variable: `Churn` (Yes / No)

---

## About

Analysis developed as part of a data analytics portfolio focused on business impact and actionable insights.  
Further analysis by customer profile and services is in progress.

**Author:** Caroline Borges  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/caroline-costa-borges/)
