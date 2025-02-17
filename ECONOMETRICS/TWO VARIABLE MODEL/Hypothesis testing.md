- let us consider the case of SAT scores, and suppose someone suggests that there is no relation between income and the SAT scores. 
- then this would imply that the null hypothesis is Ho : B2 = 0, implying that the slope coefficient is zero, therefore no relation between the income and the scores. 
- if the zero null hypothesis is sustainable then it would not make sense to include X in the model
- therefore if X is fully expected to be included in the model, the null hypothesis has to be expected to be rejected in favor of the alternate hypothesis that is B2 =/= 0. 

### hypothesis testing procedure: a brief recap 
![[Pasted image 20250127214206.png]]
this is the formula for the z value where the se (b2) is sigma divided by summation of x1^2
the degree of freedom is given by n - 2 

### the confidence interval approach 

so we need to basically check whether B2 is within the confidence interval. 
the confidence interval can be found by : 
	( b2 - t*. se( b2 ), b2 + t*. se(b2) )
	where the t* is the value for confidence level alpha at a certain degree of freedom. 
note : we will accept the null hypothesis if its within the confidence interval and reject it, if its outside the confidence interval. 

### the t- test procedure 

so we need to use the t test for this one. we find the t value using the formula for t value which is already given above 
	if the absolute value of the t is less than the t value at alpha(critical t value), then we accept the null hypothesis otherwise we reject it 