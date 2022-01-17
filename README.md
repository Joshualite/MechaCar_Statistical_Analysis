# MechaCar_Statistical_Analysis



## Linear Regression to Predict MPG

![image](https://user-images.githubusercontent.com/66183125/148712429-8722dc76-0b0d-4a3b-8550-b547c74731fd.png)

- The variables vehicle_length and ground_clearance are statistically unlikely to provide random amounts of variance to the linear model, the probability is very low such as it shows their values.

 Vehicle_length: 2.60e-12
 Ground_clearance:5.21e-08

- According to the values that we have within our p-value , we have enough evidence to be able to reject the null hypothesis, so our slope cannot be zero and it also shows us that there is a relationship between our independent variables and our dependent variable

p-value :5.35e-11

-  According to the value shown by our squared r, we have a good level of significance, it may not be perfect but to a large extent our variables explain the model
R2: 0.7149


## Summary Statistics on Suspension Coils

![image](https://user-images.githubusercontent.com/66183125/148713782-55e5c2f9-351d-47fb-835c-39279b636eae.png)

![image](https://user-images.githubusercontent.com/66183125/148713722-6ed559fc-95af-4ee2-a3d0-e1031f8a35c2.png)

In this section, two statistical summaries were created, one general and the other per batch, where we are asked to review a condition regarding the value of the variance of suspension coils, which must not exceed 100 pounds per square inch. If we review our image, we can see that in the general statistical summary and in batches 1 and 2 the specifications are met, but we have a problem with batch number 3 since it exceeds the variance of 100 with a total value of 170, so this could cause us a problem.

## T-Tests on Suspension Coils
For the t test analysis we want to determine if all manufacturing lots and each lot individually are statistically different from the population mean of 1,500 pounds per square inch.

![image](https://user-images.githubusercontent.com/66183125/149683065-13d77343-1d18-4c01-8676-3e5fa8b57e76.png)

In the first t-test analysis where we take all the lots, there is no statistical difference between its mean and the population mean, this is because the p-value is .06, so there is not enough evidence to reject the null hypothesis

Lot1
![image](https://user-images.githubusercontent.com/66183125/149683971-70e2c7c0-5de6-4340-9b05-b263dce23d82.png)

 the t-test analysis where we take only the first lot, there is no statistical difference between its mean and the population mean, this is because the p-value is 1, so there is not enough evidence to reject the null hypothesis 


Lot2
![image](https://user-images.githubusercontent.com/66183125/149683999-38458849-2f28-4c84-b85a-ece066f384e6.png)
the t-test analysis where we take the second lot, there is no statistical difference between its mean and the population mean, this is because the p-value is .60, so there is not enough evidence to reject the  null hypothesis.

Lot3
![image](https://user-images.githubusercontent.com/66183125/149684018-f3fff90c-c1f9-4abc-9a16-ec44d519b924.png)

the t-test analysis where we take the third lot, there is  statistical difference between its mean and the population mean, this is because the p-value is .04, so there is  enough evidence to reject the  null hypothesis.


