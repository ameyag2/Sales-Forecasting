# Company Sales Forecasting

This project focuses on predicting sales using the SARIMA (Seasonal Autoregressive Integrated Moving Average) model after performing Exploratory Data Analysis (EDA) on the dataset. SARIMA is a robust technique for time series forecasting, capable of handling data with both trends and seasonal patterns.

## Project Overview

In this project, we:
- Preprocessed the sales dataset
- Conducted EDA to analyze the sales distribution over time
- Checked the time series data for stationarity
- Determined the best SARIMA model parameters using the Akaike Information Criterion (AIC)
- Trained the SARIMA model
- Assessed the model's performance with diagnostic plots and calculated the Root Mean Squared Error (RMSE)
- Created out-of-sample forecasts for future sales

## Steps to Get Started

To run this project locally, follow these instructions:

1. Clone the repository:
   ```
   git clone https://github.com/ameyagidh/CompanySalesForecasting.git
   ```

2. Install the necessary dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Open and execute the `sales_forecasting.ipynb` notebook to explore the code and reproduce the results.

## Project Structure

The repository contains the following files:
- `sales_forecasting.ipynb`: A Jupyter Notebook with the code for sales forecasting using the SARIMA model.
- `prediction.csv`: A CSV file containing the predicted sales values.

## Results

The SARIMA model was successfully trained on the sales data, and future sales forecasts were generated. These predictions are saved in the `prediction.csv` file.

## References

- [Statsmodels Documentation](https://www.statsmodels.org/stable/index.html)
- [Forecasting: Principles and Practice](https://otexts.com/fpp3/)
