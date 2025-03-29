# INVSTO
Scenario: You are a data science intern for a hedge fund that trades markets based on data science models. Your team needs a robust model as well as pipeline to process and analyze large volumes of historical stock data efficiently. You are tasked with building a data science model to predict stock market prices based on machine learning

Dataset:
• daily OHLC data feeds for multiple stocks in various formats (e.g., CSV, JSON).
• Eg: Yahoo Finance/yfinance - try 5-10 equities as a sample dataset

Tasks:
1. Data Preparation:
○ Clean the dataset to handle anomalies, missing values, or corrupt data.
○ Prepare the data for time series analysis, ensuring it is in the correct format and indexed by date.
2. Exploratory Data Analysis (EDA):
○ Perform a detailed analysis of the stocks’ historical prices and volumes.
○ Visualize trends, seasonal variations, and other patterns in the data.
3. Feature Engineering:
○ Create new features that could be useful for predictive modeling, such as lagged variables, rolling means, and percentage changes.
4. Modeling:
○ ARIMA Model:
§ Develop an ARIMA model for at least one of the stocks. Determine the optimal parameters (p, d, q) using ACF and PACF plots or grid search techniques.
§ Forecast the future prices and compare them against the actual prices.
○ Gradient Boosting:
§ Apply a Gradient Boosting model to predict the stock prices. Utilize features like lagged returns, volume changes, and moving averages.
§ Experiment with different hyperparameters to optimize model performance.
5. Model Evaluation:
○ Evaluate both models using metrics such as RMSE, MAE, and MAPE.
○ Compare the performance of the ARFIMA and Gradient Boosting models in terms of accuracy and reliability.
6. Report and Presentation:
○ Prepare a comprehensive report detailing your methodology, analysis, model development, findings, and recommendations.
○ Include visualizations to support your conclusions and model performance comparisons.
○ Provide a detailed discussion on the implications of your findings for trading strategies.

Technologies:
• Python libraries: pandas, numpy, Dask (for large datasets), data validation libraries (e.g., pytest)
• Cloud storage or data warehouse (e.g., AWS S3, Google Cloud Storage, Snowflake) (optional)
• Visualization tools (e.g., Tableau, Power BI) (optional)
