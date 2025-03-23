1. for the time being we concentrate only on the acceptance rate of the schools.
2. suppose we are interested in finding out whether there is a statistical difference in the acceptance rate among 65 schools included in the analysis 
3. for this purpose the schools have been divided into three regions : 1. south, 2 northeast and north central, and west. The qualitative variable here is region. 
4. now we consider the following model : $$ Accept_i = B_1 + B_2D_{2i} + B_3D_{3i} + u_i $$where D2 = 1 if school is in the Northeastern or North Central Region
   = 0 otherwise (in one of the other 2 regions.)
   D3 = 1 if school is in the western region 
   = 0 otherwise (in one of the other 2 regions.)
5. since the qualitative variables region has three classes, we have assigned only two dummies. Here we are treating south as the base or reference category. 
6. we can obtain the mean acceptance rate for schools in the northeastern and north central region : $$ E(S_i|D_{2i} = 1, D_{3i} = 0 ) = B_1 + B_2 $$
7. mean acceptance rate for schools in the western region : $$  E(S_i|D_{2i} = 0, D_{3i} = 1 ) = B_1 + B_3 $$
8. mean acceptance rate for schools in the southern region : $$   E(S_i|D_{2i} = 0, D_{3i} = 0 ) = B_1 $$
9. as this exercise shows, the common intercept B1 represents the mean acceptance rate schools which have been assigned the dummy values of (0,0). 
10. note that the B2 and B3 being the differential intercepts tell us how the mean acceptance rate differs among schools in different regions. 
11. thus, B2 tells us how much the mean acceptance rate of the schools in the northeastern and north central region differ from those in the southern region 
12. and similarly B3 tells us how much the mean acceptance rate of the schools in the western region differ from the schools in southern region. 
13. ![[Pasted image 20250317164113.png]]

### what happens if we consider an ANCOVA model by introducing covariates
1. lets include a quantitative variable such as tuition fee. 
2. ![[Pasted image 20250317164358.png]]
3. at 5% level of significance, there does not appear to be statistical difference in mean acceptance rates between northeastern and north central and southern region 
4. however there is a statistical difference between the mean acceptance rate of southern region and western region 
5. thus not including the covariate led to specification error. 