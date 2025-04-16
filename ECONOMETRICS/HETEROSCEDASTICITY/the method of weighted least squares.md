1. this is a method which is viable when the $\sigma^2$ is known.
2. consider the two variable PRF $$ Y_i = B_1 + B_2X_i + u_i $$
3. assuming that the true error variance is known that is the error variance of each of the observation is known. 
4. Now consider the following transformation of the model $$ \frac{Y_i}{\sigma_i} = B_1\frac{1}{\sigma_i} + B_2\frac{X_i}{\sigma_i} + \frac{u_i}{\sigma_i} $$
5. all we have done is divide both the right hand side of the equation and the left hand side of the equation by the known $\sigma_{i}$, 
6. now let $\frac{u_i}{\sigma_i} = u_i$, and similarly we can also get $$ \frac{v_i^2}{\sigma_i^2} = v_i^2 $$
7.  $$  E(\frac{v_i^2}{\sigma_i^2}) = E(v_i^2)  $$
8. and since the $\sigma_i^2$ is known the above equation reduces to 1, which is obviously a constant. In other words, the transformed error term is homoscedastic. 