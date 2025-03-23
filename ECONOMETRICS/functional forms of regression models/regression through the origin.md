the form it takes is the following 
$$ Y_i = B_2X_i + u_i $$
1. in this model the intercept is zero or absent hence the name, regression through origin 
2. $$ b_2 = \frac{\sum{X_iY_i}}{\sum{X_i^2}} $$
3. $$ var(b_2) = \frac{\sigma^2}{\sum{X_i^2}} $$

###### comparing the formulae in no intercept model and intercept model 
1. first in the model without intercept we use raw sums of squares and cross products. 
2. whereas in the intercept present model we use mean adjusted sums of squares and cross products 
3. second the degree of freedom in computing $\hat{\sigma}^2$ is now n - 1 rather than n - 2, we have only one unknown. 
4. third the conventionally computed r squared assumes that the model has an intercept term 
5. there that formula should not be used, because it may provide non sensical solutions at times, because the computed r square may turn out to be negative. 
6. finally in the model with the intercept the sum of estimated residuals is always zero but this may not be the case for the model without the intercept. 
7. for all these reasons, one may use the zero intercept model only when there is a strong theoretical reason for it, like Okun's law or some areas of economics and finance. 