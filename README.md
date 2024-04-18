For this project, we used two datasets that track the appointments for patients with asthma in the Chicago area. The data includes each patient's check in date, appointment date, age, zip code, school code, appointment type, school days missed, ER visits, hospitalizations, and ACT scores. ACT scores, also known as Asthma Control Test, range from 0 to 26. The higher the score the better management of asthma symptoms. From the data the main questions we want to answer are what can we learn from the patient demographics, are there any correlations between ACT score and other variables, and does the time of the year have a significant impact on the ACT score? 

From our visualizations and analysis of the given data we are able to see that the clinic treated patients ages 1 - 30 years old, with the bulk of patients ranging between 5 and 17 years old. The clinic saw patients across 94 different zip codes across the Chicagoland area. The majority of patients seen were concentrated within the top 10 zip codes, all located on the South and West sides.

The correlations we focused on are ACT score and number of visits per patient, ACT score and patient age, ACT score and school days missed, and ACT score and medical visits. Starting with ACT score and number of visits, we found that it has a slope of 0.13, and an r-value of 0.12. From this alone, we can see that these two have a positive but weak relationship. The p-value associated with this relationship is 0.000328. This is lower than 0.05, so we can reject the null hypothesis and say that the correlation coefficient is significantly different from zero. So, ACT score and number of visits have a significant correlation. Following the same methodology, ACT score and patient age have a slope of 0.13 and a r-value of 0.15. This signifies a positive but weak relationship. Looking at the p-value, we see that it is 1.27e-05, which is lower than 0.05, so there is a significant correlation. Because both of these relationships are significant and positive, they have the same effect on ACT score. When a patient visits the clinic more or the higher a patient’s age, then the better their ACT score and asthma symptoms. ACT score and school days missed have a slope of -0.32, r-value of -0.25, and a p-value of 2.16e-35. This relationship is negative and somewhat weak, but the correlation is significantly different from zero, so there is a relationship here. With a r-value of -0.25, school days missed have the strongest relationship with ACT score. Lastly, ACT score versus medical visits has a negative and weak relationship with a slope of -0.65 and r-value of -0.17. But once again, with a p-value of 4.99e-17, the correlation is significant. School days missed and medical visits both have a negative effect on ACT score. When a patient misses school more or visits the ER/hospitalized more, the worse their ACT score and the poorer their asthma symptoms are. 

The last question we wanted answered is if the time of the year has an effect on the act score. When examining the average ACT score for each season, we can see that Fall’s mean is 21.54, Winter’s is 21.82, Spring’s is 21.68, and Summer’s is 23.25. We can see from an initial viewing that Fall, Winter, and Spring have pretty similar means, whereas Summer has a slighter higher ACT score. The distributions, which can be seen in the boxplot we provided in our files, show this same idea. The three have similar distributions, Winter having the smallest minimum, but Summer has the largest mean and the smallest range where its values are on the higher end of ACT scores. We also performed a one-way ANOVA. From this test, we received a p-value of 2.7e-09. Because this is lower than 0.05 we can reject the null and say that there is a significant difference between at least two of the seasons. To see which seasons have the significant difference, we performed Tukey’s test. The results of this test show us that the ACT scores in Summer vs. Fall, Summer vs. Winter, and Summer vs. Spring significantly differ from one another. This indicates that during Summer patients have better ACT scores or improved asthma symptoms. 
