# FinancialData

## This Julia program fetches financial data from Yahoo Finance/Quandl and forecasts short-term price ranges in the future using random forests.

![History and forecast of price index of QQQ](qqq_history.png)

![1 year forecast of QQQ](qqq_forecast.png)

![Features for training](qqq_features.png)

## Ensemble of Decision Trees  
Trees:      100  
Avg Leaves: 418.93  
Avg Depth:  27.44  

## 3-fold cross validation on the random forest

Fold 1  
Mean Squared Error:     0.021131047915143485  
Correlation Coeff:      0.9341862122762002  
Coeff of Determination: 0.8189416800846483  

Fold 2  
Mean Squared Error:     0.02146196131223536  
Correlation Coeff:      0.9375898014408836  
Coeff of Determination: 0.8136340635718871  

Fold 3  
Mean Squared Error:     0.01909417461594455  
Correlation Coeff:      0.9371492832785526  
Coeff of Determination: 0.8194101077650078  

### Mean Coeff of Determination: 0.8173286171405144
