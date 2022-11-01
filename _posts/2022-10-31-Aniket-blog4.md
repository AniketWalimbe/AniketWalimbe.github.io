# Importance of Variable Selection 

## Why Variable selection ? 
Variable selection means selection of appropriate variables from a complete list of variables by removing those which are irrelevant or redundant. The purpose of such selection is to determine a set of variables that will provide the best fit for the model so that accurate predictions can be made. Also, having fewer variables in the model means less computational time and complexity. 

## Techniques for variable selection 
Few of the techniques used for variable selection include : 
Backward Elimination - This is one of the most easiest of all variable selection processes. For this technique, first, start with all variables in the model and keep on eliminating the variables having the highest p-value greater than the critical alpha. Hence we will have a subset of predictors which will increase the accuracy of the model and reduce the complexity. 
Forward Selection - This is pretty similar to the backward elimation technique, the difference being that we start with no variables and add the variables having the lowest p-value less than alpha critical. 
Stepwise Regression - This technique is a combination of both backward elimination and forward selection metho, the main difference being variables can be eliminated even after getting added once. 
Best Subset Selection - This method builds all one-variable models, all two-variable models, and so on, until the last all-variable model is generated.
