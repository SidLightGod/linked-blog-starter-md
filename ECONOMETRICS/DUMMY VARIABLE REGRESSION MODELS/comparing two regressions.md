consider the model $$ Y_i = B_1 + B_2D_1 + B_3X_i + B_4(D_iX_i) + u_i $$
1. we have added an extra DiXi 
2. the mean food expenditure, males : $$ E(Y_i|D = 0, X_i) = B_1 + B_3X_i $$
3. mean food expenditure, females : $$ E(Y_i|D = 1, X_i) = (B_1 + B_2D_i) + (B_3 + B_4D_i)X_i $$ => $$ (B_1 + B_2) + (B_3 + B_4)X_i $$
4. Just as we called $B_2$ the differential intercept coefficient, we can now call $B_4$ the differential slope coefficient, also called the slope drifter.
5. the B3 + B4 gives the slope coefficient of the income variable when for the category that receives the dummy value of 1. 
6. the introduction of the dummy variable in the additive form enables us to distinguish between the intercept coefficients of the two groups and the introduction of the dummy variable in interactive, or multiplicative, form enables us to distinguish between the slope coefficients of the two groups. 

![[Pasted image 20250322130748.png]]
1. if the figure shows that there is no difference between the slope and intercept coefficient, that is the regressions are identical then it is the case of coincidental regressions. 
2. if the figure shows that the two slope coefficients are the same but the intercepts are different. This is the case of parallel regressions. 
3. if the figure shows that the two regressions have the same intercept but different slopes, it is the case of concurrent regressions. 
4. if the figure shows that both the intercept and the slope coefficients are different, it is the case of dissimilar regressions. 
5. 