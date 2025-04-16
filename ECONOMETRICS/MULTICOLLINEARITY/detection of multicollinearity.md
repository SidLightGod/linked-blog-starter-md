> 1. multicollinearity is a question of degree and not of kind. The meaningful distinction is not between presence and absence, but between its various degrees. 
> 2. since multicollinearity refers to the condition of explanatory variables that are assumed to be non-stochastic, it is a feature of sample and not of population. 

###### indicators of multicollinearity 
1. high $R^2$ but very few significant t ratios. This is the most classic symptom of multicollinearity. If the R square is very high say above 0.8, the F test in most cases reject the null hypothesis that the partial slope coefficients are jointly or simultaneously equal to zero. 
2. high pairwise correlation among the explanatory variables. In a multiple regression say involving six or more variables, we compute the coefficients of correlation between any pair of these variables and if some of these correlations are high say above 0.8, then there is serious collinearity. 
3. examination of partial correlation 
4. subsidiary or auxiliary regressions, since multicollinearity exists because one or more of the explanatory variables are exact or near exact linear combination of other explanatory variables. One way of finding out which X explanatory variable is highly collinear with the other X explanatory variables is to regress that X variable with other explanatory variables and to compute the corresponding R square, each of these regressions is called auxiliary and subsidiary 

## Variance Inflation Factor 
$$ VIF = \frac{1}{(1 - R_2^2)} $$
1. the right hand side of the equation is called the variance inflation factor because as R square increases, the variance and the standard error 
2. when this coefficient of determination is 1, these variances and standard errors are undefined, and of course if the R square is zero, that is, there is no correlation, then the VIF would be 1. 

###### why is it that the R square might just be a surface indicator of multicollinearity 
1. suppose an $R_i^2$ in an auxiliary regression is very high but less than 1, suggesting a high degree of collinearity 
2. but the variance of the explanatory variable depend not only the $\sigma^2$ but also on the variations in X2. 
3. so it can be very possible that the $R_i^2$ is very high but the $\sigma^2$ is low or the variations in the explanatory variable is high or both so that the variance of parameter can still be lower and the t ratio is higher. 
4. in other words a high R square can be counterbalanced by a low $\sigma^2$ or high variation in the explanatory variable 