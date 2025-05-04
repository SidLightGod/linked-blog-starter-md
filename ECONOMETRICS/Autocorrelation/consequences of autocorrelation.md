1. the least squares estimators still unbiased
2. but they are not efficient that is they do not have the minimum variance anymore compared to the procedures that take into account autocorrelation. In short the usual ordinary least square estimators are not best linear unbiased estimators (BLUE)
3. the estimated variance of the OLS estimators are biased. sometimes the usual formula for calculation of the variance and the standard errors, seriously underestimate the true value of the variances and the standard errors, thereby inflating the t values, this gives the impression that the particular coefficient is statistically significantly different from zero but in reality they might not be. 
4. therefore the usual t and the f tests are not generally reliable.
5. the usual formula to compute the error variance namely $\hat{\sigma}^2$ = $\frac{RSS}{df}$, is a biased estimator of the true $\sigma^2$ and in some cases it is likely to underestimate the latter. 
6. as a consequence, the latter conventionally computed $R^2$ may be an unreliable measure of the true $R^2$ 
7. the conventionally computed variances and the standard errors of the forecast may also be inefficient. 