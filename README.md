# Car Accident Severity Prediction Analysis

## Overview
This Orange workflow project analyzes car accident data to predict accident severity using machine learning. The analysis incorporates various data sources including accident data, weather conditions, and holiday information.

## Project Structure
- [SrishtiBinwani_DE_Final.ows](https://github.com/srishti-10/Car-Accident-Severity-Prediction-Analysis/blob/main/SrishtiBinwani_DE_Final.ows): Main Orange workflow file
- [car-crashes.csv](https://github.com/srishti-10/Car-Accident-Severity-Prediction-Analysis/blob/main/car-crashes.csv): Primary dataset containing accident information
- [weather-sfcsv.csv](https://github.com/srishti-10/Car-Accident-Severity-Prediction-Analysis/blob/main/weather-sfcsv.csv): Weather conditions dataset
- [holidays.xml](https://github.com/srishti-10/Car-Accident-Severity-Prediction-Analysis/blob/main/holidays.xml): Holiday information dataset

## Data Sources
1. **Car Accident Data** ([car-crashes.csv](https://github.com/srishti-10/Car-Accident-Severity-Prediction-Analysis/blob/main/car-crashes.csv))
   - Location data (Latitude, Longitude)
   - Road features (Bump, Crossing, Give_Way, etc.)
   - Accident severity
   - Timestamps
   - Additional metadata (Amenity, Side, State, Distance)

2. **Weather Data** ([weather-sfcsv.csv](https://github.com/srishti-10/Car-Accident-Severity-Prediction-Analysis/blob/main/weather-sfcsv.csv))
   - Weather conditions
   - Temperature and humidity
   - Wind speed and direction
   - Visibility and precipitation

3. **Holiday Data** ([holidays.xml](https://github.com/srishti-10/Car-Accident-Severity-Prediction-Analysis/blob/main/holidays.xml))
   - Official US holidays
   - Holiday dates and descriptions

## Analysis Pipeline
The workflow includes several key components:

1. **Data Preprocessing**
   - Feature selection and engineering
   - Data cleaning and formatting
   - Date/time processing
   - Weather data integration
   - Holiday data integration

2. **Exploratory Data Analysis**
   - Scatter plots for spatial analysis
   - Box plots for distribution analysis
   - Bar plots for categorical analysis
   - Feature statistics and correlations
   - Data distribution visualization

3. **Machine Learning**
   - Random Forest model implementation
   - Model evaluation using Test and Score
   - Feature importance analysis
   - Model performance metrics

4. **Data Enhancement**
   - Weather condition integration
   - Holiday impact analysis
   - Day/Night feature addition
   - Data balancing techniques

## Key Findings
- Spatial patterns in accident severity
- Impact of weather conditions on accidents
- Holiday effect on accident rates
- Temporal patterns in accident severity
- Feature importance in severity prediction

## Requirements
- Orange Data Mining Toolkit
- Python environment
- CSV and XML file support

## Usage
1. Open the workflow in Orange
2. Load the required datasets
3. Run the analysis pipeline
4. Review visualizations and model results

## Author
Srishti Binwani

## Last Updated
May 4, 2025