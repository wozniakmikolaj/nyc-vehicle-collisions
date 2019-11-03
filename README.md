# nyc-vehicle-collisions

## Goals and motivations
This repository is created to showcase my data cleaning and exploratory analysis skills using NYPD's Motor Vehicle Collisions dataset from NYC OpenData. My goal is to answer at least one of the following questions:
- what percentage of the collisions on average have one or more casualties?
- which borough or part of the city is the least safe for pedestrians?
- are there any seasonal fluctuations in collision frequency?

## Dataset
The full dataset can be found [here](https://data.cityofnewyork.us/Public-Safety/NYPD-Motor-Vehicle-Collisions/h9gi-nx95). This dataset contains a breakdown of every collision in New York City by location and injury dating from January 2012 (it's updated on a weekly basis). Because it consists of 1.52 million rows and 29 columns, I'll only work on data from 2018 (which I'll randomly sample to further reduce it's size).

## Project structure
For the sake of readability the project is divided into three phases: 
1. Sampling the original dataset. 
2. Cleaning the sample. 
3. Exploratory analysis of the data.

The datasets can be found in the [data]() folder in four versions: raw (downloaded from source), sampled (sample of the raw dataset), geocoded(slice of sampled data with additional geolocation info) and cleaned (clean sample of the dataset).
