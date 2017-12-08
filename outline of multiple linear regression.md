# 1.   Plan
a.   Think about the system you are studying.
b.   Choose independent and dependent variables
c.    Think about possible models (is it reasonable to assume the model should be  linear?)
d.   Research the best ways to measure those variables
e.   Develop a research plan
f.  Consider resources and determine appropriate sample size
g.   Make a plan for getting a sample

# 2.   Explore
a.   Collect, clean, and organize data
b.   Univariate statistics and plots

# 3.   Split
a.   Training vs test set (if you have enough data—otherwise, skip this step)

# 4.   Fit
a.   Fit some initial models of interest

# 5.   Diagnose
a.   Residual plots (e or t vs Y-hat, X1, ..., X(p-1)) 
               i.   Look for correct functional form or nonlinearity
               ii.   Look for evidence of nonconstant variance
               iii.   Look for evidence of outliers
               
b.   Added variable plots
               i.   Help assess functional form of predictors
               ii.   Help assess influential outliers
c.    Normal Q-Q plot & Shapiro-Wilk’s test
               i.   Assess normality assumption for errors
d.   Breusch-Pagan test and Brown-Forsythe test
               i.   Start with residual plots first to look for nonconstant error variance
               ii.   Use these tests to formally assess nonconstant error variance
e.   Variance inflation factors and scatterplot matrix (pairs)
               i.   Help look for multicollinearity
f.  Plot residuals vs time order
               i.   Check for correlated errors
g.   Deleted studentized residuals help look for Y-outliers
h.   DFFITS, DFBETAS, Cook’s Distance,
               i.   Plot Cook’s distance
               ii.   Look for evidence of influential outliers
               iii.  Leverage (from H matrix)
               iv.   Look for potential influential outliers
               v.   Check for extrapolation

# 6.   Transform
a.   Change form of predictors to include polynomial terms, etc.
b.   Transform Y with Box-Cox procedure (variance stabilizing)
c.    Change model to account for correlated error structure
d.   Change model to nonlinear form (e.g. logistic regression)
e.   Others: weighted least squares for nonconstant variance 
f.  Drop predictors or use ridge regression for multicollinearity
g.   Use robust regression methods to account for influential cases

# 7.   Select
a.   Use variable selection criteria if appropriate
b.   This will not be a focus of every study

# 8.   Test/Assess
a.   Fit your chosen model to the test set and compare the fit to the training set.

# 9.   Diagnose
a.   Run diagnostics again just to double check

# 10. Interpret
a.   Interpret your output
b.   Remember to watch out for interpretations if there are interactions or multicollinearity

