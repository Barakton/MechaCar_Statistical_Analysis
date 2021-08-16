# MechaCar_Statistical_Analysis
The purpose of this weeks challenge is to help solve production issues with the new prototype car. Below are some results of the script we created.

## Linear Regression to Predict
![mpgdeliv1](https://user-images.githubusercontent.com/83259639/129510697-8fa35094-1be7-4278-a4bc-70ad08c5f1b3.PNG)

Here are a few conclusions we can draw from the photo provided above.
- Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
  - It looks like ground clearance and vehicle length provided a non-random amount of variance.
-  Is the slope of the linear model considered to be zero? Why or why not?
  - The slope would actually be non-zero due to our p-value being below .05
-  Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
  - Only 71% of the variability using this model.

## Summary Statistics on Suspension
The following two photographs are here to help visualize the trip analysis

Total Sum - ![total_sum](https://user-images.githubusercontent.com/83259639/129511741-490bfeb4-1ce1-4de7-8fad-70b2e29fbba1.PNG)

Lot Sum - ![lot_sum](https://user-images.githubusercontent.com/83259639/129511766-6e4a4a46-f434-4be9-8d1a-453aa0ca75c0.PNG)

Looking at the above photos we can collect results to the following question

- The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
  - For lots 1 & 2 we can tell that we are under the 100 pounds per square inch (psi) requirement. Lot 3 shows a high amount of variance, so we will have to look at that plant to figure out what is going on.

## T-Tests on Suspension Coils
Here are the t-tests for the following lots.
- All lots
  ![t-test1](https://user-images.githubusercontent.com/83259639/129512115-9ae08bd9-292c-4367-a646-32c593a6fca9.PNG)
- Lot 1
![t-test2](https://user-images.githubusercontent.com/83259639/129512139-a2b97ca2-66ed-4cec-8877-abb6bb7dc822.PNG)
- Lot 2
![t-test3](https://user-images.githubusercontent.com/83259639/129512156-220af8b1-7f84-4af5-8075-d148228571e7.PNG)
- Log 3
![t-test4](https://user-images.githubusercontent.com/83259639/129512169-51cc5812-6b9d-44a9-9af7-83a22271c7ab.PNG)
 
 Here is a brief summary of the above photos:
For all lots, lot 1 & lot 2, they are not statistically different from the population mean. Lot 3 is slightly satistically different.

## Study Design: MechaCar vs Competition
Here are a few things I would like to address

- What metric or metrics are you going to test?
  - Being able to do a crash test to determine overall safety would be a good metric to follow up on and look into.
- What is the null hypothesis or alternative hypothesis?
  - The null hypothesis would be if Mechacars and their competitors have the same safety features, Mechacars overall safety score would be the same or less than their competetors
- What statistical test would you use to test the hypothesis? And why?
  - 
- What data is needed to run the statistical test?
  - frame damage and airbag deployment.
