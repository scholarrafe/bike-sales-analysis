# Bike Sales Dashboard

## Overview

![Bike Sales Dashboard](Screenshot (13).png)
This project involves the analysis of bike sales data for the years 2021 and 2022. By loading data from a SQL Server database and joining two datasets, a comprehensive dashboard was created using Power BI to visualize sales trends and factors affecting bike rentals.

## Data Source
The data was sourced from a SQL Server database and includes information regarding bike rentals, weather conditions, and various temporal attributes.

## Dataset Description
The dataset contains the following columns:

- **dteday**: Date of the record
- **season**: Season during which the rentals occurred
- **yr**: Year (2021 or 2022)
- **mnth**: Month of the year
- **hr**: Hour of the day
- **holiday**: Indicator of whether the day is a holiday
- **weekday**: Day of the week
- **workingday**: Indicator of whether the day is a working day
- **weathersit**: Weather situation (e.g., clear, cloudy, etc.)
- **temp**: Actual temperature in Celsius
- **atemp**: Feels-like temperature in Celsius
- **hum**: Humidity (percentage)
- **windspeed**: Wind speed (in km/h)
- **rider_type**: Type of rider (e.g., registered, casual)
- **riders**: Number of bike rentals

## Project Objectives
- Load and preprocess data from SQL Server.
- Perform a join operation on two datasets to consolidate relevant information.
- Create an interactive Power BI dashboard that visualizes:
  - Monthly and hourly sales trends for 2021 and 2022
  - Impact of weather conditions on bike rentals
  - Seasonal trends in bike rentals

## Getting Started
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/bike-sales-dashboard.git
