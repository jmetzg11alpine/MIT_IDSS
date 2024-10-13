## Linear Regression

# Performance Assessment - R Squared 
TSS = Total sum of squares of the difference of each y minus the mean of y

RSS = Residual Sum of squares, unexplained variation in Y, after taking into account X

R2 = 1 - (RSS/TSS)

# Assumtions
- independent
- Homoscedasticity - constant variance of errors
- linear relationship
- no multicollinearity 
- normality or residuals (with mean of zero)

# what can go wrong 
- heteroskedasticity, variance changes with observations. Errors aren't consistent.
- multicollinearity, features are aligned and can't tell which feature affects the target variable. 
- data can be used to make predictions, but it doesn't mean the model shows what is causing these outcomes (chocolate consumption and nobel prize winning). Latent Variables, z => x, z => y, x can be used to predict y, but x doesn't explain y

# Validation
- validation set, test set, and training set. Train with different alphas, number of features 
- k-fold cross validation, summary score of different 
- bootstrap (sampling wiht replacement), build many datasets from the same dataset to get a distribution of coefficients. 