# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG
![Deliverable 1 Console](https://user-images.githubusercontent.com/92186586/194159111-7e6bbd44-a025-4581-9724-1dd353f05fcc.png)

From the outcome above we see that the data seems to fit in normally. The minimum is -19.4702 and the max is 18.5849. We also see that the median is -0.0697 which is almost perfectly inbetween the min and max.

1. Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
   For this,we reference the P-Value and see that it is within the 95%. Meaning that it is below 0.05 significance.
   
2. Is the slope of the linear model considered to be zero? Why or why not?
  To answer this we reference the formula used for MPG. As we can take a look at the coefficients output 
  and notice that the outcome is not 0. 
  
3. Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
  We can look at the r squared value and see that it's at .7149. This would indicate a strong correlation and          result in a rather effective method.
  
  ## Summary Statistics on Suspension Coils

Attached below is the summary statistics and lot summary statistics of the suspension coil data. 
![Lot Summary](https://user-images.githubusercontent.com/92186586/194161056-23db77a8-4dd3-4f37-9468-454e88d2bb99.png)

![total Summary](https://user-images.githubusercontent.com/92186586/194161117-24df11cd-7736-4276-a82e-ce79ac9505fe.png)

Summary 
From these two images we see that the means are all very close to one another at 1500, in both total summary and lot summaries. The medians are at that same range as well. 

1. The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

The total does meet the requirements because it is at 62, which is less than 100. Howvere, in the lots, we can see that lot 3 has variance over 100 at 170. Since lot 3 has such high varience, it has also made the overall total varience high. 

## T-Tests on Suspension Coils

Attached Below is the output of t-tests.
#One Sample
![One Sample](https://user-images.githubusercontent.com/92186586/194162657-5b1740cd-3e7a-4819-bbee-1c40d93c5c37.png)

As we can see from the output above, the mean falls in the 95% confidence interval. P-Value is greated than alpha. This would form a normal distribution graph. 

#lot 1
![Lot 1](https://user-images.githubusercontent.com/92186586/194162693-61d4abd6-371f-4d5e-ba98-a54c759e0b63.png)
The mean for this also falls within the 95% confidence interval. P value is significantly greater than alpha. 

#lot 2
![Lot 2](https://user-images.githubusercontent.com/92186586/194162719-252c710d-d9e1-40e3-8336-83b19ee2341f.png)
we see that P value is greater than alpha at 0.05. The mean would also fall in the 95% confidence interval.

#lot 3
![Lot 3](https://user-images.githubusercontent.com/92186586/194162743-30dc0dba-6635-4962-bad7-a51de3300325.png)
Once again the mean falls within the 95%. However, since P value is less than alpha, we cannot assume that it'll be normal distribution.



