# Python_Task_1
Project 1 for python course
# Weather Data Analysis Tool

## Overview

The **Weather Data Analysis Tool** is a Python application designed to analyze and visualize weather data. It processes weather data from CSV files and provides insights into temperature trends, rainfall patterns, and extreme weather events. The application is built using Python's core libraries and does not rely on external dependencies.

## Features

### Core Functionality
1. **Data Initialization**
   - Reads weather data from a CSV file with fields:
     - `Date`, `Temperature (°C)`, `Rainfall (mm)`, `Humidity (%)`, `Wind Speed (km/h)`, and `Condition` (e.g., Sunny, Rainy).
   - Handles data using Python's core tools.

2. **Data Import and Validation**
   - Allows users to import new weather data.
   - Validates data to ensure correct formats for dates and numerical fields.
   - Replaces missing values with averages or predefined defaults.

3. **Weather Trend Analysis**
   - Calculates key statistics:
     - Average temperature, rainfall, and humidity over specific periods.
     - Days with the highest and lowest temperature or rainfall.
     - Count of sunny, rainy, or windy days in a given month.

4. **Weather Reports**
   - Generates summary reports for user-specified date ranges:
     - Displays average, maximum, and minimum values for temperature, rainfall, and wind speed.
     - Lists days with extreme conditions (e.g., storms or heatwaves).

5. **Data Visualization**
   - Provides ASCII-based visualizations:
     - Line charts for temperature trends. ![Screenshot (19)](https://github.com/user-attachments/assets/fef9d83a-e3d1-49d9-b361-490b23077b7a)

     - Bar charts for daily rainfall. ![Screenshot (20)](https://github.com/user-attachments/assets/51605a31-900e-401c-8aae-c0e13899b0c3)

     - Summary tables showing monthly weather statistics. ![Screenshot (21)](https://github.com/user-attachments/assets/0cfa1722-a331-4ff5-9e94-6196a520e014)


### Advanced Features (Optional)
1. **File Handling**
   - Exports weather reports to CSV files.
   - Saves and reloads user-defined analysis configurations.

2. **Error Handling**
   - Catches invalid data inputs and provides meaningful error messages.

3. **Interactive Search**
   - Allows searching for weather data by date or condition.

4. **User Interface**
   - Interactive, menu-driven program with options to:
     - Import or add weather data.
     - View statistics for specific dates or ranges.
     - Generate ASCII-based visualizations.
     - Export reports.

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/mahfuz0929/Python_Task_1/
   cd Weather_Data_Analysis_Tool

