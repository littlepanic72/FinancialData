# FinancialData

## Julia code that fetchs financial data from Yahoo/Quandl and forecasts stock price range index using random forests

![History and forecast of price range index of QQQ](qqq_history.png)

![1 year forecast of price range index of QQQ](qqq_forecast.png)

## Details of the fitted random forest

Ensemble of Decision Trees  
Trees:      100  
Avg Leaves: 460.97  
Avg Depth:  23.8  

## 3-fold cross validation on the random forest

Fold 1  
Mean Squared Error:     0.034623180625582395  
Correlation Coeff:      0.8960158911544056  
Coeff of Determination: 0.7138680648885449  

Fold 2  
Mean Squared Error:     0.032621057531044786  
Correlation Coeff:      0.912091083315768  
Coeff of Determination: 0.7250511463096451  

Fold 3  
Mean Squared Error:     0.713868  
Correlation Coeff:      0.725051  
Coeff of Determination: 0.719149  

Mean Squared Error:     0.03343889177232751  
Correlation Coeff:      0.9032348461078543  
Coeff of Determination: 0.7191494071217978  

Mean Coeff of Determination: 0.7193562061066626
