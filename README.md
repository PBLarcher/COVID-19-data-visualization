# U.S. COVID-19 Data Exploration Tool

## Overview

This project is an interactive Python-based analysis tool designed to explore and visualize COVID-19 trends across the United States. Utilizing real-world data from Johns Hopkins University, the program allows users to select a specific state and generates detailed statistics, trend charts, and interactive geospatial maps.

## Features
- User Interaction
  - customized reports based on user input (Name and U.S. State)
- Statistical Analysis:
  - Calculates the Ground Zero date for the chosen state (eg. typing 'texas' will return 'March 05, 2020')
  - Provides a breakdown of total cases, deaths, and daily averages for the years 2020 and 2021.
  - Computes cumulative totals as of December 31, 2021.


## Figure 1. 
### Option 1 was chosen
<img width="956" height="720" alt="Screenshot 2026-01-08 175312" src="https://github.com/user-attachments/assets/97854c3c-c795-4e5f-a73c-e32f5f8c6769" />

The screenshot is a simple visualization using two bar charts and two plots which contain New Daily Cases (Linear plot), Cumulative Cases (Linear plot) , New Daily Deaths (Bar Chart), and Cumulative Deaths (Linear plot).

(This option should pop up after you enter your Name, the state of your choice (Not Case Sensitive), and selecting '1' as the option.)

## Figure 2. Interactive chloropleth map: Total Reported Cases and Deaths in Texas
### Option 2 was chosen
<img width="1084" height="670" alt="Screenshot 2026-01-08 174530" src="https://github.com/user-attachments/assets/104b1c46-9228-45a5-bc1e-e2d00cb21322" />

The screenshot demonstrates how the script functions, what it does and what you should see as a visualization for the Map, for example I chose to do Texas. From here you can see a mouse cursor above "Harns" County, which also displays a text box containing cumulative deaths and cases.


## What was used?
 - Python 3
 - Pandas
 - Geopandas
 - Matplotlib
 - Mapclassify

## About the Data
The project utilzes datasets derived from the John Hopkins University CSSE COVID-19 Data Repository

## Installation & Setup
### 1. Clone the Repository:
```
### git clone [https://github.com/yourusername/covid-data-exploration.git](https://github.com/yourusername/covid-data-exploration.git)
```

### 2. Installation of required libraries: The packages should be installed if you are experiened with using Jupyter Notebook and the libraries. If not, run this:
```
pip install pandas
pip instal geopandas
pip install matplotlib
pip install folium
pip mapclassify
```

