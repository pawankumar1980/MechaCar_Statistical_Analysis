# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

<img width="824" alt="Screen Shot 2022-12-11 at 16 16 47" src="https://user-images.githubusercontent.com/111800568/206929900-ff471c0e-b3d3-4ece-97df-7c1cea3c88db.png">

The vehicle length is the most vital contributor to non-random variance, with a p-value of 2.60e-12. The other strong contributor to non-random variance is the ground clearance with a p-value of 5.21e-8. The other factors like vehicle weight, spoiler angle and AWD are not statistically significant.

The slope of the linear model is not zero. We can see that the slope coefficients contain significant non-zero values (vehicle length, ground clearance, and AWD), and the p-values are less than the significance level of p=0.05. The multiple linear regression formula for mpg = -.01 + 6.267*(vehicle length) + .001*(vehicle weight) + .069*(spoiler angle)+3.546*(ground clearance)-3.411*(AWD)

Our r^2 value is 0.7149, which means the model does have good predictive power for the mpg. However, r-squared is one of many considerations for effectiveness. There may be other variables not included in the dataset contributing to the variation in the mpg.

