# Ensemble learning Tutorial

 Ensemble methods is a machine learning technique that combines several base models in order to produce one optimal predictive model.


I took this dataset from Kaggle and cleaned it in a seprate file.

https://www.kaggle.com/datasets/altruistdelhite04/loan-prediction-problem-dataset

In this scenario we are exploring & comparing multiple Ensemble learning techniques to predict the loan status of a preson based on various parameters.

## [Basic Ensemble Techniques](https://github.com/madhur02/Ensemble_learning_on_Loan_dataset/blob/master/Simple%20Ensemble%20Learning%20Techniques.ipynb)
1. Max Voting
2. Averaging
3. Weighted Average
## [Advanced Ensemble Techniques](https://github.com/madhur02/Ensemble_learning_on_Loan_dataset/blob/master/Ensemble%20Learning%20on%20Loan%20Prediction..ipynb)
1. Bagging
2. Boosting
3. Stacking
## [Algorithms based on Bagging and Boosting](https://github.com/madhur02/Ensemble_learning_on_Loan_dataset/blob/master/Ensemble%20Learning%20on%20Loan%20Prediction..ipynb)
**1. Bagging meta-estimator** -- Bagging meta-estimator is an ensembling algorithm that can be used for both classification (BaggingClassifier) and regression (BaggingRegressor) problems. It follows the typical bagging technique to make predictions.

**2. Random Forest** 
Random forest is a Supervised Machine Learning Algorithm that is used widely in Classification and Regression problems. It builds decision trees on different samples and takes their majority vote for classification and average in case of regression

**3. AdaBoost or Adaptive boosting**
AdaBoost is one of the simplest boosting algorithms. Usually, decision trees are used for modelling. Multiple sequential models are created, each correcting the errors from the last model. AdaBoost assigns weights to the observations which are incorrectly predicted and the subsequent model works to predict these values correctly.

**4. GBM or Gradient Boosting** 
GBM is another ensemble machine learning algorithm that works for both regression and classification problems. GBM uses the boosting technique, combining a number of weak learners to form a strong learner. Regression trees used as a base learner, each subsequent tree in series is built on the errors calculated by the previous tree.

**5. XGB -- XGBoost (extreme Gradient Boosting)** 
XGB is an advanced implementation of the gradient boosting algorithm. XGBoost has proved to be a highly effective ML algorithm. XGBoost has high predictive power and is almost 10 times faster than the other gradient boosting techniques. It also includes a variety of regularization which reduces overfitting and improves overall performance. Hence it is also known as **‘regularized boosting‘** technique.
