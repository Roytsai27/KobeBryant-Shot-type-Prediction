# KobeBryant-Shottype-Prediction
### It's a machine learning competition to predict the shot-type  of Kobe
# Problem 
test.csv contains all the information about Kobe
Our goal is to use the features and predict his shot type.
# Details
The mail idea of our project is using feature **shot distance** to split thte data into two sets

For example, We split the data with shotdistance greater than 10 and build a model to train these two datasets

We had tried many classifier such as Knn,Logistic Regression , Decision Tree, Xgboost...
as we find out that Randomforest has the best performance on  both accuracy and running time 

We eventually use the model , and tuning parameters based on  this model