# Fuel Pipeline leak detection and location based on Negative Pressure Wave
This project is python based code for ML modeling fuel pipeline leaks submitted toward the degree of Master of Science Intelligent Systems.

## Table of Contents:
  #### Data
  #### Preprocessing
  #### Leak detection modeling
    XGBoost
    Attention-based LSTM
  #### Leak location model
## Data
    The project contains 2 datasets:
    1) PT_Data.csv - Pressure sensors signals. use this file for the preprocessing and detection modeling stage.
    2) Data10.csv - Leak detection time and distance. use this file for the location modeling stage.
## Preprocessing
    Run the following files as preprocessing for the modeling stage:
    1) [DataPrep - Noise reduction and splits .ipynb](https://github.com/AnatKarny/FuelLeakDetection/blob/main/DataPrep%20-%20Noise%20reduction%20and%20splits%20.ipynb)
    2) [DataPrep - Normalize Data.ipynb](https://github.com/AnatKarny/FuelLeakDetection/blob/main/DataPrep%20-%20Normalize%20Data.ipynb)
    3) DataPrep - Statistical feature extraction.ipynb
    4) DataPrep - Spectral analysis feature extraction.ipynb
    5) DataPrep - feature selection.ipynb
## Leak detection modeling
    The leak detection phase contains two classification models:
    1) LeakDetection - XGBoost.ipynb
    2) LeakDetection - LSTM.ipynb 
## Leak location model
    LeakLocation.ipynb - Run this file to apply registration model fo leak location.
