white's general test of heteroscedasticity is quite easy to apply. 

###### the procedure to apply White's test 
1. we first estimate the regression by OLS, obtaining the residuals 
2. we then run the auxiliary regression $$ e_i^2 = A_1 + A_2X_{2i} + A_3X_{3i} + A_4X_{2i}^2 + A_5X_{3i}^2 + A_6X_{2i}X_{3i} + v_i $$
3. we obtain the R square from the auxiliary regression. Under the hypothesis that there is no heteroscedasticity, white has shown that the R square value times the sample size n follows a $\chi^2$ distribution with the degree of freedom equal to the number of explanatory variables in the regression excluding the intercept term, (k-1)
4. if the chi square value obtained from the regression is larger than the chi square critical value at the chosen level of significance or if the p value of the computed chi square value is reasonably low, we can reject the null hypothesis of no heteroscedasticity, otherwise we fail to reject the null hypothesis. 