# FinancialData

## This Julia program fetches financial data from Quandl/Yahoo Finance and forecasts short-term price ranges using a random forest.

### Ensemble of Decision Trees  
Trees:      100  
Avg Leaves: 438.92  
Avg Depth:  30.65  

### 3-fold cross validation on regression forest  
Fold 1  
Mean Squared Error:     0.014223813020761287  
Correlation Coeff:      0.9469233705611833  
Coeff of Determination: 0.8692589889371432  

Fold 2  
Mean Squared Error:     0.013609144779382772  
Correlation Coeff:      0.945900623295796  
Coeff of Determination: 0.871852067358602  

Fold 3  
Mean Squared Error:     0.013001991404043354  
Correlation Coeff:      0.9484130855432567  
Coeff of Determination: 0.8805596711384951  

Mean Coeff of Determination: 0.87389024247808  

![1 year forecast](output_28_0.png)

![History and forecast](output_27_0.png)

![Features used in model training](output_24_0.png)

![Volatility](output_30_0.png)
