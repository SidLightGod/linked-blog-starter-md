- the coefficient of the determination or r^2 measures the goodness of the fit 

##### derivation of the goodness of fit formula 
1. not all ei = Yi - Y^j  are zero some are positive and some are negative. 
2. $$Yi = \hat{Y}i + ei$$
3. $$ Yi - \bar{Y} = (\hat{Y} - \bar{Y}) + (Yi - \hat{Yi})[epsilon]$$
4. the right hand side of the above equation represents the variation in the Yi from its mean value which must be equal to the sum of the variation in Y1 explained by X around its mean and residual variation. 
5. now letting the small letters represent the deviations from mean values we can write the following 
	- $yi = \hat{y}i + ei$
	- to be noted is that the yi = Yi - Y(bar) and since the e bar is 0 it implies that the $\bar{Y} = \bar{\hat{Y}}$
	- this means that the mean values of actual Y and estimated Y are the same or $yi = b2xi + ei$


6. now we get : 
	$$\sum{y^2}i = \sum{\hat{y^2}i} + \sum{e^2}i$$
so we can write this as : 

7. $$ \sum{y^2}i = b^2_2\sum{x^2}_i + \sum{e^2}_i$$

8. the left hand side term can be called the total sum of squares or TSS, which basically means the total variation of the actual Y values about their sample mean, $\bar{Y}$ 

9. the summation of Y bar squared is the total variation of the estimated Y values about their mean value and this is called the explained sum of squares or ESS. The second term on the left hand side, summation of epsilon squared is the **Residual sum of Squares** or RSS 

==This implies that TSS = ESS + RSS==

##### SOME IMPORTANT OBSERVATIONS FROM THE ABOVE RELATION
1. if the SRF fits the data quite well then the ESS should be much larger than the RSS 
2. if all actual Y lie on the fitted SRF, ESS will equal the TSS and RSS will be zero. 
3. on the other hand if the SRF fits the data poorly, then the RSS will be much larger than the ESS. 
4. this implies that if the X explains no variation at all in the Y, ESS will be zero and the TSS will equal RSS. 

so basically, 
$$ r^2 = \frac{ESS}{TSS}$$

**RSS measures the proportion or percentage of the total variation in Y explained by the regression model.**

- the r^2 is a non negative quantity 
- its limits are 0 to 1 since a part (ESS) can not be greater than the whole (TSS). 
- an RSS of 1 implies a perfect fit while an RSS of zero implies no relationship. 

