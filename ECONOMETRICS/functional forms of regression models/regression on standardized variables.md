1. a variable is said to be standardized if we subtract the mean value of the variable from its individual values and divide the difference by the standard deviation of that variable. 
2. thus, in regression of Y on X, if we redefine these variables as $$ {Y_i}^\star = \frac{Y - \bar{Y}}{S_Y} $$ and $$  {X_i}^\star = \frac{X - \bar{X}}{S_X} $$ where Y bar is the sample mean of Y 
   S_Y is the sample standard deviation of Y 
   X bar is the sample mean of X 
   and S_X sample standard deviation of X. 
3. ${Y_i}^\star$ and ${X_i}^\star$ are called the standardized variables 
4. an interesting property of standardized variable is that the mean value is always zero and its standard deviation is always 1. 
5. and as a result it does not matter in what units the Y and X variable(s) are measured. 
6. therefore instead of running the standard bivariate regression, we could run the regression of standardized variables as $$ {Y_i}^\star = B_1^{\star} + B_2^{\star}X_i^{\star} + u_i^{\star}  $$
7. **the regression coefficient of the standardized explanatory variable denoted by the starred parameters are known as the beta coefficients**

###### the interpretation of the beta coefficient? 
1. the interpretation is that if the standardized regressor increases by one standard deviation, the average value of the standardized regressand increases by $B_2^{\star}$ standard deviation units. 
2. thus unlike the traditional models, we measure the effect not in terms of the units in which the Y and X are measured, but in the standard deviation units. 
3. 