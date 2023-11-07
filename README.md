# Omdena - Discovering the Relationship Between Crime Statistics and Weather in the Houston Area

## Project Link: 
https://omdena.com/chapter-challenges/discover-the-relationship-between-crime-statistics-and-weather-in-the-houston-area/
## Background
Climate change is a pressing concern for metropolitan areas like Houston, TX, with its rapid population growth posing social, safety, and economic challenges. The proposed project investigates the relationship between weather and crime statistics in Houston. As global temperatures rise, weather events such as heatwaves, hurricanes, and heavy rainfall may impact crime rates.

Analyzing historical crime and weather data, the project seeks to provide data-backed insights for law enforcement to address weather-related crime spikes and enhance public safety during extreme weather events.
This project’s significance lies in its potential to inform crime prevention strategies and resource allocation for law enforcement in Houston.

Understanding how weather patterns influence criminal behaviors can lead to targeted approaches in mitigating weather-related crime and building more resilient urban environments. By leveraging data science and crime analysis, the project contributes to creating safer communities amid the challenges posed by climate change.

## Problem
Houston faces significant challenges with crime and public safety as a bustling metropolitan area. Law enforcement agencies seek to enhance crime prevention measures and respond effectively to criminal activities. Global warming adds to the complexity, leading to unpredictable weather events like heatwaves, hurricanes, and flooding, potentially impacting crime patterns.

The project aims to explore the relationship between weather and crime statistics in Houston. Analyzing historical crime and weather data seeks to identify correlations or patterns. The insights will help law enforcement make data-driven decisions, enabling targeted crime prevention strategies and resource allocation.

Understanding the weather’s influence on criminal behaviors will empower law enforcement to address weather-related crime spikes and enhance public safety during extreme weather events. The goal is to build safer and more resilient communities in Houston, considering the challenges of climate change and its potential impact on crime rates.

## Project Goals
- Investigate the Impact of Global Warming on the Crime Rate.
- Assess the Influence of Weather Events (heatwaves, hurricanes, heavy rainfall) on Specific Types of Crime (property crimes, violent crimes).
- Analyze the Relationship between Temperature, Humidity, wind speed, and Crime Rate in a day.
- Investigate Seasonal Variations (Summer and Winter) in Crime and Weather.
- Explore Weather Effects (hot and humid days, heavy rain) on Specific Types of Crime (theft, assault, domestic violence)

## Project Plan
<img src = "https://github.com/ttariqaziz/weather_crime_relationship_houston_omdena/blob/main/images/project_plan_houston_omdena.jpg">

## Project Structure
```
📦weather_crime_relationship_houston_time_series_analysis_omdena 
├─ .gitignore
├─ Data
│  ├─ Cleaned
│  │  └─ daily crime numbers and weather data for time series analysis.csv
│  ├─ crime_from_kaggle
│  │  └─ Documenting_Hate_2017 - Data.csv
│  ├─ crimefromHPD
│  │  ├─ 2019_NIBRSPublicView.Jan1-Dec31.xlsx
│  │  ├─ NIBRSPublicView.Jan1-Dec31-2020.xlsx
│  │  ├─ NIBRSPublicViewDec21.xlsx
│  │  ├─ NIBRSPublicViewDec22.xlsx
│  │  └─ NIBRSPublicViewJul23.xlsx
│  ├─ houston_monthly unemployment_rate
│  │  └─ Houston-The Woodlands-Sugar Land, TX Metropolitan Statistical Area.csv
│  └─ weatherbyyear
│     ├─ htx_2006_weather.csv
│     ├─ htx_2007_2008_weather.csv
│     ├─ htx_2010_weather.csv
│     ├─ htx_2011_weather.csv
│     ├─ htx_2012_weather.csv
│     ├─ htx_2013_weather.csv
│     ├─ htx_2014_weather.csv
│     ├─ htx_2015_weather.csv
│     ├─ htx_2018_weather.csv
│     ├─ htx_2019_weather.csv
│     └─ htx_2021_weather.csv
├─ LICENSE
├─ Notebooks
│  ├─ 1_1_Weather_data.ipynb
│  ├─ 1_2_clean_merge_crime_houston_datasets.ipynb
│  ├─ merge_crime_houston_datasets.ipynb
│  ├─ task_1_data_collection_and_preparation.ipynb
│  ├─ task_3_model_developement_time_series_analysis.ipynb
│  ├─ task_3_model_developement_time_series_analysis_Tariq.ipynb
│  └─ task_5_model_deployment_first_draft.ipynb
├─ README.md
└─ images
   ├─ App Deployment.jpg
   ├─ App Deployment1.jpg
   └─ project_plan_houston_omdena.jpg
```

## Folder Overview
- reports - Folder to store all Final Reports of this project.
- Data - Folder to Store all the data collected and used for this project.
- Docs - Folder for Task documentations, Meeting Presentations and task Workflow Documents and Diagrams.
- References - Folder to store any referneced code/research papers and other useful documents used for this project.
- Visualization - Folder to store dashboards, analysis and visualization reports.
## Gradio App
<img src = "https://github.com/ttariqaziz/weather_crime_relationship_houston_omdena/blob/main/images/App%20Deployment1.jpg">
<img src = "https://github.com/ttariqaziz/weather_crime_relationship_houston_omdena/blob/main/images/App%20Deployment.jpg">

Dagshub repository link: https://dagshub.com/ttariqaziz/WeatherCrimeHouston
