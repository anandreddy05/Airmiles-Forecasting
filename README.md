# Airmiles Forecasting Project
This project focuses on time series forecasting using historical airmiles data. The goal is to analyze trends, seasonal patterns, and make future predictions using the Holt-Winters Exponential Smoothing model.

## GitHub Repository: Airmiles Forecasting

## Dataset Overview
The dataset consists of daily air traffic data with the following columns:

- Date: The observation date (starting from January 1, 1996).
- Airmiles: The total number of air miles recorded on that date.
## Exploratory Data Analysis (EDA)

EDA was conducted to visualize trends, seasonal patterns, and stationarity. The analysis included:
## Time series plots
- Seasonal decomposition
- Autocorrelation and Partial Autocorrelation (ACF & PACF) analysis
## Time Series Modeling
The project applies the Holt-Winters Exponential Smoothing Model, which considers:
- Trend: Multiplicative
- Seasonality: Multiplicative
- Seasonal Periods: 12

The model was trained on historical data and used to forecast future air miles.

## Model Evaluation
To assess model performance, the following metrics were used:
- Mean Absolute Error (MAE): 877,575.16
- Root Mean Squared Error (RMSE): 877,575.16
- Mean Absolute Percentage Error (MAPE): 1.80%

## Forecast Visualization
Visualizations of actual vs. predicted values were generated to assess model accuracy and trends.

## How to Run the Project
- Clone the repository
```bash
git clone https://github.com/anandreddy05/Airmiles-Forecasting.git
cd Airmiles-Forecasting
```
```bash
pip install -r requirements.txt
```
## Future Enhancements
- Experiment with ARIMA, Prophet, and LSTM models
- Improve hyperparameter tuning for better forecasts
- Deploy as a real-time forecasting app

📢 Contributions are welcome! Feel free to fork, modify, and submit a pull request.
