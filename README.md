# FinancialData

## This Julia program fetches financial data from Quandl/Yahoo Finance and forecasts short-term price ranges using a random forest.

### Ensemble of Decision Trees  
Trees:      100  
Avg Leaves: 439.23  
Avg Depth:  29.41  

### 3-fold cross validation on regression forest  
Fold 1  
Mean Squared Error:     0.01361883615775832  
Correlation Coeff:      0.945731796988748  
Coeff of Determination: 0.8739716547505065  

Fold 2  
Mean Squared Error:     0.012130636926655322  
Correlation Coeff:      0.9532343272329584  
Coeff of Determination: 0.8860368625580082  

Fold 3  
Mean Squared Error:     0.01327994637297167  
Correlation Coeff:      0.9488790192785918  
Coeff of Determination: 0.8785499370865194  

Mean Coeff of Determination: 0.8795194847983447  

![1 year forecast](output_28_0.png)

![History and forecast](output_27_0.png)

![Features used in model training](output_24_0.png)

![Volatility](output_30_0.png)
