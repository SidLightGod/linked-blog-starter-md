1. the technique of dummy variable can be extended to handle more than one qualitative variable. Consider the following model 
2. $$ Y_i = B_i + B_2D_{2i} + B_3D_{3i} + B_4X_i + u_i $$ where Y = hourly wage in dollars 
   X = education 
   D2 = 1 if female and 0 if male 
   D3 = 1 if non white and non hispanic, 0 if otherwise 
3. in this model sex and race are qualitative variable and education is a quantitative explanatory variable. The following is the result 
4. ![[Pasted image 20250318214717.png]]
5. the base category is white hispanic male. second on average keeping the level of education and race constant, on average, women earn less than men by about 2.36 dollar per hour. 
6. similarly the non white / non hispanic earn less than the base category, holding the level of education constant, by about 1.7327 
7. third holding sex and race constant mean hourly wages go up by about 80% for every additional year of education. 

### Interaction Effects 
1. implicit in the equation is the assumption that the differential effect of the sex dummy D2 is constant across two categories of race and the differential effect of the race dummy D3 is constant across the two sexes. 
2. that is to say if the mean wage of male is higher than female, it is whether they are hispanic or not. 
3. likewise if non white or non hispanic have a lower mean wage, this is so regardless of the sex
4. there may be interactions between the qualitative variables and therefore their effect on the mean Y may not be simply additive but may be multiplicative as well, as in the following model 
5. $$ Y_i = B_1 + B_2D_{2i} + B_3D_{3i} + B_3(D_{2i}D_{3i}) + B_4X_i + u $$ the dummy D2iD3i, the product of two dummies, is called the interaction dummy, for it gives the joint or simultaneous, effect of two qualitative variables 
6. from the equation we can obtain 
   ![[Pasted image 20250318230745.png]]
   which is the hourly wage function for female non white non hispanic workers
7. ![[Pasted image 20250318230844.png]]
8. ![[Pasted image 20250318230905.png]]
9. 