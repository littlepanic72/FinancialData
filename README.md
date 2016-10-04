# FinancialData

## This Julia program fetches financial data from Quandl/Yahoo Finance and forecasts short-term price ranges using a random forest.

### Ensemble of Decision Trees

Trees:      100  
Avg Leaves: 439.94  
Avg Depth:  30.45  

### 3-fold cross validation on regression forest

Fold 1

Mean Squared Error:     0.01498373502158112  
Correlation Coeff:      0.9448450483106067  
Coeff of Determination: 0.8662885967467642  

Fold 2

Mean Squared Error:     0.013102967741010418  
Correlation Coeff:      0.9472090295944326  
Coeff of Determination: 0.8769819849654112  

Fold 3

Mean Squared Error:     0.013108344026083551  
Correlation Coeff:      0.9464126557134377  
Coeff of Determination: 0.8756799214317152  

#### Mean Coeff of Determination: 0.8729835010479636

![1 year forecast](output_28_0.png)

![History and forecast](output_27_0.png)

![Features used in model training](output_24_0.png)

![Volatility](output_30_0.png)
