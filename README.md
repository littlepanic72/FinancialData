# FinancialData

## This Julia code fetchs financial data from Yahoo/Quandl and forecasts stock price ranges using random forests.

![History and forecast of price range index of QQQ](qqq_history.png)

![1 year forecast of price range index of QQQ](qqq_forecast.png)

## Details of the fitted random forest

Ensemble of Decision Trees  
Trees:      100  
Avg Leaves: 477.89  
Avg Depth:  23.48  

## 3-fold cross validation on the random forest

Fold 1  
Mean Squared Error:     0.031918574720917636  
Correlation Coeff:      0.9088350744651604  
Coeff of Determination: 0.7321444286782817  

Fold 2  
Mean Squared Error:     0.03260557226307098  
Correlation Coeff:      0.9150934546617377  
Coeff of Determination: 0.7293181231108234  

Fold 3  
Mean Squared Error:     0.732144  
Correlation Coeff:      0.729318  
Coeff of Determination: 0.714252  

Mean Squared Error:     0.03341205552292637  
Correlation Coeff:      0.8997983221864012  
Coeff of Determination: 0.7142518656545618  

Mean Coeff of Determination: 0.7252381391478889
