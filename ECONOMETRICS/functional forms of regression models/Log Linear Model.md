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

> one very attractive feature about Log linear model is that the slope coefficient B2 measures the elasticity of the Y with respect to X, that is the percentage change in Y for a given (small) percentage change in X. 

- symbolically, if we let $\delta{Y}$ stand for a small change in Y and similarly $\delta{X}$ stand for a small change in X, we define the elasticity coefficient, E, as $$ E = \frac{\% change in Y}{\% change in X} $$
- solving this we get the expression $$ E = slope (\frac{X}{Y}) $$
-    thus if Y represents the quantity of a commodity demanded and X represents its unit price, B2 measures the price elasticity of demand. 

###### why is the double log or log linear model also called the constant elasticity model? 
1. since the regression line is a straight line, its slope is constant throughout. 
2. and since its slope coefficient is equal to the elasticity coefficient, for this model, the elasticity is constant throughout. 
3. because of this special feature the log linear model is also called the constant elasticity model. 

