###### are there any guidelines or rules of thumb that can be followed while choosing among competing models? 
1. one guiding principle is to simply plot the data. If the scattergram shows that the relationship between two variables look reasonably linear, the linear specification might be appropriate. 
2. but if the scattergram does not show a linear relationship between the two variables, then taking the log of the dependent and the independent variable and then plotting its scatterplot, and checking if it follows a linear relationship, if it does, then it would imply that a log linear model would be appropriate.
3. factors such as the relevance of the explanatory variables included in the model, the expected sign coefficient of the explanatory variables, their statistical significance and certain derived measures like elasticity coefficient. 

###### the problems with choosing a model based on the r squared, that is the model with the highest r square? 
1. to compare the r square of the two models, the dependent variable needs to be of the same form. 
2. r square measures the proportion of variation in the dependent variable explained by the explanatory variable.
3. in the linear model therefore, the r square measures proportion of variation in Y explained by X. whereas in the case of log linear model, the r square measures the variation in the log of Y explained by the log of X. 
4. the variation in Y and the variation in log of Y are two different things conceptually. 
> the variation in the log of a number measures the relative or the proportional change and the variation in the a number measures the absolute change. 

5. it is not a great idea to choose a model based on a higher r square value as r square can always be increased by adding more explanatory variables to the model. 