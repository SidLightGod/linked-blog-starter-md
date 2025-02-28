let us consider the case of SAT scores. The model we are considering for the SAT scores is $$ Y_i = AX_i^{B_2} $$
- here Y is the SAT scores and X is the annual family income. 
- this model is non linear in variable $X^2$ 
- we can however represent this equation in the so called log linear form : $$ lnY_i = lnA + B_2lnX_i $$
- if we let $B_1 = lnA$ then we can write the above equation as : $$ lnY_i = B_1 + B_2lnX_i + u_i $$

###### why is this model also called double log model 
1. the log linear model is a linear regression model, for the parameters in the model enter linearly. 
2. it is of interest that the model is also linear in the logarithms of the variables. 
3. and because of these reasons it is also called the double log model. 

- now letting $Y_i^* = lnY_i$ and $X_i^* = lnX_i$ 
- so we can write the equation as following :   $$Y_i^* = B_1 + B_2X_i^* + u_i $$
- since the OLS assumptions are satisfied we can easily estimate it with the ordinary least squares (OLS)