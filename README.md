Final Project 

The scientific question: A study showes that for particle matters within 2.5-10, PM 2.5 reflects surface solar radiation the most and so affect the power output of solar PVs. I would like to see if PW 2.5 really imposes a negative affect on surface  solar radiation and if so how much is the effect. 

* PM 2.5 air quality data from all sites in New York state in 2016 from EPA: https://raw.githubusercontent.com/dy2395/rces-final-project/master/NY_2016_PM2.5.csv

* Monthly average surface solar radiaion data from 2000 to 2018 from NASA: https://opendap.larc.nasa.gov/opendap/CERES/EBAF/Surface_Edition4.0/CERES_EBAF-Surface_Edition4.0_200003-201803.nc (*** Removed as its resolution is low and does not include direct normal radiation for diffuse radiation calculation)

* 2016 PSM Direct Normal Irradiance (DNI) and Global Horizontal Irradiance (GHI) from NREL: https://docs.google.com/uc?export=download&id=1t3EoGgaMc-nF6gyx1QjLdBoON3w-eezV for GHI; https://docs.google.com/uc?export=download&id=1-A3DzYEXPnvraSTTtxFi53XvS71_Z88B for DNI.


Summary of analysis:
Visualize GHI and DNI data over the US and the New York State. Calculate the diffuse horizontal irradiance (DHI) and diffuse fraction. Plot PM 2.5 concentration data from air quality sites over the New York State and make close-up to New York City. Also plot filtered data with higher values for clearer comparison in New York City. Find and average diffuse irradiance & diffuse fraction data that are close to the PM 2.5 data locations, and run linear regression models to examine the correlation.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/dy2395/rces-final-project/HEAD)