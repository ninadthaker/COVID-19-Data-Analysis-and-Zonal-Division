# COVID-19-Data-Analysis-and-Zonal-Division

# Introduction

## Project Background
A virus originated from PRC's Wuhan has taken lives of 1.17M people. With total of 44.5M cases registered worldwide till date. During
this unfortunate time, maintaining physical distancing and wearing mask has become necessity. However, the cases are still increasing
every single day. Hence, to avoid exposure to the virus and to keep people safe, worldwide more than 100 countries imposed full or
partial lockdowns with different levels over the course of the year. The levels of the lockdown are changed based on the number of
cases and deaths registered.

## Problem Statement
This Project will look at the data for the Republic of Ireland inorder to analyze the cases per county graphically and to potentially help
for making decision on what level of movement restriction must be imposed on a county and on the nation if and when needed to avoid
the spread of the Novel Coronavirus.

## Objectives
1) We will first perform ETL - Extract Transform Load on the data to identify and select only the data which is useful for our project.
2) We will then plot the Time Series plots for a few counties and visualize their situation for 8 months.
3) Then we are interested to in the Correlation analysis of the counties i.e. we want to find if there is a chance of getting infected when
travelling from one to another county.
4) We want to control the future cases so we will create a method to find the current cases and based on that we will tag the counties
for division i.e. Zonal Division is Red being highest case count, Orange with medium amount of cases which could skyrocket or decline
in future and Green as low case count as of now.
5) Once we find and decide the zones for each county, we will plot them on the MAP as this would allow us to visualize how well or bad
each county is doing and through that we may impose the levels of lockdowns to allow only authorized movement to allow general
public movement with limited access/ gathering etc.

## Note
The dataset used in this project is taken from https://data.gov.ie/dataset/covid19countystatisticshpscirelandopendata1
(https://data.gov.ie/dataset/covid19countystatisticshpscirelandopendata1), and is updated periodically. There could be some
missing/inaccurate data in this dataset but for the purpose of this project, we will assume that this is accurate and based on that we will
perform our analytical tasks.

The MAP related files can be found on https://gadm.org/download_country_v3.html (https://gadm.org/download_country_v3.html) by
selecting "Ireland" and downloading the Shapefile.

## Packages

The following is a complete list of packages used in this project:

1) collections
2) numpy
3) pandas
4) seaborn
5) matplotlib
6) geoplot
7) geopandas
8) shapefile

The packages can be installed using one of the following methods...

1) WinPython: pip install numpy pandas seaborn matplotlib geopandas geoplot pyshp
2) Anaconda: conda install numpy pandas seaborn matplotlib geopandas geoplot pyshp
