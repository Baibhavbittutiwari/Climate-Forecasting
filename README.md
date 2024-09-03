# Delhi-Climate-Analysis-and-Forecasting
This project analyzes and forecasts the mean temperature of Delhi using time series data. It includes data import, visualization, stationarity checks, seasonal decomposition, and model building with advanced techniques like LSTM (Long Short-Term Memory) neural networks.
## Data Analysis:

- Import Data: Load and preprocess data, handle missing values, and convert dates.
- Visualization: Scatter plots to visualize temperature trends.
- Stationarity Check: Augmented Dickey-Fuller test for stationarity and necessary transformations.
- ACF and PACF Tests: Analyze data properties.
- Seasonal Decomposition: Verify seasonality patterns.

## Model Prediction:
![image](https://github.com/user-attachments/assets/3babd4ac-9b83-4ba8-a2b3-0fe7ccfea6f5)

- Data Preparation: Add cyclical and lagging features.
- Data Preprocessing: Normalize features and split data.
- Model Preparation: Define and compile a Bidirectional LSTM model.
- Model Training: Train with early stopping and learning rate reduction.
- Model Prediction: Evaluate the model and visualize results.

Scripts 'time_series_analysis.py' and 'prediction.py' cover data analysis and LSTM model building, respectively. This project demonstrates a comprehensive approach to time series forecasting, ensuring accurate and robust predictions.
