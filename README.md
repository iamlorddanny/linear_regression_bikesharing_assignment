
# Linear regression Submission on BikeSharing upgrad

The dependent variable (Count of Bike rentals, or Demand for Bike rentals on a given day) is determined by the equation: 

Demand of bike rentals (count of rentals on a given day) Y = 
2040.728472 * (yr) -856.298580* (holiday) +3915.657583 * (temp)
 -1211.631001 * (windspeed) -973.775471* (season_spring) + 401.913171* (season_winter) 
-636.310347* (mnth_jul) + 495.793864* (mnth_sept) 
-696.415150 *(weathersit_2) -2487.368512 * (weathersit_3) + 2217.347907


## Inferences

From the categorical variables from the given data set: Holiday, Temperature, Windspeed, Spring season, Winter season, Month of July and Septerber and certain Weather situations best explain the expected demand for the bike rentals.

Temperature has a very high positive coefficient – indicating it is a strong predictor of the demand, suggesting people prefer to take bikes on rentals on warm or hot days over nike rentals on a cold day
Windspeed has a negative coefficient suggesting less interest from riders to take a bike rental on a windy day
If the weather situation is misty or indicative of rain, thunderstorm, or snowfall, the demand is likely to fall
Seasonality and months also explain the demand

##  Validation of Model
The error terms / residuals of the model are normally distributed: Plotting a histogram of the error terms of the training data.

The histogram for residuals on training data is a normally distributed histogram with mean at zero.

Independence: The error terms are with-in 2 standard deviations on either size of Zero.

Homoscedasticity: The target values have same variance at every level of X

The plot below showing uniform scatter of error terms for all values of Y validates Homoscedasticity of the model

Linear relationship: The Y predicted follows the same pattern as that of Y actual and this proves a linear relationship of the model on the training data

## Technology Used

Python
Jupyter Notebook
Stats Models Module
SciKit-Learn Module


