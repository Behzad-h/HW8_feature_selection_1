# **Feature Selection Methods:** An Overview
______

In machine learning, Feature selection refers to the process of selecting a subset of relevant features (predictor variables) for use in model building. The goal of feature selection is to improve the performance of the model by reducing overfitting, improving interpretability, and reducing the computational cost.

There are several feature selection methods, and they can be broadly classified into three categories:

### **Filter Methods**
Filter methods select features based on some statistical measure, such as correlation or mutual information, without considering the model. The most commonly used filter methods include:

* Pearson Correlation Coefficient
* Mutual Information
* Chi-Square Test

### **Embedded Methods**
Embedded methods perform feature selection during the model training process. They select features by assigning them weights or coefficients based on their importance in the model. The most commonly used embedded methods include:

* Lasso Regression
* Ridge Regression
* Elastic Net

### **Wrapper Methods**
Wrapper methods select features by training a model on different subsets of features and evaluating its performance. The most commonly used wrapper methods include:

* Forward Selection
* Backward Elimination
* Recursive Feature Elimination (RFE)


Each method has its advantages and disadvantages. The choice of a particular feature selection method depends on the data set, the problem, and the machine learning algorithm used. In general, it is recommended to try multiple methods and compare their performance to choose the best one.

In conclusion, feature selection is a critical step in machine learning, and choosing the right method can significantly impact the performance of the model.

In `feature_selection.ipynb` notebook, we implement different types of feature selection methods on a sample dataset and investigate the output of each method.
