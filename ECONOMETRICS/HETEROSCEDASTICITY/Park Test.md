the form that Park Test takes is the following $$ ln \sigma_{i}^2 = B_1 + B_2 ln X_i + v_i $$
here $v_i$ is the residual term.
1. this is precisely what Park Test suggests. 
2. unfortunately the above regression is not operation since we do not know the heteroscedastic variance, so Park suggests using $e_i$ as proxies for $u_i$ and running the following regression $$ ln e_i^2 = B_1 + B_2 lnX_i + v_i $$

###### steps involved in Park's Test 
1. run the original regression despite heteroscedasticity problem, if any.
2. from this regression, obtain the residuals $e_i$, square them and take their log
3. run the regression suggested by Park using an explanatory variable in the original model and run the regression against each X variable, alternatively run the regression against the estimated Y.
4. test the null hypothesis that B2 = 0, the hypothesis that there is no heteroscedasticity in the model, if there exists a significant relationship between the natural log of ei squared and the natural log of Xi then it can be concluded that heteroscedasticity is present in the model and remedial measures need to be taken. 

> the problem with this test is that the error term in this regression may itself be heteroscedastic 
