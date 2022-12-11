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


