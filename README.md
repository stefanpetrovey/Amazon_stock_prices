# 📈 Amazon Stock Price Prediction – Time Series Forecasting
In this laboratory assignment, the goal is to perform time series forecasting by predicting the current close price of Amazon stock using historical data. The dataset includes 7 days of previous stock statistics to predict the target value for the current day.

## 📊 Dataset Description
**The Amazon Stock Price Dataset consists of the following columns:**

date – *the date of the recorded price*

open – *the opening price of the stock*

high – *the highest price during the day*

low – *the lowest price during the day*

volume – *the volume of stocks traded*

close – *the closing price of the stock (Target variable)*

**Models Used**
To achieve accurate predictions, the following machine learning models were implemented and compared:

*Random Forest Regressor*

*XGBRegressor (Extreme Gradient Boosting)*

*GridSearchCV – used to fine-tune model hyperparameters for improved performance*

## Conclusion

In this project, time series forecasting techniques were successfully applied to predict the Amazon stock closing price using historical data from the past 7 days. Among the models tested, both Random Forest and XGBRegressor showed strong predictive capabilities. By leveraging GridSearchCV, hyperparameters were optimized to enhance model performance.

The results demonstrate that machine learning models can effectively capture trends and patterns in financial data, offering reliable predictions for stock price movement. This approach can be further expanded and improved by incorporating more features, increasing the time window, or applying deep learning models for even greater accuracy.



