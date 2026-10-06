# Econometrics Panel Data Project – Impact of COVID-19 on U.S. GDP Growth

This project analyzes how the spread of COVID-19 affected quarterly GDP growth across U.S. states from 2020 to 2022 using panel-data econometric methods.

## 📊 Project Overview

The analysis constructs a state-quarter panel dataset combining:

- COVID-19 case counts from the Dartmouth Atlas Project
- GDP from the Bureau of Economic Analysis (BEA)
- Unemployment rate from the Bureau of Labor Statistics (BLS)
- Retail sales from the U.S. Census Bureau
- Mobility data from Google Mobility Reports
- Population data from the U.S. Census Bureau

## 🧮 Methods

The analysis applies multiple regression techniques to a state-level panel dataset.

\[
GDPGrowth_{it} = \beta_1 COVIDCases_{it} + \beta_2 Population_{it} + \beta_3 RetailSales_{it} + \beta_4 Mobility_{it} + \beta_5 UnemploymentRate_{it} + \alpha_i + \lambda_t + \epsilon_{it}
\]

- Estimated Pooled OLS, Fixed Effects, and Random Effects models
- Conducted a Hausman test to compare Fixed Effects and Random Effects specifications
- Interpreted model results and visualized key relationships in economic performance

## 🧰 Tools & Libraries

- Python: pandas, NumPy, statsmodels, matplotlib
- Jupyter Notebook for data analysis, econometric modeling, and visualization

## 📈 Key Findings

- Higher COVID-19 case counts were associated with lower quarterly GDP growth across states.
- The Fixed Effects specification helped account for unobserved, time-invariant differences across states.
- Model comparison favored the Fixed Effects approach as the most interpretable specification for this analysis.

## 📁 Files

- `covid_economic_panel_analysis.ipynb` — Full data cleaning, regression modeling, diagnostics, and visualization workflow
- `covid_economic_panel_analysis_report.pdf` — Written report summarizing data, methodology, and findings

## 👩‍💻 Author

**Cindy Jiang**  
B.S. Mathematics & B.A. Economics, Pepperdine University  
LinkedIn: linkedin.com/in/cindy-jiang-a1b7a5272
