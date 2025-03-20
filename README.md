# Demand Forecasting

## Objective
Forecast the demand for the next 36 months using the provided dataset.

## Models Used
- **Univariate Forecasting:** ARIMA
- **Multivariate Forecasting:** LSTM (Long Short-Term Memory Neural Network)

## Dataset
- The dataset contains the following columns:
  - `internal_product_code`
  - `internal_geo_code`
  - `period_start` (timestamp for demand data)
  - `value` (demand quantity)

## Steps to Run the Code
1. Install required dependencies:
   ```bash
   pip install pandas numpy matplotlib statsmodels scikit-learn tensorflow
   ```
2. Place the `data.parquet` file in the working directory.
3. Run the Python script:
   ```bash
   python demand_forecasting.py
   ```

## Model Evaluation
- The last 6 months of data are used for testing model accuracy.
- ARIMA and LSTM forecasts are compared against actual values.

## Output
- The script will generate demand forecasts for the next 36 months.
- A visualization will be displayed comparing ARIMA and LSTM forecasts.

## Contribution
- Clone this repository.
- Modify the model or preprocessing as needed.
- Share your changes via a pull request.

## License
This project is open-source and available for public use.

