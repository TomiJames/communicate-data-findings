# Ford GoBike System Data
## by Joy James


## Dataset

The original dataset contained about 183,412 observations across 16 variables. Most of the variables speak to details about the trip itself and a few such as age and gender describe the rider. In the course of the analysis, new features were derived from existing ones. Also, outliers from the trip duration were also dropped.

## Summary of Findings

After carrying out univariate, bivariate and multivariate exploration of this data, the following was observed:
1. A normal trip is about 0 to 1500 seconds long i.e. 0 - 25 minutes although most of them are about 8 minutes long.
2. Riders cover up to 4 kilometers on these trips but most trips are between 1 to 2 kilometers long.
3. Most riders prefer to ride in the evening compared to any other time of the day.
4. Most of the riders are male and most of them are aged around 30 years old.
5. As expected, the distance covered correlates positively with trip duration. However, this is weaker than expected.
6. The age and gender of the riders have little or no relationship with the trip duration.
7. The time of day the trip starts significantly impacts the duration and distance covered during the trip.
<br>
<br>
In conclusion, the distance to be covered during the trip and time of the day the trip is to be taken significantly affects how long the trip will be.


## Key Insights for Presentation

For the explanatory exploration, I focus just on the influence of the time of day and distance covered on the trip duration. I start by exploring the distributions of these different variables. I then go ahead to show the relationship between trip duration and distance. Finally I show how the trip duration changes for the same distance depending on the time of the day the trip was taken.