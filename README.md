Challenge 15 -- R Statistics and MechaCar

## Study Design: MechaCar vs Competition

Mechacar, an auto manufuacturing company is looking for ways to improve their products fuel mileage.  We have decided to use statistics as a way to better understand how we can improve our cars performance by changing the cars characteristics.   We are doing this by reviewing data for MPG to understand how well our car will do with fuel mileage as well as the desired configuration for the suspension.

## Linear Regression to Predict MPG

During the research it was shown that a few factors can be ruled out as having a small p-value and not considered to be issues with the production.   These would be the weight of the vehicle, the spoiler angle and whether or not the car has all wheel drive.  Inversely, it was identified that factors such as vehicle height and length do impact MPG at a significant level, and are items we can explore within MechaCar to improve vehicle MPG.

https://github.com/JohnJohnson913/MechaCar_Statistical_Analysis/blob/cf5ddb51c06b2500e7d6a415da55677951c1662c/Image_1.png

## Summary Statistics on Suspension Coils

Additionally, we wanted to ensure that our suspension of the car was being produced within our desired tolerances.   This would signify that it is in our desired tolorances if the variance of the suspension coils have a variance of under 100 psi.   The tests were conducted by comparing data from our manufactured lots and analyzing the PSI variance.  Good news, the overall variance was under 100 psi with lot 1 and 2 had a very small variance, however lot 3 did maintain a vairiance of 170 psi.

https://github.com/JohnJohnson913/MechaCar_Statistical_Analysis/blob/cf5ddb51c06b2500e7d6a415da55677951c1662c/Image_2.png

## T-Tests on Suspension Coils

Finally, performing a T-Test on all three lots examined whether the null hypothisis could be rejected.  For lot one and two has a significance level above .05% meaning can accept the null and sumize that lot 1 and 2 are significantly significant, where Lot 3 @ .04 is below the the variance of .05% allowing us to reject the null hypothisis. 

https://github.com/JohnJohnson913/MechaCar_Statistical_Analysis/blob/cf5ddb51c06b2500e7d6a415da55677951c1662c/Image_3.png
