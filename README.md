# Linear Regression - Bias Variance Tradeoff 
## Tasks
### 1
Write a brief about what function does the method, LinearRegression().fit() performs

### 2
In this question you are going to calculate the bias and variance of your trained model.\
You have been provided with two datasets i.e., train set and test set, consisting of pairs (xi; yi).\
It can be loaded into your python program using pickle.load() function. Now divide the train\
set into 10 equal parts randomly, so that you will get 10 different train datasets to train your\
model.\
After re-sampling data, you have 11 different datasets (10 train sets and 1 test set). Train a\
linear classifier on each of the 10 train set separately, so that you have 10 different classifiers or\
models. Now you can calculate the bias and variance of the model using the test set. You need\
to repeat the above process for the following class of functions,\
• y = mx + c\
• y = ax2 + bx + c\
• y = ax3 + bx2 + cx + d\
And so on up till polynomial of degree 20. You are only supposed to use sklearn's\
linear model.LinearRegression().fit() and preprocessing.PolynomialFeatures() for\
finding the appropriate coefficients with the default parameters. Tabulate the values\
of bias and variance and also write a detailed report explaining how bias and variance changes\
as you vary your function classes.\
Note: Whenever we are talking about the bias and variance of model, it refers to the average\
bias and variance of the model over all the test points.

### 3
Tabulate the values of irreducible error for the models in Task 2 and also write a detailed report\
explaining why or why not the value of irreducible error changes as you vary your class function.

### 4
Based on the variance, bias and total error calculated in earlier tasks, plot the Bias^2 - \
Variance tradeoff graph and write your observations in the report with respect to underfitting,\
overfitting and also comment on the type of data just by analyzing the Bias^2 - Variance plot.

Answers to the above tasks are in report.pdf