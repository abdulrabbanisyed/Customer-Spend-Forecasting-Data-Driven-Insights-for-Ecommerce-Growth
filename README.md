# Linear_regression
Linear regression implementation(OLS)
If there is a relationship between variables that follow cause and effect, then the best representation you can use is Linear Regression.
There is one dependent variable (Y) and one independent variable (X) and the mathematical representation of it as follows:
 ### Y = mX + E ( E is the error we can anticipate and try to reduce and m is the slope of the regression line)
Important point to note is Linear regression can be called from sklearn.linearmodel linearregression.
But this sklearn model takes input in container form or arrays.
And the above model do not have any hyper parameters like "Regularization, Learning rate etc" because it is either implemented in SGD (Gradient Descent) or OLS(Ordinary least squares)
