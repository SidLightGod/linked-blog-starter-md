# CASE 1: The error variance is proportional to X : Square Root transformation 
![[Pasted image 20250416195211.png]]
1. if after plotting the residuals we see a pattern similar to the one above, the indication is that the error variance is linearly related or proportional to X. 
2. $$ E(u_i^2) = \sigma^2X_i $$
3. which states that the heteroscedastic variance is proportional or linearly related to Xi; the constant true variance is the factor of proportionality. 
4. suppose we transform the model to : 
   ![[Pasted image 20250416195702.png]]
5. the above equation is what is known as the square root transformation.

# CASE 2 : Error variance is proportional to Xi squared 
![[Pasted image 20250416201643.png]]
1. if the estimated residuals show a pattern similar to the one above, it suggests that the errors are not linearly related but increases proportionally to the square of X. $$ E(u_i^2) = \sigma^2X_i^2 $$
2. in this the appropriate transformation of the model is to divide both the sides by X and not the square root of X : 
3. ![[Pasted image 20250416202230.png]]

