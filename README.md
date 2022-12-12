# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

<img width="824" alt="Screen Shot 2022-12-11 at 16 16 47" src="https://user-images.githubusercontent.com/111800568/206929900-ff471c0e-b3d3-4ece-97df-7c1cea3c88db.png">

The vehicle length is the most vital contributor to non-random variance, with a p-value of 2.60e-12. The other strong contributor to non-random variance is the ground clearance with a p-value of 5.21e-8. The other factors like vehicle weight, spoiler angle and AWD are not statistically significant.

The slope of the linear model is not zero. We can see that the slope coefficients contain significant non-zero values (vehicle length, ground clearance, and AWD), and the p-values are less than the significance level of p=0.05. The multiple linear regression formula for mpg = -.01 + 6.267*(vehicle length) + .001*(vehicle weight) + .069*(spoiler angle)+3.546*(ground clearance)-3.411*(AWD)

Our r^2 value is 0.7149, which means the model does have good predictive power for the mpg. However, r-squared is one of many considerations for effectiveness. There may be other variables not included in the dataset contributing to the variation in the mpg.

## Summary Statistics on Suspension Coils

<img width="488" alt="Screen Shot 2022-12-11 at 16 53 02" src="https://user-images.githubusercontent.com/111800568/206931234-8d4f6b22-5381-4433-949e-6476f0d5de2d.png">

In the total summary, the variance of all three lots in tandem does fall under the maximum variance of 100 PSI with a variance of 62 PSI.

<img width="511" alt="Screen Shot 2022-12-11 at 16 53 46" src="https://user-images.githubusercontent.com/111800568/206931252-0df055e2-838e-4f7d-95a5-31d05b420b26.png">

The lot summary shows that the major contributor to the variance is lot 3, with a variance of 170 PSI, with the other two lots having 1 and 7.5, respectively.

The manufacturing data meets the maximum variance in PSI requirement, but we can see significant problems in lot 3 with a variance of 170 PSI. Lot 3 does not meet the maximum variance requirement.


## T-Tests on Suspension Coils

<img width="809" alt="Screen Shot 2022-12-11 at 21 09 35" src="https://user-images.githubusercontent.com/111800568/206946523-2dac797c-0e80-4501-b23f-febeb4ab76d9.png">

From our t-test on all the manufacturing lots together, we can see the sample mean is not statistically different from the population mean of 1500 PSI with a p-value of 0.06.


<img width="799" alt="Screen Shot 2022-12-11 at 21 08 59" src="https://user-images.githubusercontent.com/111800568/206946570-fb14ce53-601c-43c8-9429-8f12fece1e21.png">

When we perform t-tests on the individual lots, we can see that lots 1 and 2 are not statistically different from the population mean with p-values of 1 and 0.6, respectively; lot 3 has a mean that is statistically different from the population mean with a p-value of 0.04.


## Study Design: MechaCar vs Competition

The MechaCar can be compared against competition on parameters like cost, city & highway fuel efficiency, horsepower, safety rating, and colour, which are of interest to the consumers.

We will test whether the MechaCar has statistically significant differences in these metrics compared to competing models. The null hypothesis will be that these observables do not vary significantly, and the alternative hypothesis will be that the MechaCar varies significantly in these variables compared to the competition.

Ideally, the consumer would want higher fuel efficiency for city & highway usage, higher horsepower & a better safety rating. The cost of the car needs to be competitive or lower. We will perform one one-tailed t-test to determine if MechaCar has met these required conditions compared to the competition.

In order to run these statistical tests, we would need the cost, fuel efficiency, horsepower, safety rating, and carbon waste output data from MechaCar and competitors.
