The LASSO and Boosting for Regression
(a) Download the Communities and Crime data3 from https://archive.ics.uci. edu/ml/datasets/Communities+and+Crime. Use the first 1495 rows of data as the training set and the rest as the test set.
(b) The data set has missing values. Use a data imputation technique to deal with the missing values in the data set. The data description mentions some features are nonpredictive. Ignore those features.
(c) Plot a correlation matrix for the features in the data set.
(d) Calculate the Coefficient of Variation CV for each feature, where CV = ms , in
which s is sample standard deviation and m is sample mean..
√
128⌋ features with highest CV , and make scatter plots and box plots for them. Draw conclusions about significance of those features, just by the scatter plots.
(f) Fit a linear model using least squares to the training set and report the test error.
(g) Fit a ridge regression model on the training set, with λ chosen by cross-validation. Report the test error obtained.
(h) Fit a LASSO model on the training set, with λ chosen by cross-validation. Report the test error obtained, along with a list of the variables selected by the model. Repeat with standardized4 features. Report the test error for both cases and compare them.
(i) Fit a PCR model on the training set, with M (the number of principal compo- nents) chosen by cross-validation. Report the test error obtained
