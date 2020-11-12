# ForestCoverTypes
Using the KNN (K Nearest Neighbors), Logistic Regression, and Decision Tree algorithms to classify the type of trees found in the Roosevelt National Park in Colorado.


# Problem Statement: Classify the types of trees found in the Rossevelt National Park in Colorado.

# Languages and Libraries Used: Python, Sklearn, Matplotlib, Pandas, Seaborn, Numpy.

# K Nearest Neighbors: 
After reducing the number of classes from 7 to 3, in the target variable, an optimum cluster value of K = 3 was chosen with a 96.7% accuracy rate. 

# Logistic Regression: 
The logisitic regression algorithm had an accuracy of 65% but its ROC score of 0.77 was in acceptable range.

# Decision Tree: 
Firstly using gini impurity to compuite the impurity of the nodes and then using the feature_importances_ function for feature selection 6 suitable features were selected to achieve an accuracy of 90.6%.

# What I Learnt:

1. KNN (K Nearest Neighbors), Error rate
2. Decision Tree, Entropy, Decision Tree, Information Gain, Cost Complextiy Pruning

# Dataset Source: 
The dataset was taken from the UCI Machine Learning Repository: https://archive.ics.uci.edu/ml/datasets/covertype
