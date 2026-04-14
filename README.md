# 🚢 Titanic Survival Analysis

Exploratory data analysis on the Titanic dataset to understand what factors influenced passenger survival rates using logistic regression and data visualization.

## 🎯 Objective
Identify patterns in survival based on passenger class, gender, age, and fare using data analysis and visualization to understand which demographics had the highest survival chances.

## 🛠️ Tools Used
- Python, pandas, numpy
- seaborn, matplotlib
- statsmodels (Logit regression)

## 📊 Key Findings
- Female passengers had dramatically higher survival rates compared to males, with gender being one of the strongest predictors of survival (~14x odds increase for females).
- First-class passengers survived at significantly higher rates than third-class passengers (~9.6x odds increase for first-class), showing clear class-based disparities.
- Younger passengers showed better survival chances, with each year increase in age slightly decreasing the likelihood of survival (~1.02x odds increase for younger ages).

## 📁 Files
- `Titanic-survival.ipynb` — Full EDA and logistic regression analysis
- `train_data.csv` — Titanic dataset

## ▶️ How to Run
```bash
pip install pandas numpy seaborn matplotlib statsmodels
jupyter notebook Titanic-survival.ipynb
