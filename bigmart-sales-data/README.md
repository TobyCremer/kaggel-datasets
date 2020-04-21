Credit-Card-Fraud-Detection
Machine learning models to automatically predict credit card frauds

Dataset
The dataset for this project was obtained from kaggle website.
[https://www.kaggle.com/mlg-ulb/creditcardfraud]

Requirements
Python 3.6
Pandas and Numpy
Keras 2.1.6
TensorFlow 1.8
Sklearn Library 0.19.1
Python's Matplotlib (2.2.2) for Visualization
Exploratory Data Analysis
   1. Checking the target class. (0 - No Fraud  1 - Fraud).


   2. Checking Time of Transaction vs Amount of Transaction for each class ((0 - No Fraud  1 - Fraud)


   3.  Amount per Transaction for each class (0 - No Fraud  1 - Fraud)


   4. Correlation Matrix between different features of the dataset


   3. Describing the dataset 


Data Preprocessing
Feature Elimination
Data Normalization
Balancing the skewed dataset using
3.1 Undersampling technique
3.2 Oversampling using SMOTE technique
Machine Learning Models
Used Sklearn, TensorFlow and Keras libraries to built the following models in Spyder IDE.

Autoencoder Artificial Neural Networks
Random Forest
Logistic Rregression
Performace Evaluation
5 fold cross Validation
Confusion Matrix
Precision - Recall Curves
Cohen's Kappa Statistic
AUC - ROC curves
Results
1. Autoencoders - Artificial Neural Network
   1.1 Model Loss for Autoencoders  -  Plot of Loss vs Epoch of training and testing data
Epoch = 88 , Batch_size = 32



   1.2 Error Distribution of Autoencoders for each class (0 - No Fraud  1 - Fraud).
  

              reconstruction error with no fraud         reconstruction error with fraud

  1.3 AUC - ROC  and Confusion Matrix for Autoencoders Neural Nets
 

  1.3  Precision- Recall Curves for Autoencoders Neural Nets
 

2. Random Forest
     2.1  AUC - ROC for Random Forest
  

   2.2  Precision- Recall Curves for Random Forest
  

   2.3 Confusion Matrix for Random Forest


3. Logistic Rregression
     3.1  AUC - ROC for Logistic Rregression


     3.2  Precision- Recall Curves for Logistic Rregression


       3.3  Confusion Matrix for Logistic Rregression
