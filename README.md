# Bike Sharing Assignment

> A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

## Table of Contents

- [General Info](#general-information)
- [Technologies Used](#technologies-used)
- [Conclusions](#conclusions)
- [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

* They want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:
    * Which variables are significant in predicting the demand for shared bikes.
    * How well those variables describe the bike demands

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

-  The linear regression model was able to predict bike demand precisely with an R2 Score of more than 80%.

- Final Equation
```
cnt = yr*0.237132 + temp*0.388947 + windspeed*(-0.160217) + Jan*(-0.050699) + July*(-0.064112) + Oct*0.052266 + Sept*0.060748 + Sat*0.023058 + Cloudy*(-0.078506) + Light_snow_rain*(-0.290117) + spring*(-0.121727) + 0.297184 
```

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used

- numpy - version 1.23.5
- pandas - version 1.5.2
- matplotlib - version 3.6.2
- seaborn - version 0.12.2
- scikit-learn - version 1.2.2
- statsmodels - version 0.13.5


## Contact

Created by [@pulkitgangwar] - feel free to contact me!

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
