# Linear_regression
Linear regression implementation(OLS)
If there is a relationship between variables that follow cause and effect, then the best representation you can use is Linear Regression.
There is one dependent variable (Y) and one independent variable (X) and the mathematical representation of it as follows:
 ### Y = mX + E ( E is the error we can anticipate and try to reduce and m is the slope of the regression line)
Important point to note is Linear regression can be called from sklearn.linearmodel linearregression.
But this sklearn model takes input in container form or arrays.
And the above model do not have any hyper parameters like "Regularization, Learning rate etc" because it is either implemented in SGD (Gradient Descent) or OLS(Ordinary least squares)

Linear regression is based upon FIVE assumptions:
     1. Linearity - Assuming we have linear relationship among variables.
     2. No endogeneity - Considering relevant or forgot to include a relevant variable.
     3. No normality - Meaning there is equal error for each data point.
     4. No auto correlation - If autocorelation is present, then we need to avoid using linear regression.
     5. No multi colinearity - If multiple variables are co related our linear regression model will be biased, hence we assume no multi-colinearity.
It will be the biggest mistake if we violate any of these assumptions.
