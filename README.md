# FinancialData

## This Julia program fetches financial data from Yahoo Finance/Quandl and forecasts short-term price ranges in the future using random forests.

![History and forecast of price index of QQQ](qqq_history.png)

![1 year forecast of QQQ](qqq_forecast.png)

![Features for training](qqq_features.png)

## Details of the fitted random forest

Ensemble of Decision Trees  
Trees:      100  
Avg Leaves: 421.59  
Avg Depth:  27.74  

## 3-fold cross validation on the random forest

Fold 1  
Mean Squared Error:     0.021890818926757215  
Correlation Coeff:      0.9435258136392332  
Coeff of Determination: 0.8063872723195904  

Fold 2  
Mean Squared Error:     0.02718300987571482  
Correlation Coeff:      0.9187867881263782  
Coeff of Determination: 0.768617616706045  

Fold 3  
Mean Squared Error:     0.025663664962558487  
Correlation Coeff:      0.9248810161391396  
Coeff of Determination: 0.78151116167982  

### Mean Coeff of Determination: 0.7855053502351518
