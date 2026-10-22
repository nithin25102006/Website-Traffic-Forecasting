# Website Traffic Forecasting Using LSTM

## Problem Statement
To predict future website traffic using past daily page views and help allocate server resources efficiently.

## Dataset
Daily page views for five Wikipedia articles over 400 days.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- TensorFlow and Keras
- Google Colab

## Methodology
1. Load and preprocess the dataset.
2. Check and handle missing values.
3. Create time-series sequences using the previous 30 days.
4. Train an LSTM model for 30 epochs.
5. Evaluate predictions using MAE and RMSE.
6. Plot actual versus predicted traffic.
7. Forecast website traffic for the next 7 days.

## Project Files
- `website_traffic.csv` — Dataset
- `future_traffic_forecast.csv` — 7-day forecast
- `Website_Traffic_Forecasting.ipynb` — Python notebook

## How to Run
Open the `.ipynb` notebook in Google Colab and run the cells in order.

## Evaluation
The model is evaluated using Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).
