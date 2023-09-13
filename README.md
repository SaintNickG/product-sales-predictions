# product-sales-predictions
# Prediction-of-Product-Sales
## * Author- Nicholas Giuffrida
## Project Overview
-  Predict future sales of items based on the factors provided

-  ##  Data
-  To prepare this data, the data was cleaned, and the following processes were performed:
## Expolratory Data Analysis
![exploratory](https://github.com/SaintNickG/Prediction-of-Product-Sales/assets/137968958/3cf5ad37-1cd4-45f5-a996-49dab462ae8dthi)

>  **The comparison of Low Fat, versus Regular Items in our data set**
>
> 
> 
 ![heatmap](https://github.com/SaintNickG/Prediction-of-Product-Sales/assets/137968958/b1829aaa-99e7-4520-9b89-611b9ef36c3f)
>  **A heatmap to show correlation between our numerical features**
>
> 
> 
## Maching Learning Using the Following Models:
- Bagged Tree Regressor model
- Random Forest Regressor Model
- Tuned Random Forest Regressor Model

###  Models Evaluated & Results

1 Bagged Tree Model :
------------------------------------------------------------
Regression Metrics: Test Data
------------------------------------------------------------
- MAE = 758.095
- MSE = 1,180,809.190
- RMSE = 1,086.650
- R^2 = 0.572

- 
2 Default Random Forest Regressor Model: Test Data
------------------------------------------------------------
Regression Metrics: Test Data
------------------------------------------------------------
- MAE = 775.778
- MSE = 1,251,016.208
- RMSE = 1,118.488
- R^2 = 0.547

- 
3 Tuned Random Forest Regressor Model: Test Data
------------------------------------------------------------
Regression Metrics: Test Data
------------------------------------------------------------
- MAE = 728.168
- MSE = 1,091,820.739
- RMSE = 1,044.902
- R^2 = 0.604

The Final Model Chosen was a Tuned Random Forest Regressor Model.

For the testing set on the model, 60.4 of the variance in y was explained by x.

The Mean Absolute Error was off by about 728.17.

The Mean Squared Error was 1,091,820.739.

The Root Mean Squared Error had a calculation of  1,044.902 .
