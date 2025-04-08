# Solar_power_forcasting
*A Winning Project at the SAS Hackathon for Sustainability & Data4Good*

## Overview
This project aims to **forecast solar power production** using a variety of **time series modeling techniques**—both statistical and machine learning-based. Built collaboratively by our team for the **SAS Hackathon**, the solution was awarded **1st place** for its innovative approach to applying data science for sustainability.

## Objective
The primary goal is to evaluate the performance of classical statistical models versus machine learning approaches under various preprocessing and forecasting strategies. Solar energy production data serves as a rich, structured time series dataset.

##  Models & Techniques Used
We implemented and compared multiple forecasting strategies:
- **Direct Multi-step Forecast**
- **Recursive Multi-step Forecast**
- **Direct-Recursive Hybrid Forecast**

###  Models Included
- **Statistical Models**
  - Auto ARIMA
  - Auto ETS
- **Machine Learning Models**
  - LightGBM
  - Linear Regression
  - LSTM (Long Short-Term Memory Networks)

##  Key Findings
- **LightGBM** achieved the best results based on **Mean Absolute Error (MAE)**.
- **Linear Regression** performed best in terms of **Mean Squared Error (MSE)**.
- Among the strategies, the **Recursive Forecasting Method** showed the most consistent performance.

##  Tools & Libraries
- Python, pandas, NumPy
- `sktime`, `lightgbm`, `statsmodels`, `scikit-learn`, `keras`, `matplotlib`

## Impact
This project emphasizes how advanced forecasting methods can support **renewable energy optimization**, contributing to a more **sustainable and data-driven future**.


