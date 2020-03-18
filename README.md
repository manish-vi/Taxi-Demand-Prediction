# Taxi Demand Prediction New York City

## Problem Statement
For a given location in New York City, our goal is to predict the number of pickups in that given location. The taxi driver uses prediction to move to the locations where predicted pickups are high.

## Objectives & Constraints 
__Objectives:__ Our objective is to To find the number of pickups, given location coordinates(latitude and longitude) and time, in the query region and surrounding regions. To solve the above we would be using data collected in Jan - Mar 2015 to predict the pickups in Jan - Mar 2016.

__Constraints:__ 
* __Latency__ Given a location and current time a taxi driver excepts to get the predicted demands in his/her neighboring region in a few seconds. Hence, there is a medium latency requirement.

* __Interpretability:__ Taxi drivers are only concern about good prediction resuls. Hence, there is a no interpretability required.

## Source of Data
__Data can be downloaded from here:__  
Get the data from : http://www.nyc.gov/html/tlc/html/about/trip_record_data.shtml (2016 data) The data used in the attached datasets were collected and provided to the NYC Taxi and Limousine Commission (TLC)

## Performance metrics
1. Mean Absolute percentage error.
2. Mean Squared error.

## Getting Started
Start by downloading the project and run "Taxi-Demand-Prediction-NYC.ipynb" file in ipython-notebook.

## Prerequisites
You need to have installed following softwares and libraries in your machine before running this project.
1. Python 3: https://www.python.org/downloads/
2. Anaconda: It will install ipython notebook and most of the libraries which are needed like sklearn, pandas, seaborn, matplotlib, numpy and scipy: https://www.anaconda.com/download/

## Libraries: 
* __dask:__ It is used to handle very large files.
    * i) pip3 install dask

* __folium:__ It is used to plot maps using latitude and longitude.
    * i) pip3 install folium
    * ii) conda install -c conda-forge folium

* __xgboost:__ It is used to make xgboost regression model. 
    * i)  pip3 install xgboost
    * ii) conda install -c conda-forge xgboost 

* __gpxpy:__ It is used while we calculate the straight line distance between two (latitude, longitude) pairs in miles.
    * i) pip install gpxpy

## Authors
•	Manish Vishwakarma - Complete work  
