1. OLS estimators are still linear 
2. they are still unbiased.
3. but they no longer have minimum variance that is they are no longer efficient. This is so even in large samples. In short, OLS estimators are no longer BLUE in small as well as in large samples. 
4. the usual formula to estimate the variance of OLS estimators are generally biased. A priori we can not tell whether the bias will be positive (upward bias) or negative (downward bias). **A positive bias happens when the OLS overestimates the true variances of the estimators, and a negative bias occurs if OLS underestimates the true variances of the estimates**
5. the bias arises from the fact that $\hat{\sigma}^2$, the conventional estimator of true $\sigma^2$ is no longer an unbiased estimator of $\sigma^2$. 
6. as a result the usual confidence intervals and hypothesis tests based on t and F distributions are unreliable. 