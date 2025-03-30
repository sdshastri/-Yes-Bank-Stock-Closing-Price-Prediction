# Yes-Bank-Stock-Closing-Price-Prediction
## Problem Statement ==> Yes Bank is a well-known bank in the Indian financial domain. Since 2018, it has been in the news because of the fraud case involving Rana Kapoor. Owing to this fact, it was interesting to see how that impacted the stock prices of the company and whether Time series models or any other predictive models can do justice to such situations. This dataset has monthly stock prices of the bank since its inception and includes closing, starting, highest, and lowest stock prices of every month. The main objective is to predict the stock’s closing price of the month.\

# Model_Name	MSE	RMSE	R_squared
 0	Linear regression	19.9886	4.4709	0.9978
 1	Ridge regression	20.0954	4.4828	0.9978
 2	Lasso regression	20.9591	4.5781	0.9977
 3	KNN	37.7286	6.1424	0.9959

# Conclusions
Independent variables(input variable) have a very high influence on dependent variable(target variable).
The accuracy for each model is more than 95%.
In this case, Linear Regression has given the best results with lowest MSE and RMSE and highest R square value scores out of all.
KNN performed the worst out of all.
As we know that, lasso regression automatically selects only those features that are useful and hence discarded some features when applied in this case, whereas in this case all the features were important for prediction purpose so it ended up giving poor results.
