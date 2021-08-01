The purpose of this challenge was to assess the various parameters of MechaCar data through usage of RStudio. We performed various statistical tests to determine statistical significance of multiple variables.

## Deliverable 1: Linear regression to predict mpg


<img width="803" alt="Deliverable1" src="https://user-images.githubusercontent.com/82029390/127777810-30e3e189-b0d0-4585-b622-bbf58061bcac.png">


As seen in the screenshot above, the three variables with amounts of variance greater than the p-value of 5.35 x 10^-11 are the y intercept, vehicle length, and ground clearance relative to the mpg. These variables thus significantly impact our mpg. 
Our linear regression generated a p-value of 5.35 x10^-11 which is much smaller than our assumed significance level of 0.05% and we can thus state that there is sufficient evidence to reject our null hypothesis which tells us that the slope of our linear model is NOT zero.
This linear model does effectively predict mpg of our MechaCar prototypes because our r-squared value suggests that approximately 72% of mpg predictions will be relatively accurate if we use this model. 

## Deliverable 2: Summary Statistics on suspension coils


<img width="596" alt="AllLots" src="https://user-images.githubusercontent.com/82029390/127777900-607b3e3a-7669-4cdc-9978-c729be23ab86.png">

<img width="343" alt="LotTotal" src="https://user-images.githubusercontent.com/82029390/127777909-30797987-e9be-4cc3-b474-b2f236800c2c.png">

The total variance would suggest that the variance of the suspension coils does not exceed 100 pounds per square inch with a value of 62.3. However upon examining the variance for each individual lot, it becomes evident that Lot 3 has a variance that does in fact exceed 100 pounds per square inch with a value of 170.286.


## Deliverable 3: t-test on Suspension coils

<img width="808" alt="Deliverable3" src="https://user-images.githubusercontent.com/82029390/127777924-2e9ef388-f160-49a9-adeb-4d2557b0d86c.png">

<img width="802" alt="Lots123" src="https://user-images.githubusercontent.com/82029390/127777947-e5a79fb3-8d6f-4880-8af0-ec65b9ec9b81.png">

Our t-test generated a p-value of .06028 which is greater than our assumed significance level of .05. We can thus assume that these two means are statistically similar. 

Lot1: We have a p-value of 1 which is greater than our significance level and can thus assume the two means are statistically similar.

Lot 2: Lot 2’s p-value of .6 is still greater than our significance level of .05 and we can assume the two means are statistically similar. 

Lot 3: The p-value is .04 and smaller than our significance level of .05 and we can therefore assume that the two means are NOT statistically similar. 



## Deliverable 4: Design a study comparing the MechaCar to the Competition 


