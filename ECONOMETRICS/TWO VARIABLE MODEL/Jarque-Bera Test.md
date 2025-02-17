1. a test for normality that has been incredibly popular these days is the Jarque Bera test. 
2. this is an asymptotic or large sample and is based on the OLS residuals. This test first measures the coefficients of the skewness(a measure of the asymmetry of the PDF), S and the Kurtosis, K (a measure of how tall or flat the PDF is in relation to the normal distribution), of a random variable. 
3. Jarque and Bera has developed the following test statistic 
4. $$ JB = \frac{ n }{ 6 } [S^2 + \frac{ (K - 3)^2 }{ 4 } ] $$
5. for a normally distributed variable, the skewness is zero and the Kurtosis is 3. 
6. under the normality assumption the JB test follows the Chi Squared distribution with 2 D.F, asymptotically. 
7. $JB (asy) \sim X^2_2$
8. if the variable is normally distributed then the S is zero and the k - 3 is also zero therefore the value of the JB statistic is zero ipso facto 
9. if the variable is not normally distributed then the JB statistic would be taking increasingly larger values. 
10. if the computed chi values from the JB statistic exceeds the chi value for 2 D.F at the chosen level of significance, we reject the null hypothesis of the normal distribution. but if it does not exceed the critical chi value, we do not reject the null hypothesis 

> The confidence level = 100 - level of significance ($\alpha$) 
> p value <= $\alpha$ ---> we reject the null hypothesis 
> p value >= $\alpha$ ----> we fail to reject the null hypothesis 

