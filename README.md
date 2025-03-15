# London Bike Rides Project using Python & Tableau

![Bikes](https://github.com/ver369/London_bike_rides_project/blob/main/London%20bikes.jpg)

## Overview
This project is based on a dataset of bike-sharing trips in London, containing information on ride counts, weather conditions (temperature, wind speed, humidity), and time-related factors (day of the week, time of day, etc.). The data allows for an analysis of how different factors influence bike usage.

## Dataset
The data for this project is sourced from Kaggle Dataset:

- **Dataset Link** [London bike sharing dataset](https://www.kaggle.com/datasets/hmavrodiev/london-bike-sharing-dataset)

## Step 1. Data Preprocessing using Python
[Process of Working with Data](https://github.com/ver369/London_bike_rides_project/blob/main/london_bikes_project.ipynb)

- Imported the dataset using Pandas and checked its structure
- Renamed columns for better readability
- Converted humidity values to percentage format
- Mapped numerical season codes to descriptive labels
- Saved the cleaned dataset to an [Excel file](https://github.com/ver369/London_bike_rides_project/blob/main/london_bikes_final.xlsx), which was later used for visualization in Tableau
## Step 2. Data Visualization using Tableau
![Tableau Dashboard](https://github.com/ver369/London_bike_rides_project/blob/main/Tableau%20Vizualization.png)
[Link to the Dashboard](https://public.tableau.com/views/LondonBikeRides_17420621229300/Dashboard1?:language=en-US&:sid=E5AB52F791374C7083B2C5A8D10AC9DE-0:0&:redirect=auth&:display_count=n&:origin=viz_share_link)

I built an interactive visualization in Tableau, which includes:
- A moving average chart to highlight overall trends in bike usage
- A heatmap of temperature and wind speed to show the impact of weather on rides
- Filters to allow for a more detailed exploration of the data

## Conclusion
This project helps uncover seasonal and weather-related trends in bike traffic and provides a useful tool for data analysis. 

