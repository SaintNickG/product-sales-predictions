# product-sales-predictions
# Prediction-of-Product-Sales
## * Author- Nicholas Giuffrida
## Project Overview
-  Predict future sales of items based on the factors provided

-  ##  Data
-  To prepare this data, the data was cleaned, and the following processes were performed:
## Expolratory Data Analysis

![image](https://github.com/SaintNickG/product-sales-predictions/assets/137968958/e90f193b-a1c7-4f19-b50a-ba9aac9f158e)
>  **We Found that we could achieve more accurate models by examining Store Size to Impute missing values**
>
> 
> 

>![image](https://github.com/SaintNickG/product-sales-predictions/assets/137968958/75d51094-3ba1-42f9-9157-64eea16ab1b5)
> **We found our strongest correlation to Total Sales was with Retai Price**
>![image](https://github.com/SaintNickG/product-sales-predictions/assets/137968958/fcd24bb4-421e-4374-8a74-c96a4afbfd4b)
>
> 
## Machine Learning Using the Following Models:
- Linnear Regression
- Bagged Tree Regressor model
- Random Forest Regressor Model
- Tuned Random Forest Regressor Model

###  Models Evaluated & Results
1 Linnear Regression
------------------------------------------------------------
Regression Metrics: Test Data
------------------------------------------------------------
- MAE = 805.628
- MSE = 1,197,790.279
- RMSE = 1,094.436
- R^2 = 0.566
2 Bagged Tree Model :
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

##  Recomendation

![image](https://github.com/SaintNickG/product-sales-predictions/assets/137968958/86b1212e-19b8-451d-ba30-a4e6afde496f)
**It is clear that the three most important coefficients used by our Linear Regression Model were the three Outlet Types: Grocery Store, Supermarket Type 2,and Supermarket Type 1**.
-  **We see that the three most important features used were *Outlet Type*, *Item Type, and Loc Type***.
- **Notice that the only feature with any noticeable positive influence over our model was the *Fat Content* feature.**

![image](https://github.com/SaintNickG/product-sales-predictions/assets/137968958/734d19f2-dd29-44c4-9a19-d28e0b89cac6)
**Our final image shows, that our most accurate model, predicts Retail Price as the most important factor to increase total product sales at a given outlet.**

-  Our three most important features for making predictions were: Retail Price Outlet Type_Grocery Store and Viz.
 -  Based on these Predictions, the recommendation is that the client place more, high retail price items in more grocery stores with higher visibility on the product.
