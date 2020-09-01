# Python-LSTM-Univariate-Time-Series-Forecasting-

The first part of this demonstration (PART A) is focused on data preparation with respect to the imported '.csv' file in order to track and handle missing values and to convert the data into a clean dataset (Data Cleaning/Preprocessing).

The second part of this project (Part B) comprises Case Study I and II. The scope of Case Study I is to use the average Monthly Minimum Temperature dataset (dataset has been grouped by the mean Monthly Minimum Temperature) so as to investigate and assess a) the LSTM model predictive capabilities by training this deep learning neural network with 9 years of past average monthly data from the 'MonthlyMinTemp' feature to predict the average Monthly Minimum Temperature values of the next 12 months and b) the LSTM forecasting capabilities by training the machine learning model with all dataset samples to forecast the average Minimum Temperature values for a prediction horizon of 12 months (future sequence of observations). In Case Study II, there is an increase in the size of the training set(dataset has been grouped by the mean Weekly Minimum Temperature) and the model predictive capabilities are investigated by training the LSTM with approximately 8.5 year of past average Weekly Miminum Temperature data to predict the average Weekly Minimum Temperature values for a prediction horizon of 1.5 year(78 weeks).

The evaluation of the LSTM model performance for the cases where the prediction horizon is known is based on the comparison of the forecasted values with the test(actual/target)values (Performance Metric --> Root Mean Squared Error), whereas for all examined Case Studies, the LSTM training performance is also provided (Training relative error percentage distribution plots and relative error summary statistics).

The Dataset (.csv file format) has been obtained from Kaggle:

"Daily Minimum Temperatures in Melbourne" -- File: "daily-minimum-temperatures-in-me.csv" -- Source:https://www.kaggle.com/paulbrabban/daily-minimum-temperatures-in-melbourne
