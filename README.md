# White-wine-quality-prediction-with-MLR-model
Use R and multiple linear regression to predict white wine quality by analyzing white wine lab results

## dataset is from kaggle [https://www.kaggle.com/danielpanizzo/wine-quality].

## data dimension:
4898 observations on 12 variables.

## Project goal: 
finding the suitable MLR model to predict “Vinho verde” white wine quality using physicochemical factors. 
The fianl model can benefit wine producers,suppliers and customers.

## Methods:

1. Variable selection:AIC,BIC, adjusted R square and backwards stepwise selection.

2. Assumptions check: constant variance, linearity, and normality  using redisual plot and QQ-plot.

3. Leverage and outliers check by using standardized residual vs. leverage plots.

4. Box-Cox transformation: log and sqrt transformation.

5. Cross-validation: Fitted ordinary least squares model, backwards stepwise model, ridge model, and Lasso model with cross-
validation


## Result:

The best model is OLS_fianl model with 0.7226 RMSE. 








                 
