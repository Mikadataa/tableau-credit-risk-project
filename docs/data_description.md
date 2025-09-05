# 📑 Data Description — Default of Credit Card Clients

**Dataset:** Default of Credit Card Clients in Taiwan (2005)  
**Source:** [Kaggle](https://www.kaggle.com/datasets/uciml/default-of-credit-card-clients-dataset)  

This dataset contains information on default payments, demographics, credit limits, bill statements, repayment history, and default outcome.

---

## 📋 Variables

| Column | Description | Example | Notes / Use in Project |
|--------|-------------|---------|-------------------------|
| ID | Client identifier | 0001 | Not used in analysis |
| LIMIT_BAL | Credit limit (NT$) | 50,000 | Used for segmentation of high vs low credit |
| SEX | Gender (1=male, 2=female) | 1 | Demographic analysis |
| EDUCATION | Education level (1=graduate, 2=university, 3=high school, 4=others, 5/6 unknown) | 2 | Used for segmentation |
| MARRIAGE | Marital status (1=married, 2=single, 3=others) | 2 | Segmentation |
| AGE | Age in years | 35 | Demographic analysis |
| PAY_0–PAY_6 | Repayment status in last 6 months (-1=paid duly, 1=1 month delay, …, 9=9+ months delay) | 2 | Key for defining delinquency stages |
| BILL_AMT1–BILL_AMT6 | Bill statement amount in last 6 months | 20,000 | Basis for exposure analysis |
| PAY_AMT1–PAY_AMT6 | Amount paid in last 6 months | 15,000 | Basis for recovery analysis |
| default.payment.next.month | Default flag (1=yes, 0=no) | 1 | Target variable / KPI |

---
