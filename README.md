# Tobacco-Use-and-Mortality
___________________________________________________________________________________________________________________________________________________________________
📌 Project Overview
This project analyzes the relationship between tobacco use and mortality rates using multiple public health datasets. By combining data preprocessing, exploratory data analysis (EDA), and machine learning techniques, the study aims to identify key factors contributing to tobacco-related deaths and provide data-driven insights.

___________________________________________________________________________________________________________________________________________________________________
🎯 Objectives

Analyze trends in tobacco consumption and mortality.
Identify correlations between smoking prevalence and health outcomes.
Build predictive models to estimate mortality impact.
Determine the most influential features affecting mortality rates.

___________________________________________________________________________________________________________________________________________________________________
📂 Dataset Description

The analysis uses multiple datasets representing different health indicators:

-Admissions Data – Hospital admission records

-Fatalities Data – Mortality statistics

-Health Metrics – General health indicators

-Prescriptions Data – Tobacco-related medication usage

-Smokers Data – Smoking prevalence by region/time

Each dataset is cleaned, standardized, and merged for analysis.

___________________________________________________________________________________________________________________________________________________________________
🛠️ Technologies Used

-Python
-Pandas & NumPy – Data manipulation
-Matplotlib & Seaborn – Data visualization
-Scikit-learn – Machine learning models
-Jupyter Notebook

___________________________________________________________________________________________________________________________________________________________________
🔍 Methodology

1. Data Cleaning
-------------------------------------
-Handling missing values

-Correcting data types

-Standardizing column names

2. Exploratory Data Analysis
-------------------------------------
-Trend analysis

-Correlation heatmaps

-Distribution analysis

3. Feature Engineering
--------------------------------------
-Creation of derived health indicators

-Aggregation of tobacco-related metrics

4. Model Building
--------------------------------------
-Train-test split

-Regression-based modeling

-Model evaluation using R² and MSE

5. Feature Importance & Explainability
---------------------------------------
-Identification of top predictors

-Interpretation of model outputs

___________________________________________________________________________________________________________________________________________________________________
📊 Key Findings

1. Tobacco use shows a strong positive correlation with mortality rates.
2. Smoking prevalence is a primary predictor of fatalities.
3. Hospital admissions act as a key intermediary factor

___________________________________________________________________________________________________________________________________________________________________
⚠️ Limitations

1. Results depend on dataset quality and completeness.
2. Causation cannot be fully inferred from correlation.
3. External socioeconomic factors are not included.

___________________________________________________________________________________________________________________________________________________________________
🚀 How to Run the Project

-git clone https://github.com/AfsanaShaikh21/tobacco-use-mortality.git
-cd tobacco-use-mortality
-pip install -r requirements.txt
-jupyter notebook Tobacco_Use_and_Mortality.ipynb

___________________________________________________________________________________________________________________________________________________________________
📁 Repository Structure
|
├── Tobacco_Use_and_Mortality.ipynb
├── data/
│   ├── admissions.csv
│   ├── fatalities.csv
│   ├── metrics.csv
│   ├── prescriptions.csv
│   └── smokers.csv
├── README.md
└── requirements.txt

___________________________________________________________________________________________________________________________________________________________________
📜 Conclusion

This project demonstrates how data science and machine learning can be applied to public health data to better understand the impact of tobacco use on mortality. The insights generated can support policy-making and preventive healthcare strategies.
