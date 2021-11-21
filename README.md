# MechaCar_Statistical_Analysis
## Purpose
The goal of this challenge was to use R to discover which variables predict the MPG for vehicle prototypes,
collect summary statistics on the PSI of suspension coils,
determine if manufacturing lots are statistically different from the mean population, and finally 
design a study to compare the MechaCar performance against vehicles from other manufacturers.
## Linear Regression to Predict MPG
![Deliverable1](https://user-images.githubusercontent.com/87148177/142712416-e553176d-e149-43c8-bbe7-c820be983db0.png)\
-The variables in our dataset that show a non-random effect on the MPG of the MechaCar are the Vehicle Length and the Ground Clearance. A linear regression model run on these variables against figures for MPG, resulted in p-values of 2.6x10-12 and 5.21x10-8, respectively. In addition, the intercept was also statistically significant.\
-The slope of the linear model can not be considered zero as the p-value of 5.35x10-11 is lower than even an extreme level of significance. Because of this, the null hypothesis must be rejected. This means that the relationship between our variables and the miles per gallon is subject to more than random chance.\
-Although there are other factors, this model does predict the mpg of the MechaCar prototype with relative effectiveness. The r-squared value of 0.7149 indicates that the model is 71% accurate.
## Summary Statistics on Suspension Coils
![total_summary](https://user-images.githubusercontent.com/87148177/142712436-ceebd8f8-82ac-431f-b1d4-834dbe5dcb0a.png)\
![lot_summary](https://user-images.githubusercontent.com/87148177/142712438-2c024cd2-cebf-44aa-b2cf-40275c75fb4a.png)\
While the overall variance is under 100 psi and meets specifications, the variance for lot 3 is well over the threshold at 170.28.
## T-Test Results
![coil_T_test](https://user-images.githubusercontent.com/87148177/142712464-9f1457b8-a74e-4b2b-9902-8628f1343f3b.png)\
A review of the results of the T-test for the suspension coils across all manufacturing lots shows that they are not statistically different from the population mean, and the p-value is not low enough (0.0603) for us to reject the null hypothesis.\
![T_tests](https://user-images.githubusercontent.com/87148177/142712466-41a2d8ae-cc26-4b4e-8e29-20942e096ec0.png)\
-A review of the results of the T-test for the suspension coils for Lot 1 shows that they are not statistically different from the population mean, and the p-value is not low enough (1) for us to reject the null hypothesis.
## Study Design: Mechacar vs Competition
