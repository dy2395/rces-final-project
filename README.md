Final Project 

The scientific question: A study showes that for particle matters within 2.5-10, PM 2.5 reflects surface solar radiation the most and so affect the power output of solar PVs. I would like to see if PW 2.5 really imposes a negative affect on surface  solar radiation and if so how much is the effect. 

PM 2.5 air quality data from all sites in New York state in 2019: https://eescg6901.columbiajupyter2.org/hub/user-redirect/lab/tree/rces-final-project/PM2.5_New_York_2019.csv

Monthly average surface solar radiaion data from 2000 to 2019: https://xfr139.larc.nasa.gov/e33e498e-97a0-4bf4-ac71-8241c98002a9/CERES_EBAF_Edition4.1_200003-201911.nc

Summary of analysis:
Select and plot air quality monitor sites near New York city as particle matter are more abundant near compact cities. And then select surface solar radiation data in clear skies (to eliminate the cloud effects) near the monitor sites and plot it.  Then select where PM 2.5 level < 12(μg/m3) and > 35.5 (μg/m3) and plot the corresponding surface solar radiaion to see if there is a huge difference. I can also try using a linear regression model (scikit-learn) to find relationship between PM 2.5 level and surface solar radiation in clear skies.