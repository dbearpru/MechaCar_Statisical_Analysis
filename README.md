# MechaCar_Statisical_Analysis

# Deliverable 1


1. Vehicle length and vehicle ground clearance are statistcally likely to be non-randon amounts of variance both would have an impact on miles per gallon.
The opposite is true to vehicle weight, spoiler angle, and All Wheel Drive. There p-Values show a random amount of variance with the dataset. 

2. The p-Value is much smaller at 5.35e-11 than the assumed significance level of .005%. Therefore we should reject the null hypothesis which means our slope is not zero.

3. The linear model has an r-squared value of .7149 or about 71% of mpg predictions will be determined by the model. The regression model is not a good predictor of mpg of MechaCar Prototypes.


![Screen Shot 2022-06-18 at 11 03 32 AM](https://user-images.githubusercontent.com/90650209/174444313-737bcf1a-7718-4a2e-965e-dcc435f91aea.png)



![Screen Shot 2022-06-18 at 11 04 12 AM](https://user-images.githubusercontent.com/90650209/174444329-0c13926b-005c-476e-afbd-468138c3e672.png)

 
 

# Deliverable 2


We see in the tables below that the Variance in PSI for the whole of the 3 lots is 62.29. Within the 100 psi limit that we are given.

![Screen Shot 2022-06-18 at 11 06 22 AM](https://user-images.githubusercontent.com/90650209/174444464-c394e5db-1799-4f78-9908-3a4657218e55.png)

When we drill down into specific lots we see .98 variance and 7.47 variance in lots one and two resepectiviley. We end up seeing that the varaiance is 170.29 for the third lot which is skewing our data. We should probably figure out why the variance is so much higher in lot 3. 



![Screen Shot 2022-06-18 at 11 05 35 AM](https://user-images.githubusercontent.com/90650209/174444429-085ad08a-f6fa-4b36-b0c1-969f50a6bc09.png)


# Deliverable 3



![Screen Shot 2022-06-18 at 11 08 20 AM](https://user-images.githubusercontent.com/90650209/174444530-b853a20e-d2e0-4b86-a564-546f30c98453.png)

When reviewing all of the lots we see that they are not statistically different from the population mean and the p-value is not small enough for us to reject the null hypothesis.

![Screen Shot 2022-06-18 at 11 08 46 AM](https://user-images.githubusercontent.com/90650209/174444621-d83c875b-b060-4083-8bad-4f2edc16f0b2.png)

When reviewing lot 1 we see it is not statiscally different from the population mean and that the p-value at 1 is not low enough to reject the null hypothesis. 

![Screen Shot 2022-06-18 at 11 09 46 AM](https://user-images.githubusercontent.com/90650209/174444646-eea0d10a-1348-44de-b945-df54500469f8.png)

When reviewing lot 2 we see it is not statiscally different from the population mean and that the p-value at .607 is not low enough to reject the null hypothesis. 

![Screen Shot 2022-06-18 at 11 10 16 AM](https://user-images.githubusercontent.com/90650209/174444674-0798dd14-a968-4544-879d-486afc016401.png)

When reviewing lot 3 we see it is statiscally different from the population mean and that the p-value at .0417 is not low enough to reject the null hypothesis. This lot should be more closely evulated. 

# Deliverable 4

# Study Design MechaCar vs. Competition 


1. We are going to test the safety rating of MechaCars. Consumers are very concerned by safety.

2. We will make our null hypothesis that is a safety rating of zero and an alternativ ehypothesis that the mean is not zero.

3. We will use linear regression summaries to show how variables either impact or don't impact safety vs. competitors.

4. We will need the safety rating of various cars and there features and dimensions to determine the safety ratings. 


