# FinancialData

## This Julia program fetches financial data from Yahoo Finance/Quandl and forecasts short-term price ranges in the future using random forests.

### Ensemble of Decision Trees

Trees:      100  
Avg Leaves: 409.58  
Avg Depth:  26.33

### 3-fold cross validation on regression forest

Fold 1  
Mean Squared Error:     0.01416369515677799  
Correlation Coeff:      0.944565152014596  
Coeff of Determination: 0.8629132878766308

Fold 2  
Mean Squared Error:     0.016875723818731016  
Correlation Coeff:      0.9454304001711907  
Coeff of Determination: 0.8554258091994553

Fold 3  
Mean Squared Error:     0.013393011766480984  
Correlation Coeff:      0.9549022819375861  
Coeff of Determination: 0.8797912443538789

#### Mean Coeff of Determination: 0.8660434471433217

![1 year forecast](output_39_0.png)

![History and forecast](output_38_0.png)

![Features used in model training](output_35_0.png)

![Volatility](output_17_0.png)
