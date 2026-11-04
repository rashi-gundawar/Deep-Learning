# Assignment 04 – LSTM Time-Series Forecasting

## Objective
To develop an LSTM-based model for time-series forecasting using historical stock-price data and predict the next day's closing price.

## Dataset
**AAPL Stock Price Dataset**

## Tasks Performed
- Loaded the historical AAPL stock-price dataset
- Explored the dataset and its columns
- Visualized historical closing prices
- Selected the closing price as the target variable
- Removed missing values
- Normalized the price values using MinMaxScaler
- Created time-series sequences using the previous 60 trading days
- Split the data into 80% training and 20% testing sets
- Reshaped the data for LSTM input
- Built an LSTM-based forecasting model
- Trained the model for 20 epochs
- Plotted training and validation loss
- Generated predictions on the test data
- Converted predictions back to the original price scale
- Calculated MAE and RMSE
- Compared actual and predicted stock prices
- Predicted the next day's closing price

## Visualization
The following graphs are generated:
- AAPL Historical Closing Price
- Training vs Validation Loss
- Actual vs Predicted Stock Prices

## Prediction
The trained LSTM model uses the most recent 60 trading days to predict the next AAPL closing price.

## Tools and Technologies
- Python
- Google Colab
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

## Result
The LSTM model was trained on historical AAPL stock prices and evaluated using MAE and RMSE. Actual and predicted prices were visualized, and the trained model was also used to forecast the next day's closing price.
