1. frequently in regression analysis the dependent variable is influenced not only by the variables that can be quantified on some well defined scale but also by the variables that are basically qualitative in nature. 
2. such qualitative variables usually indicate the absence or presence of a quality or an attribute. 
3. one method of quantifying these variables is by constructing artificial variables that take on values of 0 and 1 
4. 0 indicating the absence of an attribute and 1 indicating the presence of an attribute. 
5. for example 1 may indicate the person is a female while 0 may designate a male. 
6. variables that assume values such as 0 or 1 are known as dummy variables. 
7. we denote the dummy explanatory variables with the letter D instead of X. 

> a regression models which contains only dummy variables are called analysis of variance (ANOVA) models. 

$$ Y_i = B_1 + B_2D_i + u_i $$
where Y is the annual expenditure on food ($) 
$D_i$ = 1 , if female 
	= 0, if male 

#### Now lets see the mean food expenditure of males, 
$$ E(Y_i|D_i = 0) = B_1 + B_2(0) $$
=> $$  E(Y_i|D_i = 0) = B_1 $$ 
#### Now lets see the mean food expenditure of females 

 $$ E(Y_i|D_i = 1) = B_1 + B_2(1) $$
 => $$ E(Y_i|D_i = 1) = B_1 + B_2 $$ 
> from this we see that the B1 gives the mean food expenditure of males while the slope coefficient B2 tells us how much the mean food expenditure of females differ from males and B1 + B2 gives us the mean food expenditure of females. 

> **since the dummy variables take the values 0 and 1, it is not legitimate to call B2 the slope coefficient here, it is better to call it the differential intercept coefficient, because it tells us how much the value of the intercept term differs between two categories.** 

- WE CALL THE CATEGORY THAT GETS THE VALUE OF ZERO, THE BASE, OR REFERENCE, OR BENCHMARK, OR COMPARISON CATEGORY. 
- basically these dummy variables operate in similar fashion as the boolean values in programming. 

#### Dummy Variable Trap

> the dummy variable trap arises in the regression model when there is perfect multicollinearity due to inclusion of too many dummy variables. 

- lets say we have k categories and run a regression for k dummy variables then they will be linearly dependent 
- this causes perfect multicollinearity, making the regression model unstable. 
- so to avoid this trap we must run the regression with k - 1 dummy variables 

> the regression models consisting of both qualitative variables and quantitative variables are called the analysis of covariance models. or ANCOVA model 

> the ANCOVA models are an extension of the ANOVA model in the sense that they provide a method of statistically controlling the effect of quantitative variables called the covariates or control variables in a model that includes both the quantitative variables and dummy variables or qualitative variables, explanatory variables. 

