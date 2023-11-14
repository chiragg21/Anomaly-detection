# Anomaly-detection
MTH442 course project

Data-set : 
Worked with the New York Taxi Dataset which contains the number of taxis used by the public from July 2014 to January 2015. There are in total 10,320 time instances. Contains two coloumn one of time stamps and other the number of passengers over an interval of 30 min. 

Objective and procedure:
1) Examined the dataset to detect any irregularities or anomalies.
-- Consolidated the data from 30-minute intervals to daily intervals to identify anomalies on specific days.
-- Examined and eliminated any existing trends or seasonality components in the data.
-- Assess whether the data is covariance stationary.
-- Determined p and q values for the ARMA process.
-- Conducted model fitting and obtained residuals by calculating the difference between observed and predicted values.
-- Detected anomalies with a significance level of 5%.

2) Conduct data analysis to pinpoint the peak time-period during a day with the highest probability for taxi drivers to find customers.
-- Removed all the days where anomalies observed.
-- Calculated the average for all the 48 intervals in a day for two categories – weekdays and weekends.

Conclusion:
-- We found seven anomalies in 215 days.
-- Anomalies occur either on the day of the festival or a natural calamity.
-- We observed that the time slots with higher passenger frequency occur on weekdays between 8 am to 3 pm and 6 pm to 11 pm, and on   
   weekends between 10 am to 4 pm and 6 pm to 1 am.
-- It is also observed that weekdays have more working hours during the day, while the weekends have more working hours during the night.


