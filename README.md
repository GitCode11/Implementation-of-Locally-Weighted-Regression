# Implementation-of-Locally-Weighted-Regression

Locally weighted linear regression is a non-parametric algorithm, that is, the model does not learn a fixed set of parameters as is done in ordinary linear regression. Rather parameters 'theta' are computed individually for each query point x. While computing 'theta', a higher “preference” is given to the points in the training set lying in the vicinity of x than the points lying far away from x.

The code above shows variation of the Locally Weighted Regression curve for various values of 'Tau'.

To run the code, please make sure that the latest version of Python, Jupyter and aforementioned libraries are installed in your system.
