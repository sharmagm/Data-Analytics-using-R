# Data-Analytics-using-R

Summary:

In this module, we are analyzing the data provided for Aircraft (with number of observations = 800).

Firstly, we are reading the data, calculating sample size, cleaning the data based on the conditions provided for height, speed_ground, speed_air, duration and distance, visualizing the data, selecting the parameters, model checking, re-modeling with higher degree, determining model adequacy and checking goodness of fit.

Based on the various functions and tests performed on the data, we can conclude that the model is a best fit and landing distance is dependent on the make of aircraft, ground speed and height over threshold.

Analysing the model,

y = β0β0 + β1β1x1 + β2β2x2 + β3β3x2 + β4β4x3^2

where βiβi are the co-efficients which are represented as:

y(distance) = 1774.48 + 402.75 * x1 + 13.71 * x2 - 68.82 * x3 + 0.69 * x32x32

x1 = Type of aircraft with Boeing = 1 and Airbus = 0

x2 = height

x3 = speed_ground

Conclusion:

We can conclude from the above observations that this model is the best fit model due to the following reasons:

All the variables plays a significant role in this model.

Resiual plots do not follow a particular pattern and is distributed randomly.

P value of 2.2e-16 is very small and less than 0.05.

R^2 of 0.977 is very near to 1 hence the model can determine 97.7% of the variability in distance.

Landing distance is dependent on the make of aircraft, ground speed and height over threshold.
