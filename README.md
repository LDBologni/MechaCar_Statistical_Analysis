# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

- Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

The results show that the ground clearance and vehicle length have a significant impact on mpg, as per the other variables as the vehicle weight, spoiler angle, and All Wheel Drive (AWD) indicate that provide a random amount of variance in the dataset.

- Is the slope of the linear model considered to be zero? Why or why not?

The p-Value for this model is 5.35e-11, is a small number that indicates that there is sufficient evidence to reject the null hypothesis.

- Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

The linear model depicts a R-squared value of 0.7149 (approximately 71.5%), indicating that the model will mostly predict correctly the values of the mpg in the model.

- **Model Summary**

![Linear_Regression_D1](https://user-images.githubusercontent.com/98929742/171056068-2f9df4f3-4fb9-4df7-8099-e3eda7b31301.png)

## Summary Statistics on Suspension Coils

 Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
 
The Suspension Coil population depicts a Variance of 62.29 PSI, meaning that the Variance is withing 100 PSI Variance requirement.

![Total_lot_summary](https://user-images.githubusercontent.com/98929742/171055954-68491653-f3f7-4938-b318-b6e9da8c0719.png)

In addition reviewing the data of the lot individually the data displays the following:

![Manufacturing_Lot_Summary](https://user-images.githubusercontent.com/98929742/171055974-3cfeb6f0-6cab-43af-9acd-7918a1991bb0.png)

The results display the following:

Lot 1 and Lot 2 shows that the Variance is whithing the PSI requirement, as for the Lot 3 does not meet the Variance requirement

## T-Tests on Suspension Coils

<img width="445" alt="T_test_all" src="https://user-images.githubusercontent.com/98929742/171056686-01ceb41a-c586-4d33-8b35-4e9b8d0c05e6.png">

<img width="429" alt="T_test_lot" src="https://user-images.githubusercontent.com/98929742/171056662-e7c36010-0b03-4bda-a6de-79c5c52ac6db.png">

## Study Design: MechaCar vs Competition

**Comparisson Metrics:**

- Maintenance cost
- Safety Feature Rating
- Engine Type
- Selling Price
- MPG
- Drive Package


-**Hypothesis: Null and Alternative**

- Null Hypothesis (Ho): No statistical difference between MechaCar fuel efficiency and the fuel efficiency of all other comparable vehicles.

- Alternative Hypothesis (Ha): Statistical difference between the fuel efficiency of MechaCar versus the other cars.


-**Statistical Tests**

A statistical test to compare the data between companies is a one-sample t-test, the data of the population will be all comparable vehicles. An example of data required to perfom the test is the fuel efficiency of the population.









