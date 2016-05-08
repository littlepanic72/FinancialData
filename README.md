# FinancialData

## This Julia program fetches financial data from Yahoo Finance/Quandl and forecasts short-term price ranges in the future using random forests.

![History and forecast of price index of QQQ](qqq_history.png)

![1 year forecast of QQQ](qqq_forecast.png)

![Features for training](qqq_features.png)

## Details of the fitted random forest

Ensemble of Decision Trees  
Trees:      100  
Avg Leaves: 396.12  
Avg Depth:  23.84  

## 3-fold cross validation on the random forest

Fold 1  
Mean Squared Error:     0.035782284743962625  
Correlation Coeff:      0.9012970254510736  
Coeff of Determination: 0.7064563724722084  

Fold 2  
Mean Squared Error:     0.029660169369729494  
Correlation Coeff:      0.9082789864229112  
Coeff of Determination: 0.7362693809279154  

Fold 3  
Mean Squared Error:     0.03201644665648319  
Correlation Coeff:      0.900542762558105  
Coeff of Determination: 0.731425297197309  

### Mean Coeff of Determination: 0.724717016865811
