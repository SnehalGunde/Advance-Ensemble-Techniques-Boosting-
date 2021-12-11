# Boosting

An ensemble is a collection of models which ideally should predict better than individual models. The key idea of boosting is to create an ensemble which makes high errors only on the less frequent data points.
Boosting leverages the fact that we can build a series of models specifically targeted at the data points which have been incorrectly predicted by the other models in the ensemble. If a series of models keep reducing the average error, we will have an ensemble having extremely high accuracy.
Boosting is a way of generating a strong model from a weak learning algorithm.

Some examples of Boosting algorithms are — AdaBoost, Gradient Boosting Machine (GBM), XGBoost.

a. AdaBoost : 
AdaBoost stands for Adaptive Boosting, was developed by Schapire and Freund, who later on won the 2003 Godel Prize for their work. In this method, every subsequent model is built on a new distribution. This new distribution is created by changing the probability or weights attached with every point. Here, we explain the AdaBoost algorithm using the classification setting in which the target values are +1/-1.

b. Gradient boosting :
Gradient boosting is a machine learning technique used in regression and classification tasks, among others. It gives a prediction model in the form of an ensemble of weak prediction models, which are typically decision trees.

c. XGBoost:
Extreme Gradient Boosting (XGBoost) is similar to the gradient boosting framework but more efficient and advanced implementation of the Gradient Boosting algorithm.
It was first developed by Taiqi Chen and became famous in solving the Higgs Boson problem. Due to its robust accuracy, it has been widely used in machine learning competitions as well. It uses more accurate approximations to tune the model and find the best fit.
Let’s have a look at some of the advantages of XGBoost:
1. Parallel Computing:​ when you run xgboost, by default, it would use all the cores of your laptop/machine enabling its capacity to do parallel computation
2. Regularization:​ The biggest advantage of xgboost is that it uses regularization and controls the overfitting and simplicity of the model which gives it better performance.
3. Enabled Cross-Validation: ​XGBoost is enabled with internal Cross Validation function
4. Missing Values:​ XGBoost is designed to handle missing values internally. The missing values are treated in
such a manner that if there exists any trend in missing values, it is captured by the model.
5. Flexibility: ​XGBoost is not just limited to regression, classification, and ranking problems, it supports
user-defined objective functions as well. Furthermore, it supports user-defined evaluation metrics as well.
