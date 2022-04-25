# MechaCar_Statisical_Analysis

## Overview
### AutosRUs newly developed MechaCar is dealing with some production troubles which is not allowing progress.  Enter Jeremy, the data analytic leader to save the day!

The goal of the project:
* Perform linear regression on the given data to predict the the MPG of the new prototype.  
* Collect the total summary stats from the dataframe to get the mean, median, mode and standard deviation on the PSI of the suspension coils from different lots.
* Run T-Tests to determine if the PSI for each manufacturing lot is statistically different from the population mean of 1,500 pounds per square inch.
* Create and design study to compare the performances of the Mechacar compared to competition.

## Linear Regression to Predict MPG

![Deliverable 1 Picture](https://user-images.githubusercontent.com/95198079/165012948-0f3c2630-6bf6-4ead-8b48-ea97eacd5a4b.png)

* The most significant variables in our dataset which show a non-random effect on the MPG of the MechaCar are the Vehicle Length and the Ground Clearance. Looking at the above photo,spefically at vehicle length and ground clearance, a linear regression model run on these variables against figures for MPG, resulted in p-values of 2.6x10-12 and 5.21x10-8. The intercept was also statistically higher, which means there may be other factors involved, not included in our dataset that could affect MPG. 
* The slope of the linear model is not considered to be zero. The p-value in the photo is deems to be very insignificant.  The relationship between the variables and the MPG appears to be subject to more than random chance.
* Finally, the linear model does predict the MPG of the new prototype with positive effectiveness.  The r-squared gives us a 70+% accuracy rating so it appears to be more than random.  

## Summary Statistics on Suspension Coils

![Suspension Coil stats](https://user-images.githubusercontent.com/95198079/165014298-c0c70681-5483-4fd8-8eec-05a452a8f948.png)


## T-Tests on Suspension Coils
### Suspension coils overall T-Test
![T Test Sample](https://user-images.githubusercontent.com/95198079/165014698-8528e8fd-d67d-4e37-8880-3498a20a3149.png)

Lot 1 T-Test

![T Test lot 1](https://user-images.githubusercontent.com/95198079/165014737-58ba085d-4bfd-4b30-b36f-e6e9979815a9.png)

These results show the suspension coils for Lot 1 are not too different from the population mean.  The p-value isn't low enough to reject the null hypothesis. 

Lot 2 T-Test

![T Test Lot 2](https://user-images.githubusercontent.com/95198079/165014856-cba7ae97-c971-4451-87e3-17ecb85d38e8.png)

Lot 2 shows these are also not too different statiscally from the population mean, also the p-value is not low enough to reject the null hypothesis as well.


Lot 3 T-Test

![T Test Lot 3](https://user-images.githubusercontent.com/95198079/165014903-66290243-7dc8-48c2-bc67-e54df5f80f2c.png)

Our first difference off of the population mean statistically.  This p-value is also low enough to reject the null hypothesis.

## Study Design: MechaCar vs Competition

The MechaCar needs to perform better than the average vehicle, in order to do this, focus must be put on improving the fuel efficiency.  Data can be gathered from different locations where weather may affect driving, also rural vs suburban as well.  The distance traveled of trips could help determine the fuel efficiency a little better.  With this data, it must constantly be compared to rival companies to see where it lines up.  

Metrics being tested:
* Large efficient data
* Variance in said data

What is the null hypothesis or alternative hypothesis?
HO: No statistical  difference
Ha:MechaCar has a greater mean than competitive companies MPG.

This data can be found using t-tests. 

The data needed would be to gather cubic space data from Mechacar prototypes and also comparable competitor vehicles.  




