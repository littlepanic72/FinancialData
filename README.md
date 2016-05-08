# FinancialData

## Use random forest to forecast price range index

![History and forecast of price range index of QQQ](qqq_history.png)

![1 year forecast of price range index of QQQ](qqq_forecast.png)

![Features used in training](qqq_features.png)

## Model details

Ensemble of Decision Trees  
Trees:      100  
Avg Leaves: 479.43  
Avg Depth:  22.65  

## 3-fold cross validation on regression forest

Fold 1  
Mean Squared Error:     0.03600321661200395  
Correlation Coeff:      0.9073898246766314  
Coeff of Determination: 0.708264521440887  

Fold 2  
Mean Squared Error:     0.03518195921901468  
Correlation Coeff:      0.8900908356566225  
Coeff of Determination: 0.696364088606338  

Fold 3  
Mean Squared Error:     0.708265  
Correlation Coeff:      0.696364  
Coeff of Determination: 0.695934  

Mean Squared Error:     0.035798219972087875  
Correlation Coeff:      0.8974128265486412  
Coeff of Determination: 0.6959336390884633  

Mean Coeff of Determination: 0.7001874163785627
