
# PRDA-01: Startup Profit Analysis

## 📌 Project Overview

This project analyzes startup profitability using **MySQL, Microsoft Excel, and Power BI**. The objective is to identify the key factors affecting profit, compare profitability across different states, and predict profit using Multiple Linear Regression.

The analysis focuses on Research & Development (R&D) Spend, Administration, Marketing Spend, and State to generate actionable business insights.

## 🎯 Project Objectives

- Analyze startup profit across different states.
- Identify the relationship between business expenditures and profit.
- Perform Multiple Linear Regression using Excel.
- Predict profit using regression coefficients.
- Build an interactive Power BI dashboard to visualize key findings.
- Provide data-driven recommendations for business decision-making.

## 🛠️ Tools & Technologies

- **MySQL:** Data exploration, aggregation, and SQL analysis.
- **Microsoft Excel:** Data analysis, regression modeling, and profit prediction.
- **Power BI:** Interactive dashboard and data visualization.

## 📂 Dataset Description

The dataset contains 50 startup records with the following columns:

| Column | Description |
|---|---|
| `RD_Spend` | Expenditure on research and development |
| `Administration` | Administrative expenses |
| `Marketing_Spend` | Marketing expenditure |
| `State` | State in which the startup operates |
| `Profit` | Profit earned by the startup |

**States covered:** California, Florida, and New York.

## 🔍 Project Workflow

### 1. Data Analysis Using MySQL

- Explored the dataset and checked data completeness.
- Analyzed the number of startups in each state.
- Calculated average profit by state.
- Compared profitability across different locations.

### 2. Regression Analysis Using Excel

Applied Multiple Linear Regression to study the relationship between startup expenditures and profit.

**Regression Equation:**

```text
Predicted Profit =
50122.19299
+ (0.80571505 × RD_Spend)
- (0.026815968 × Administration)
+ (0.027228065 × Marketing_Spend)
```

**Model Performance:**

- **R-squared:** 95.07%
- **Significance F:** 4.52851E-30

The model explains approximately 95.07% of the variation in profit within the analyzed dataset. This indicates a strong overall fit, although it does not guarantee equally accurate predictions for new data.

### 3. Profit Prediction

Used the regression equation to estimate profit from given R&D, administration, and marketing expenditure values.

The predicted results can help demonstrate how a regression model supports financial planning and business decisions.

### 4. Power BI Dashboard

Created an interactive dashboard containing:

- Total Profit KPI
- Average Profit KPI
- State-wise Average Profit comparison
- R&D Spend vs. Profit scatter chart
- Marketing Spend vs. Profit scatter chart
- Administration vs. Profit scatter chart
- State slicer for interactive filtering

## 📊 Key Findings

- Florida recorded the highest average profit at approximately **118,774.02**.
- New York recorded an average profit of approximately **113,756.45**.
- California recorded an average profit of approximately **103,905.18**.
- The regression model achieved an R-squared value of approximately **95.07%**.
- R&D Spend was statistically significant at the 5% significance level in this model.
- Administration and Marketing Spend were not individually statistically significant at the 5% level, based on their p-values.

## 💡 Business Recommendations

- Evaluate R&D investments carefully, as R&D Spend showed a strong positive relationship with profit in this dataset.
- Investigate differences in operating performance across states before making expansion decisions.
- Review administration and marketing expenditure to identify opportunities for cost optimization.
- Use regression predictions as decision-support estimates, not guaranteed future profits.
- Validate the model on new or unseen data before relying on it for business forecasting.

## 📁 Project Files

Suggested repository structure:

```text
PRDA-01-Profit-Analysis/
│
├── README.md
├── dataset.csv
├── Profit_Analysis.xlsx
├── SQL_Queries.sql
├── Profit_Analysis_Dashboard.png
├── Regression_Output.png
└── Predicted_Profit_Output.png
```

*Upload only the files you actually have. Update the filenames to match your repository.*

## 🚀 Conclusion

This project demonstrates the practical application of SQL-based analysis, Excel regression modeling, profit prediction, and Power BI visualization to solve a business profitability problem.

It showcases analytical thinking, statistical interpretation, and data visualization skills relevant to Data Analyst roles.

## 👤 Author

**Prince Rajwar**

Aspiring Data Analyst | SQL | Excel | Power BI | Python


