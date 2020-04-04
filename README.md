# Regressions
Computes linear to 4-th order linear regressions on training data to find weight params and then compares training and test errors using these parameters. There is also an implementation of k-fold cross validation for the degree of the polynomail. It can be called multiple times with increasing degree to find the least error polynomial for the data. This helps with reducing the chance of overfitting data