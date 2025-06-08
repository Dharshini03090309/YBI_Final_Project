# YBI_Final_Project
AiML with Data Science Intenrship -  Final Project

1. Data Loading & Initial Inspection
Loaded 5 datasets:

1] city_day.csv (daily city-level air quality)

2] city_hour.csv (hourly city-level air quality)

3] station_day.csv (daily station-level air quality)

4] station_hour.csv (hourly station-level air quality)

5] stations.csv (station metadata)

6] Checked the first 5 rows of each dataset to understand structure.


2. Basic Data Exploration

Used head(), info(), and describe() to:

1] View column names and data types.

2] Summarize statistical distributions.

- Verified no missing values.

- Checked for duplicates with duplicated().sum() (found none).

3. Visualizations

1] Temporal Analysis: Explore trends over years/seasons/hours.

2] Geospatial: Compare cities/stations.

3] Pollutant Correlations: How gases/particulates relate to AQI.
