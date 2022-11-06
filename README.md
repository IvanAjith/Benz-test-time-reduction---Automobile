Used Mercedes-Benz car dataset to predict the time it takes to pass testing.

Steps in my Project :

Step 1: Loaded the dataset file and combined the train and test dataset together with a indication so that I can separate later.

Step 2: Performed the EDA to check the nulls and outliers

Step 3:  Prepare a for loop to check and neglect the features with 95% cumulative unique value. By doing so, we can neglect around 233 columns out of 378 columns.

Step 4: Used the getdummies method to decode the categorical values

Step 5: Separated the train and test data set again 

Step 6: Prepared a base model – Linear Regression 

Step 7: Used PCA model to reduce the dimensions 

Step 8: Boosted the model with a XGBoost 

Step 9: Predicted using the x_test_transformed

