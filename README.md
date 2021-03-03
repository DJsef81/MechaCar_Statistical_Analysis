# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG
After performing a linear regression on the MechaCar_mpg.csv file, we found that the following variables a non-random amount of variance to the Miles Per Gallon (MPG) values in the dataset. 

* Vehicle Length
* Ground Clearance

The slope of the linear model has a non-zero positive slope provided by the two above factors, shown by Vehicle Length and Ground Clearance beta values of 6.267 and 3.546 respectively and a small p-value for both variables. 

This linear model predicts the MPG of MechaCar prototypes effectively. The r^2 value is 0.7149, with a strong enough coefficient of determination r-value of 0.845, making a good approximation of real world data points. 

### Linear Regression
![](https://github.com/DJsef81/MechaCar_Statistical_Analysis/blob/main/Module%2015%20Challenge%20Images/Linear_Regression_mpg.png)
### Linear Regression Summary 
![](https://github.com/DJsef81/MechaCar_Statistical_Analysis/blob/main/Module%2015%20Challenge%20Images/linear_regression_Summary_mpg.png)

## Summary Statistics on Suspension Coils

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch (PSI). 
Our Total Suspension Coil Summary data shows the variance in regards to the suspension coils overall does no exceed 100 PSI. 

However looking at each individual lot, Lot3 greatly exceeds the 100 PSI variance. They should be rejected. 

### Total Suspension Coil Summary Data
![](https://github.com/DJsef81/MechaCar_Statistical_Analysis/blob/main/Module%2015%20Challenge%20Images/Total%20Suspension%20Coil%20Summary%20Data.png)
### Total Suspension Coil Summary Data by Lot
![](https://github.com/DJsef81/MechaCar_Statistical_Analysis/blob/main/Module%2015%20Challenge%20Images/Total%20Suspension%20Coil%20Summary%20Data%20by%20Lot.png)
## T-Tests on Suspension Coils
summarize your interpretation and findings for the t-test results. Include screenshots of the t-test to support your summary.
### T-Test Entire Set 
![](https://github.com/DJsef81/MechaCar_Statistical_Analysis/blob/main/Module%2015%20Challenge%20Images/TTEST%200.png_)
### T-Test Lot 1
![](https://github.com/DJsef81/MechaCar_Statistical_Analysis/blob/main/Module%2015%20Challenge%20Images/TTEST%201.png)
### T-Test Lot 2
![](https://github.com/DJsef81/MechaCar_Statistical_Analysis/blob/main/Module%2015%20Challenge%20Images/TTEST%202.png)
### T-Test Lot 3
![](https://github.com/DJsef81/MechaCar_Statistical_Analysis/blob/main/Module%2015%20Challenge%20Images/TTEST%203.png)

## Study Design: MechaCar vs Competition

short description of a statistical study that can quantify how the MechaCar performs against the competition. In your study design, think critically about what metrics would be of interest to a consumer: for a few examples, cost, city or highway fuel efficiency, horse power, maintenance cost, or safety rating.
* What metric or metrics are you going to test?
* What is the null hypothesis or alternative hypothesis?
* What statistical test would you use to test the hypothesis? And why?
* What data is needed to run the statistical test?

What makes our MechaCar stands out from the competition, and how can we quantify that?

We've focused on studying many variables that when optimized, can proivde the best MPG for our vehichle. As gasoline prices and commute times have seen steady increases throughout the last two decades, I believe this is an area we should focus on when targeting consumers. It would be ideal to show them not just our MechaCar's performance capabilities, but it's ability to save them on gas compared to our competition. 

To compare with the competition, I believe a Two-Sample T-Test to compare average MPG between two vehicle types would be sufficient. 

A Null Hypothesis would state that the MechaCar has the same MPG efficiency when compared to the competition. 

A alternative hypothesis would state that the MechaCar has a higher MPG efficiency then the competition 

To test these hypotheisis, we would need normal sample sizes for both the MechaCar and the competition (approximately 30-40 cars each), then subjecting both to the same driving tests to gauge and compare MPG. Such tests could include:

* Highway driving at various predetermined times and speeds 
* Street driving for various predetermined times/routes. 
* Uphill driving 
* Driving with varying degrees of added weight in the car. 

After collecting our test data we can compare the results and make our assesments, either verifying our hypothesis or necessitating a new comparison hypothesis. 
