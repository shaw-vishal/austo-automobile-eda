# Austo Automobile — Consumer Behaviour Analysis

An exploratory data analysis project on 1,581 automobile customers of Austo Motors, uncovering what drives car purchase decisions across SUV, Sedan, and Hatchback segments.

---

## Problem Statement

Austo Motors' current marketing campaign was underperforming. The management needed a data-driven analysis of their customer base to understand **who is buying which car, why, and what financial factors influence the decision** — so they could fix their targeting and improve campaign ROI.

---

## Dataset

- **Records:** 1,581 customers
- **Features:** 14 variables
- **Variables include:** Age, Gender, Profession, Marital Status, Education, No. of Dependents, Salary, Partner Salary, Total Salary, House Loan, Personal Loan, Partner Working, Price, Car Make (SUV / Sedan / Hatchback)

---

## Approach

- Data cleaning — fixed gender misspellings ("Femal", "Femle"), handled 106 missing partner salary values with logical imputation (90 non-working partners → 0, 16 working with missing → 0, <1% of data)
- Univariate analysis on all 14 variables
- Bivariate analysis — Price vs Salary, Price vs Age, Make vs Gender, Make vs Profession, Make vs Loans, Gender vs Total Salary
- Salary segmentation (Low / Mid / High / Very High) cross-tabbed against car type and gender
- Correlation heatmap across all numerical features

---

## Key Findings

| Finding | Detail |
|---------|--------|
| **Women spend 45% more per car** | Avg female spend: $47,705 vs male: $32,817 |
| **Women strongly prefer SUVs** | 68% of low-salary women buy SUVs vs 32% of men |
| **SUV buyers are 92% house-loan-free** | Disposable income is the real driver |
| **Sedan is the universal car** | Consistent 23–26% share across ALL salary segments |
| **Age strongly predicts price** | Correlation = 0.80 — strongest in the dataset |
| **Price peaks at age 46–54** | Clear lifestyle upgrade pattern with career progression |
| **Dual income households buy premium** | Working partner → mid to high price range |
| **1 dependent = highest spender** | Newly married, fewer financial commitments |

---

## Business Recommendations

1. Target SUV marketing specifically at female buyers — they spend more and prefer SUVs across all income levels
2. Focus volume strategy on $20K–$35K mid-range — that's where the majority buys regardless of income
3. Use age as an ad targeting signal — entry models for 22–30, family sedans for 31–40, premium for 40+
4. Treat Sedan as a backbone product — never deprioritize it, it sells to everyone
5. Identify "no house loan" customers as premium leads — they have the highest disposable income

---

## Tech Stack

`Python` · `Pandas` · `NumPy` · `Matplotlib` · `Seaborn` · `Jupyter Notebook`

---

## Results Summary

The analysis revealed that **gender, age, house loan status, and household income** are the strongest predictors of car type and price. Genre-based targeting (e.g. "SUVs are for men") is factually wrong for this customer base — women are the stronger SUV segment.

---

## Author

**Vishal Shaw** · Data Scientist  
[Portfolio](https://shaw-vishal.github.io) · [LinkedIn](https://linkedin.com/in/your-linkedin) · [Email](mailto:vishshaw6@gmail.com)
