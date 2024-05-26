# Predicting Unemployment Rate Using Leading Economic Indicators

## Overview
This project aims to enhance economic decision-making by accurately predicting the future trajectory of the unemployment rate using leading economic indicators. Unemployment rate forecasts are crucial for policymakers and business leaders to inform decisions related to resource allocation, policy formulation, and job market interventions.

## Project Structure

1. **Business Problem**
   - Objective: Accurately predict the future trajectory of the unemployment rate.
   - Importance: Helps in resource allocation, policy formulation, and job market interventions.

2. **Data Collection and Preparation**
   - **Data Sources:** Federal Reserve Economic Data (FRED) and U.S. Department of the Treasury.
   - **Indicators:** Unemployment rate (UNRATE), initial jobless claims (ICSA), consumer sentiment index (UMCSENT), housing starts (HOUST), S&P 500 index (SP500), 10-year Treasury yield (GS10), Treasury par yield curve rates, and long-term rates.
   - **Preprocessing:** Resampling to monthly frequency, handling missing values using advanced interpolation techniques.

3. **Exploratory Data Analysis (EDA)**
   - **Visualizations:** Time series plots, histograms, scatter plot matrices, and correlation heatmap.
   - **Insights:** Identified trends, seasonality, and anomalies in each economic indicator.

4. **Feature Engineering**
   - Created lagged variables for up to 12 months.
   - Calculated moving averages (3, 6, and 12 months) to smooth out short-term fluctuations.

5. **Modeling**
   - **Models Used:** ARIMA, Random Forest, and Gradient Boosting.
   - **Model Selection:** Based on performance metrics like RMSE (Root Mean Square Error) and MAE (Mean Absolute Error).
   - **Best Model:** Random Forest with the lowest RMSE and MAE values.

6. **Model Evaluation**
   - **Metrics:** RMSE and MAE for each model.
   - **Random Forest Model:** RMSE: 0.070, MAE: 0.063.

7. **Deployment and Monitoring**
   - Continuous monitoring and updating of models.
   - Predictions made using new data.

## Getting Started

### Prerequisites
- Python 3.x
- Jupyter Notebook
- Libraries: pandas, matplotlib, seaborn, sklearn, statsmodels, fredapi, joblib
