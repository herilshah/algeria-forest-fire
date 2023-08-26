# Algerian Forest Fire Prediction

This repository contains code for predicting the Fire Weather Index (FWI) in Algerian forest regions using Ridge Regression. The prediction is based on several meteorological features including Temperature, Relative Humidity (RH), Wind Speed (Ws), Rainfall (Rain), Fine Fuel Moisture Code (FFMC), Duff Moisture Code (DMC), Initial Spread Index (ISI), and the forest fire Classes.



## Introduction

The Fire Weather Index (FWI) is a critical measure used in fire weather forecasting. It helps assess the risk of forest fires by considering various meteorological factors. This project aims to predict the FWI for different Algerian forest regions using Ridge Regression, a linear regression technique with L2 regularization.

## Data

The dataset used for this project contains the following features:

- Temperature: Temperature in Celsius (°C)
- Relative Humidity (RH): Percentage (%)
- Wind Speed (Ws): Measured in km/h
- Rainfall (Rain): Measured in mm
- Fine Fuel Moisture Code (FFMC)
- Duff Moisture Code (DMC)
- Initial Spread Index (ISI)
- Classes: Forest fire classes (e.g., "Fire," "Not Fire")
- Region: The geographic region where data was collected

## Requirements

To run this code, you need the following Python libraries and packages:

- NumPy
- Pandas
- Scikit-Learn
- Flask
- Pickle
You can install these dependencies using `pip`:

```bash
pip install -r requriements.txt
