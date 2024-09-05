
# F1 Analysis

## General overview
This project performs an analysis of Formula 1 data, combining various datasets related to race results, qualifying sessions, pit stops, driver standings, and constructor standings. A data preprocessing phase is conducted, followed by visual analyses using libraries such as Bokeh, Plotly, and Seaborn.

## Requirements
The following Python libraries are required to run the project:
- pandas
- numpy
- matplotlib
- seaborn
- plotly
- folium
- bokeh
- openpyxl

## Installation
To install the dependencies, run:
```bash
pip install pandas numpy matplotlib seaborn plotly folium bokeh openpyxl
```

## Dataset
The project uses several combined Excel datasets (can be downloaded on Kaggle) to provide comprehensive information on drivers, constructors, and Formula 1 races. The Excel file contains sheets representing:

Race results
Qualifying results
Pit stops
Driver and constructor standings

## Analysis
The following preprocessing operations are performed:
1. **Data merging**: Tables are joined using keys such as `driverId`, `constructorId`, `raceId`, and `statusId` to enrich the data with driver names, constructor details, and race information.
2. **Time conversion**: Time-related data is converted from milliseconds to minutes for better readability.

## Data Visualization
- **Interactive charts**: Using Bokeh, charts are created to visualize the trends in wins and points by year, with the option to filter by driver or constructor.
