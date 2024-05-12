# PREDICTING GAS PRICE WITH TIME SERIES ANALYSIS

In this repository, we explore time series analysis techniques to predict natural gas prices. Understanding and forecasting commodity prices like natural gas is crucial for various stakeholders in the energy market to make informed decisions and develop effective strategies.


# Features/Steps:
Historical natural gas price data is collected and preprocessed. This involves converting dates to datetime objects, setting the date as the index, and sorting the data by date.

Initial exploration of the data is conducted through visualization. Line plots are used to visualize the trend in gas prices over time, while box plots show seasonal trends by month.

Autoregressive Integrated Moving Average (ARIMA) models are fitted to the gas price data. ARIMA models capture temporal dependencies and patterns in time series data, providing a baseline for prediction.

The performance of the ARIMA model is evaluated using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE). This helps assess the accuracy of the model's predictions.

Rolling mean and standard deviation are calculated to visualize the trend and variability in gas prices over time. This provides additional insights into the data's behavior.

Seasonal decomposition analysis is performed to separate the data into its trend, seasonal, and residual components. This helps identify long-term trends and seasonal patterns in gas prices.

Using the ARIMA model, future gas price predictions are generated. This enables stakeholders to anticipate market trends and make proactive decisions.

Linear and bilinear regression techniques are applied to further analyze the data and identify underlying trends and patterns.

Interpolation is used to estimate gas prices for dates with missing data points. This ensures a complete and continuous dataset for analysis.

Visualization techniques such as line plots and scatter plots are employed to illustrate the model's predictions and interpret the results.



By combining advanced statistical methods with domain knowledge, this project aims to provide valuable insights into natural gas price forecasting, enabling stakeholders to make informed decisions in the energy market domain.
