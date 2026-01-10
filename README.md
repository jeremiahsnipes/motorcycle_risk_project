# Google SLides Link Below
https://docs.google.com/presentation/d/1JFVPVbKtxCN6o2Gz7wGDBcwucdpTy80m9gMJ7ckju-Q/edit?slide=id.g3b5b789cbf1_0_303#slide=id.g3b5b789cbf1_0_303

# ANA 699 Capstone Project  
Motorcycle Crash Risk Analysis

## Overview  
This repository contains materials for the ANA 699 analytic capstone project. The project analyzes motorcycle crash data from Southern California to examine injury severity, contributing factors, and spatial risk patterns using event-level crash records.

The analysis uses official crash data derived from California’s Statewide Integrated Traffic Records System (SWITRS) and accessed through the Transportation Injury Mapping System (TIMS).

## Project Questions  
- What factors are associated with motorcycle crash injury severity?  
- How does alcohol involvement relate to crash outcomes?  
- Are there spatial patterns or locations with consistently higher motorcycle crash risk?  

## Data Source  
The data used in this project were obtained from the Transportation Injury Mapping System (TIMS), a public crash data platform developed by the UC Berkeley Safe Transportation Research and Education Center (SafeTREC).

TIMS provides access to motorcycle crash records derived from California’s Statewide Integrated Traffic Records System (SWITRS), the official statewide database of police-reported traffic collisions. SWITRS data originate from California Highway Patrol and local law enforcement collision reports and are updated on a regular basis.

Motorcycle crash records were accessed using the TIMS Motorcycle Crash Map Viewer and filtered by county, crash severity, alcohol involvement, and year. The resulting dataset contains event-level crash records for multiple Southern California counties, including injury severity outcomes, alcohol involvement indicators, roadway and environmental conditions, temporal variables, and geocoded latitude and longitude.

## Data  
Motorcycle crash records from the following Southern California counties were combined into a single dataset:
- Los Angeles  
- Riverside  
- San Bernardino  
- San Diego  

The combined dataset is stored as:

`SoCal_Motorcycle_Crashes.csv`

Each row represents an individual motorcycle crash.

## Methods  
- Data cleaning and preprocessing  
- Exploratory data analysis  
- Injury severity classification  
- Logistic regression and tree-based modeling  
- Spatial analysis and hotspot identification  

## Repository Structure  
SoCal_Motorcycle_Crashes.csv   Combined motorcycle crash dataset  
README.md                     Project documentation  

## Tools  
- Python (pandas, scikit-learn, geopandas)  
- Data visualization and GIS libraries  

## Academic Context  
This project is part of ANA 699: Analytic Capstone Project in the M.S. in Data Science program.

## Team  
ANA 699 Capstone Group
