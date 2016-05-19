# FinancialData

## This Julia program fetches financial data from Yahoo Finance/Quandl and forecasts short-term price ranges in the future using random forests.

![History and forecast of price index](spy_history.png)

![1 year forecast](spy_forecast.png)

![Features for training](spy_features.png)

## Ensemble of Decision Trees

Trees:      100  
Avg Leaves: 415.99  
Avg Depth:  25.19  

## 3-fold cross validation on regression forest

Fold 1  
Mean Squared Error:     0.02079689266339276  
Correlation Coeff:      0.9348193684999118  
Coeff of Determination: 0.8208028712513316  

Fold 2  
Mean Squared Error:     0.01911643866315224  
Correlation Coeff:      0.9449366800371554  
Coeff of Determination: 0.8391696908592661  

Fold 3  
Mean Squared Error:     0.019817021588446466  
Correlation Coeff:      0.9353083293873988  
Coeff of Determination: 0.8270664286744345  

Mean Coeff of Determination: 0.829012996928344
