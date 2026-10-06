# COVID-19 and U.S. Economic Performance: Panel Data Analysis

This project analyzes how the spread of COVID-19 affected quarterly GDP growth across U.S. states from 2020 to 2022 using panel-data econometric methods.

The analysis combines economic, demographic, mobility, and public-health data to evaluate how COVID-19 conditions were associated with differences in state-level economic performance.

---

## 📊 Project Overview

The analysis constructs a state-quarter panel dataset combining:

- **COVID-19 case counts** — Dartmouth Atlas Project
- **Gross Domestic Product (GDP)** — U.S. Bureau of Economic Analysis (BEA)
- **Unemployment rate** — U.S. Bureau of Labor Statistics (BLS)
- **Retail sales** — U.S. Census Bureau
- **Mobility indicators** — Google Mobility Reports
- **Population data** — U.S. Census Bureau

The goal is to evaluate how COVID-19 conditions and related economic indicators were associated with differences in GDP growth across U.S. states.

---

## 🔍 Research Question

**How did the spread of COVID-19 affect quarterly GDP growth across U.S. states during 2020–2022?**

The analysis also examines how unemployment, retail sales, mobility, and population relate to differences in economic performance.

---

## 🧮 Methodology

The analysis applies multiple regression techniques to state-level panel data.

**General model specification:**

GDP Growth = COVID-19 Cases + Population + Retail Sales + Mobility + Unemployment Rate + State Effects + Time Effects + Error

### Models Estimated

- **Pooled Ordinary Least Squares (OLS)**
- **Fixed Effects Model**
- **Random Effects Model**
- **Hausman Test** to compare Fixed Effects and Random Effects specifications

The workflow includes:

- Data cleaning and transformation
- Integration of multiple public datasets
- Panel-data regression
- Model comparison
- Statistical interpretation
- Data visualization

---

## 🛠 Tools & Libraries

- **Python**
- **pandas**
- **NumPy**
- **statsmodels**
- **matplotlib**
- **Jupyter Notebook**

These tools were used for data preparation, econometric modeling, statistical analysis, and visualization.

---

## 📈 Key Findings

- Higher COVID-19 case counts were associated with lower quarterly GDP growth across states.
- The Fixed Effects specification helped account for unobserved, time-invariant differences across states.
- Comparing multiple panel-data specifications provided a more robust framework for evaluating state-level economic performance.
- The Fixed Effects model produced the most interpretable results for this analysis.

---

## 📁 Repository Contents

### Analysis Notebook

[covid_economic_panel_analysis.ipynb](./covid_economic_panel_analysis.ipynb)

Contains the main analytical workflow, including:

- Data preparation
- Exploratory analysis
- Pooled OLS estimation
- Fixed Effects estimation
- Random Effects estimation
- Hausman testing
- Visualization and interpretation

### Written Report

[covid_economic_panel_analysis_report.pdf](./covid_economic_panel_analysis_report.pdf)

Contains the written project report, including:

- Research motivation
- Data description
- Econometric methodology
- Model interpretation
- Results and conclusions

---

## 💡 Skills Demonstrated

- Python
- pandas
- NumPy
- statsmodels
- Panel Data Analysis
- Regression Analysis
- Fixed Effects Models
- Random Effects Models
- Econometrics
- Statistical Modeling
- Data Cleaning
- Data Visualization
- Quantitative Research
- Economic Data Analysis

---

## 👩‍💻 Author

**Cindy Jiang**

B.S. Mathematics & B.A. Economics  
Pepperdine University

[LinkedIn Profile](https://www.linkedin.com/in/cindy-jiang-a1b7a5272)
