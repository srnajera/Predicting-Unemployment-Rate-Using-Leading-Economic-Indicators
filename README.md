# Predicting Unemployment Rate Using Leading Economic Indicators

## Overview
This project embarked on a journey to enhance economic decision-making by accurately predicting the future trajectory of the unemployment rate. Leveraging leading economic indicators, the study aimed to provide forecasts that inform policymakers and business leaders, assisting them in resource allocation, policy formulation, and job market interventions.

## Data
The analysis utilized a comprehensive dataset covering key economic indicators sourced from the Federal Reserve Economic Data (FRED) and the U.S. Department of the Treasury. Indicators included the unemployment rate, initial jobless claims, consumer sentiment index, housing starts, S&P 500 index, and 10-year Treasury yield, among others.

## Analysis Highlights
- **Descriptive Statistics:** Provided insight into the distribution and central tendencies of the economic indicators, revealing significant variability and correlations with the unemployment rate.
- **Exploratory Data Analysis (EDA):** Time series plots, histograms, scatter plot matrices, and correlation heatmaps were used to identify trends and patterns, highlighting key relationships between indicators and the unemployment rate.
- **Feature Engineering:** Created lagged variables for up to 12 months and calculated moving averages to capture delayed effects and smooth out short-term fluctuations.
- **Forecasting Models:** Implemented ARIMA for initial trend analysis, and Random Forest and Gradient Boosting models to handle complex nonlinear relationships and improve predictive performance.
- **Model Evaluation:** The Random Forest model demonstrated the best predictive accuracy with the lowest RMSE (0.070) and MAE (0.063) compared to ARIMA and Gradient Boosting models.

## Key Findings
- **Correlation Analysis:** Identified strong correlations between the unemployment rate and indicators such as initial jobless claims (positive) and housing starts (negative), providing insights into the interconnected nature of economic indicators.
- **Model Performance:** The Random Forest model outperformed other models, effectively capturing the relationships between economic indicators and the unemployment rate, making it a reliable tool for forecasting.

## Conclusion
This project highlighted the significant influence of leading economic indicators on the unemployment rate. The models developed can be used to provide timely and accurate unemployment rate forecasts, aiding policymakers and business leaders in making strategic decisions.

## About the Analyst
Salina Najera conducted this analysis as part of her master's program in Data Science at Bellevue University. This project showcases her ability to apply advanced data science techniques to solve real-world economic problems.

**Date:** May 25, 2024

