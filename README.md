# product-sales-predictions
# Prediction-of-Product-Sales
## * Author- Nicholas Giuffrida
## Project Overview
-  Predict future sales of items based on the factors provided

-  ##  Data
-  To prepare this data, the data was cleaned, and the following processes were performed:
## Expolratory Data Analysis

![image](https://github.com/SaintNickG/product-sales-predictions/assets/137968958/b5297929-d7ce-43ad-aefe-12e50b26c901)
>  **We Found that we could achieve more accurate models by examining Store Size to Impute missing values**
>
> 
> 

>![image](https://github.com/SaintNickG/product-sales-predictions/assets/137968958/75d51094-3ba1-42f9-9157-64eea16ab1b5)
> **We found our strongest correlation to Total Sales was with Retai Price**
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
