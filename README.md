Final Project 

The scientific question: A study showes that for particle matters within 2.5-10, PM 2.5 reflects surface solar radiation the most and so affect the power output of solar PVs. I would like to see if PW 2.5 really imposes a negative affect on surface  solar radiation and if so how much is the effect. 

PM 2.5 air quality data from all sites in New York state in 2017: https://github.com/dy2395/rces-final-project/blob/master/NY_PM2.5_Daily_2017.csv

Monthly average surface solar radiaion data from 2000 to 2018: https://opendap.larc.nasa.gov/opendap/CERES/EBAF/Surface_Edition4.0/CERES_EBAF-Surface_Edition4.0_200003-201803.nc

Summary of analysis:
Select and plot air quality monitor sites in New York State. 
Select surface solar radiation data in clear sky conditions (to eliminate the cloud effects) near the monitor sites and plot it.  Then select where PM 2.5 level < 12(μg/m3) and > 35.5 (μg/m3) and plot the corresponding surface solar radiaion to see if there is a huge difference. Can also try using a linear regression model (scikit-learn) to find relationship between PM 2.5 level and surface solar radiation in clear skies.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/dy2395/rces-final-project/HEAD)