# KNN_Classification-Project
In this project I try to implement K Nearest Neighbor algorithm on a data set to to create a model that directly predicts a class for a new data point based off of the features. 
I have been given a classified data set from a company! They've hidden the feature column names but have given the data and the target classes.

The project notebook is structured as follows:
  * Importing libraries
  * Reading in the data set
  * Exploratory Data Analysis with seaborn 
  * Standardization of the variables with Scikit learn StandardScaler()
  * Splitting the data set into Training data and test data
  * Model creation with KNeighborsClassifier from Scikit Learn
  * Prediction  and model evaluation
  * Choosing best K value
  * Retraining the model with choosing K value
  * Reevaluating the model.
 The Created Model with best K value showed an improvement of the model overall performence. 
 
 
  WITH K=1
  
 [[107  37]
 [ 39 117]]
              precision    recall  f1-score   support

           0       0.73      0.74      0.74       144
           1       0.76      0.75      0.75       156

    accuracy                           0.75       300
   macro avg       0.75      0.75      0.75       300
weighted avg       0.75      0.75      0.75       300

 
 
 WITH K=25

[[114  30]
 [ 21 135]]
              precision    recall  f1-score   support

           0       0.84      0.79      0.82       144
           1       0.82      0.87      0.84       156

    accuracy                           0.83       300
   macro avg       0.83      0.83      0.83       300
weighted avg       0.83      0.83      0.83       300

