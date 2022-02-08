# ecuadorsales_regression
This project is created for Springboard as final capstone project.

## 1. Data
Data source: [Kaggle](https://www.kaggle.com/c/store-sales-time-series-forecasting/data) <br>
Data updated date: August 2017 <br>
Data start date: Jan 2013

## 2. Models
This repo explored some basic time series forecasting models:
* Simple Moving Average
* Exponential Moving Average
* Facebook Prophet
* Scikit Learn - Linear Regression
* Scikit Learn - Random Forest Regressor
* Scikit Learn - Support Vector Regressor

## 3. Model Performance
![table_rmse](/figures/table_rmse.JPG)

Facebook Prophet model is the best performing model. Considering that moving average is not a prediction model, but can be used to get a general average for one day in the future.

## 4. Next Steps
* Encode more features to be included as numerical features so the model can perform best.
* Use [time series split](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.TimeSeriesSplit.html)  to perform cross validation
