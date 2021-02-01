# MechaCar_Statistical_Analysis
Performing statistical analysis on vehicle data through using linear regression models and t-tests on vehicle prdouction metrics. 


### Signifincace level 
0.05

## Linear Regression to Predict MPG
Based on the multiple linear regression model, three of the six variables provided for the model have coefficients indicating they provide a non-random amount of variance to mpg values in the dataet. These three variables are the intercept itself(mpg), vehicle length and ground clearance. 

The slope of the linear model should not be considered zero since there is sufficient evidence. With a p-value much smaller than the asumed signicance level of 0.05%.

Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
The linear shows to predict mpg of MechaChar effectivly, having a r-squared value of 0.71 menaing a 70% of all mpg predictions will be correct when using this linear model. 


### Summary Statistics on Suspension Coils 
> The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch.

Based on the summary statistics, Lot 3 exceeds the allowed variation threshold while Lot 1 and 2 are within the allowed margin. collectivly the 3 lots are within the allowed variancce, which is 62.

## T-Tests on Suspension Coils

#### Overall T-Test 
p-value of 4.938 sufficient evidence showing PSI accross all manufacturing lots is not statistically differnt from the population mean.

#### Manufactuering Lot 1 T-Test 
p-value shows signigincatn evidence that lot 1 is statisitcally similiar to the population mean of 1,500 PSI.

#### Manufactuering Lot 2 T-Test 
p-value shows signigincatn evidence that lot 2 is statisitcally similiar to the population mean of 1,500 PSI.

#### Manufactuering Lot 3 T-Test 
p-value does not show signigincatn evidence that lot 3 is statisitcally different from te population mean of 1,500 PSI.

## Study Design: MechaCar vs Competition

With the above statistical models and testing it would be possible to analyze production metrics of other vehicles and lots. 
Having relivily similiar data would for vehicles would allow comparison between MechaCars production and its competition. 
Such data shoudl include vehicle production and performance specifications.
Many metrics could be tested to identify vehicle performance including miles per gallon, car weight, and other physical features that relate to performance. 

### hypotheses 
In order to properly test and build models a null and alternative hypthesis is needed:

- Null Hypothesis 
  

- Alternate Hypothesis 

### Testing 
Similiar multiple linear regression models and t-tests could be used on the vehicle data with a signifincae level of 0.05%.
