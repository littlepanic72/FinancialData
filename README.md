# FinancialData

## This Julia program fetches financial data from Yahoo Finance/Quandl and forecasts stock price ranges using random forests.

![History and forecast of price range index of QQQ](qqq_history.png)

![1 year forecast of price range index of QQQ](qqq_forecast.png)

## Details of the fitted random forest

Ensemble of Decision Trees  
Trees:      100  
Avg Leaves: 477.89  
Avg Depth:  23.48  

## 3-fold cross validation on the random forest

Fold 1
Mean Squared Error:     0.03243805322521157
Correlation Coeff:      0.9055747145626412
Coeff of Determination: 0.7276193474588981

Fold 2
Mean Squared Error:     0.03197463373965613
Correlation Coeff:      0.9025411161295627
Coeff of Determination: 0.7304534199794099

Mean Squared Error:     0.03200483942668486
Correlation Coeff:      0.9071267383215869
Coeff of Determination: 0.7318260345520213

# Mean Coeff of Determination: 0.7299662673301098
