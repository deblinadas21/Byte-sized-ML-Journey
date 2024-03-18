This is a sample project to predict on Market Trend using market data available on Yahoo-Finance. 

Required Modules for this project -
1. yfinance 
2. pandas
3. numpy
4. xgboost
5. matplotlib
6. scikit-learn

Steps - 

1. Download historical data for given ticker ( I have used nasdaq "^NDX" in the sample) form yahoo finance. If you already have data handy, can skip this step.

2. Create pandas data frame using the downloaded CSV file.

3. Used 95% of the data as my training data and 5% as test data to check if the prediction matches the test target data.

4. I have used the "Open","Volume" columns as "features" i.e independent data and "Close" i.e Closing price as the "target" i.e dependent data.

5. Train the XGBREgressor model with the 95% training data and predict.

5. Check accuracy of the model, optionally plot in the matplotlib chart to check how close it is to the actual test target data



