# python_project2_DSB3
Nice Ride 2017 Bike Analysis
## Problem Statement

This project will analyze trip, station, and weather data to identify the periods and stations with the highest demand, compare demand with station capacity, and examine how weather affects bike usage

## Summary

This project analyzes Nice Ride Minnesota bike trips from 2017. I used three datasets: bike trip data, station data, and weather data.

I cleaned the data by checking for missing values and converting the date columns to datetime. I also created new features such as month, day, hour, day type, and trip duration.

The analysis looks at bike demand over time, station usage, trip duration, user types, weekdays and weekends, and weather conditions. The results help show different patterns in how people used the bikes during 2017.

## Project Questions

* How does bike demand change by month, day, and hour?
* Which stations have the highest and lowest bike demand?
* How does weather affect daily bike demand?
* Do members and casual users use bikes differently?
* Are trips longer on weekdays or weekends?
* Which stations are most commonly used as both start and end stations?

## Data

The project uses three datasets.

The trip data contains information about bike trips, including start and end stations, account type, and trip duration.

The station data contains information about the stations, including station name, location, and number of docks.

The weather data contains daily temperature and precipitation information for Minneapolis.

## Data Cleaning

I checked the datasets for missing values and data types.

The date columns were converted to datetime to make the time analysis easier.

I also created new features such as month, day, hour, day type, and trip duration.

## Key 

The analysis showed that bike demand changed depending on the time of year and time of day.

Some stations had much higher activity than others.

Trip duration was different between members and casual users and also between weekdays and weekends.

Weather conditions were also related to changes in daily bike demand.

## Conclusions and Recommendations

Bike usage varied across different times, stations, user types, and weather conditions.

These findings can help better understand bike usage and can support better bike availability and station planning.

## Research

For future analysis, I would explore user behavior, popular trip routes, station availability, and more detailed weather conditions.

## Tools

Python, Pandas, Matplotlib, Jupyter Notebook, and GitHub.

## Sources

Nice Ride Minnesota bike trip and station data.

NOAA weather data.
