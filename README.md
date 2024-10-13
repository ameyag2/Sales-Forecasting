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

## Screenshots
<img width="1097" alt="Screenshot 2024-03-06 at 6 50 07 AM" src="https://github.com/ameyagidh/CompanySalesForecasting/assets/65457905/db519453-b39f-4f64-a349-2169814d4d07">

<img width="1094" alt="Screenshot 2024-03-06 at 6 50 26 AM" src="https://github.com/ameyagidh/CompanySalesForecasting/assets/65457905/82c98764-543f-40ad-861e-a08ef7633726">

<img width="1081" alt="Screenshot 2024-03-06 at 6 52 04 AM" src="https://github.com/ameyagidh/CompanySalesForecasting/assets/65457905/78032518-f4be-453a-8cb7-2f845da2a148">

<img width="1111" alt="Screenshot 2024-03-06 at 6 54 17 AM" src="https://github.com/ameyagidh/CompanySalesForecasting/assets/65457905/610ab2b7-7cc0-4ae6-826f-f488f722b35e">

<img width="1088" alt="Screenshot 2024-03-06 at 6 56 48 AM" src="https://github.com/ameyagidh/CompanySalesForecasting/assets/65457905/49dd8144-f568-4e43-89cf-e17592f90703">

<img width="1075" alt="Screenshot 2024-03-06 at 7 02 34 AM" src="https://github.com/ameyagidh/CompanySalesForecasting/assets/65457905/f1d2ff53-6308-450c-a7ce-e022adc5522e">

## References

- [Statsmodels Documentation](https://www.statsmodels.org/stable/index.html)
- [Forecasting: Principles and Practice](https://otexts.com/fpp3/)