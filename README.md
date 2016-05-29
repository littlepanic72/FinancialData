# FinancialData

## This Julia program fetches financial data from Yahoo Finance/Quandl and forecasts short-term price ranges in the future using random forests.

### Ensemble of Decision Trees

Trees:      100  
Avg Leaves: 415.59  
Avg Depth:  29.82

### 3-fold cross validation on regression forest

Fold 1

Mean Squared Error:     0.013506732237340897  
Correlation Coeff:      0.9452438694109276  
Coeff of Determination: 0.8771963351855612

Fold 2

Mean Squared Error:     0.0127880043454881  
Correlation Coeff:      0.9495946508407064  
Coeff of Determination: 0.8826092401509804

Fold 3

Mean Squared Error:     0.011812978150587397  
Correlation Coeff:      0.9620822330219206  
Coeff of Determination: 0.8947737299087323

#### Mean Coeff of Determination: 0.8848597684150913

![1 year forecast](output_37_0.png)

![History and forecast](output_36_0.png)

![Features used in model training](output_33_0.png)

![Volatility](output_17_0.png)
