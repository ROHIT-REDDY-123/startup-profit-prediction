# 📈 Multiple Linear Regression - Startup Profit Prediction

This project applies **Multiple Linear Regression** to predict startup profit based on investment features using Python and scikit-learn.

## 📌 Objective

To build and evaluate a regression model that predicts profit based on R&D Spend, Administration, Marketing Spend, and Location.

## 📊 Dataset

- **Source:** 50_Startups.csv
- **Features:**
  - R&D Spend
  - Administration
  - Marketing Spend
  - State (Categorical)
- **Target:** Profit

## 🧠 Key Highlights

- Performed **EDA** with pandas, seaborn, and matplotlib
- Encoded categorical variables using **One-Hot Encoding**
- Built a **Multiple Linear Regression** model using `LinearRegression`
- Evaluated model using **R² Score** and **Mean Squared Error**
- Applied **Backward Elimination** with `statsmodels` to refine feature set

## 🔍 Findings

- **R&D Spend** was the most statistically significant factor affecting profit.
- Other features like Administration and Marketing had lesser impact.

