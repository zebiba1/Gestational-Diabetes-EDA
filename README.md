# Gestational Diabetes Exploratory Data Analysis (EDA)

## Overview
This project explores the [Pima Indians Diabetes Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database) to identify patterns and predictors of gestational diabetes.  
The goal was to clean the data, perform exploratory data analysis, and build a basic logistic regression model.

---

## Dataset
- **Source:** UCI Machine Learning Repository / Kaggle
- **Observations:** 768
- **Features:** 8 numeric predictors + Outcome variable

---

## Data Cleaning
- Replaced biologically invalid zeros in:
  - Glucose
  - BloodPressure
  - SkinThickness
  - Insulin
  - BMI
- Visualized missing data using `missingno`
- Imputed missing values with median values to maintain distribution integrity

---

## Exploratory Data Analysis
- **Distributions:** Histograms showed right-skewed glucose and BMI distributions
- **Outcome Comparison:** Boxplots indicated higher median glucose and BMI in diabetic patients
- **Correlation Analysis:** Glucose strongly correlated with diabetes outcome (r ≈ 0.49)

---

## Predictive Modeling
A logistic regression model was trained to predict diabetes status:
- **F1 Score:** ~0.71
- **Precision:** ~0.72
- **Recall:** ~0.70

---

## Key Insights
- Higher glucose and BMI are strongly associated with diabetes
- Age and insulin levels show moderate correlations
- Logistic regression effectively classifies diabetic outcomes with reasonable accuracy

---

## How to Run
1. Install requirements (`pandas`, `numpy`, `matplotlib`, `seaborn`, `sklearn`, `missingno`)
2. Open the Jupyter Notebook
3. Run cells sequentially

---

## Visual Examples
- Histograms and boxplots for feature distributions
- Correlation heatmap
- Model performance metrics

---

## Tags
`Python` `Pandas` `EDA` `Logistic Regression` `Healthcare Analytics`

---


## Key Insights

- Glucose and BMI distributions show that diabetic patients tend to have higher values.
- Correlation heatmap confirms glucose as a strong predictor (r ≈ 0.49).
- Logistic regression model achieved an F1-score of 0.71, showing decent predictive power.
- Higher BMI and Age are also associated with increased diabetes risk.

## Author
Zebiba Ousman
https://www.linkedin.com/in/zebiba-ousman/
