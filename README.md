# MechaCar Statistical Analysis

Deliverable 1
## Linear Regression to Predict MPG

![lm() function](https://user-images.githubusercontent.com/107904664/195490914-9860427c-3bb9-4c6b-9dff-09a09d3c00be.png)

RESULTS:
* The variables/coefficients vehicle length and ground clearance provided a non-random amount of variance to the mpg values in the dataset
* The p-value for this model is 5.35e-11. This is much smaller than the assumed level of 0.05%, hence this indicates this is sufficient to reject our null hypothesis.   this concludes that the slope of the linear model is not considered to be zero.
* This linear model predict that it has an r-squared value of 0.7149.This is approximately 71% of all mpg predictions which is determined by this model, which infers     multiple regression model does predict mpg of MechaCar prototypes effectively.


Deliverable 2:

## Summary Statistics on Suspension Coils
   The Suspension Coil dataset provided for the MechaCar contains the results of testing the weight capacities of multiple suspension coils from multiple production lots to determine consistency.

![Lot_summary](https://user-images.githubusercontent.com/107904664/195493000-ec273923-8b40-43cd-91fb-341148d41ca3.png)


![total_summary](https://user-images.githubusercontent.com/107904664/195492970-d6eff9af-c99d-430c-9117-6e3c8f6ac875.png)

  * The design specifications for the MechaCar suspension coils indicate that the variance of the suspension coils must not exceed 100 pounds per square inch.
  
  * Also, we get from the above results that the entire population of the production lot ,variance is 62.29 that is well withinthe 100 PSI. So, current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually.
  * 
Deliverable 3 
## T-Tests on Suspension Coils

Performed t-tests to determine if all manufacturing lots and each lot individually are statistically different from the population mean of 1,500 pounds per square inch.
Below are the sample t-tests values for the lots

![One sample t-test and lot 1 t-test](https://user-images.githubusercontent.com/107904664/195494418-ffb200a7-eea8-42ae-81cb-a7bbb87cd8a3.png)

![lot 2 and  3 t-test](https://user-images.githubusercontent.com/107904664/195494474-6652ed08-67da-4ce3-ac24-6dca49a34246.png)


Lot 3 production cycle, something is not good. Hence the process should be tested for the system failure and the suspension coil must be inspected for the quality.

Deliverable 4
 ## Study Design: MechaCar vs Competition

The statistical study design has the following:
 *A metric to be tested is mentioned
 *A null hypothesis or an alternative hypothesis is described 
 *A statistical test is described to test the hypothesis 
 
 Comparing the similar models across all the manufacturers , we collect the following metrics
 
 Independent Variables:
 The independent variables are Drive Package, Engine (Electric, Hybrid, Gasoline / Conventional), Safety Feature Rating, Average Annual Cost of ownership (Maintenance), MPG (Gasoline Efficiency) and Resale Value.
The only dependent variable is the current (selling) price.

Null and Alternative Hypothesis:
MechaCar is priced correctly on its performance of key factors for its genre, this is Null Hypothesis.
Mecha car is not priced correctly based on performance of key factors for its genre, this is Alternative Hypothesis.

From the results above, we can conclude that the selling price is most dependent which is to be considered for the higher impact.

