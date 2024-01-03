Enhancing the README for `cleanse_data.ipynb` involves providing a detailed overview of the notebook's content, purpose, and instructions for use. Below is an enhanced version of your README:

---

# Data Cleansing Tutorial for Austin MetroBike Trips

## Overview
This tutorial demonstrates how to cleanse and analyze the Austin MetroBike Trips dataset using Python and pandas. The notebook `cleanse_data.ipynb` covers a range of techniques including loading data, data normalization, merging datasets, handling missing values, and basic data visualization.

## Prerequisites
To follow along, ensure you have the following installed:
- Python 3
- pandas library
- matplotlib library

You will also need to download the following datasets:

**Make sure you download the right file format or modify the python code to accomodate the format you choose**

1. **Austin MetroBike Trips CSV File**: [Austin_MetroBike_Trips_20231231.csv](https://data.austintexas.gov/Transportation-and-Mobility/Austin-MetroBike-Trips/tyfh-5r8s/about_data)
2. **Austin MetroBike Kiosk Locations JSON File**: [Austin_MetroBike_Trips.json](https://data.austintexas.gov/Transportation-and-Mobility/Austin-MetroBike-Kiosk-Locations/qd73-bsdg/about_data)

## Key Operations in the Notebook
1. **Data Loading**: Loading CSV and JSON files into pandas DataFrames.
2. **Setting Display Options**: Configuring pandas for optimal display of DataFrame information.
3. **Data Merging and Normalization**: Merging data from different sources and normalizing JSON data within a DataFrame.
4. **Type Conversion and Error Handling**: Converting data types and handling errors and NaN values.
5. **Data Analysis and Visualization**: 
   - Creating pie charts to visualize data cleaning steps.
   - Grouping and aggregating data for trend analysis.
   - Plotting rolling averages to observe patterns over time.

## Running the Notebook
1. Open `cleanse_data.ipynb` in your Python environment.
2. Replace the file paths with the paths where you have saved the datasets.
3. Run the cells in sequence to perform data cleansing and analysis.

## Expected Outcomes
- Understand how to handle and cleanse real-world data.
- Gain insights into Austin MetroBike usage patterns.
- Learn basic data visualization techniques using matplotlib.

## Saving Results
The notebook saves cleansed data in the following formats:
- `Kiosk_with_LatLong.csv`: CSV file containing kiosk data with latitude and longitude.
- `cleaned_metrobike_trips.json`: JSON file of the cleansed trip data.
