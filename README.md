# Bearing Fault Detection using Vibration Data

## Overview
This project demonstrates an end-to-end industrial machine learning pipeline for detecting
bearing faults using vibration sensor data.

The workflow includes feature engineering from raw vibration signals, exploratory analysis,
dimensionality reduction, and machine learning-based fault classification with confidence analysis.

## Dataset
- Vibration data collected from rotating machinery
- Sensors mounted on two bearings (X & Y directions)
- Fault types: Normal, Ball, Inner race, Outer race

## Key Techniques
- RMS and Kurtosis-based feature extraction
- Statistical and visual analysis
- PCA for dimensionality reduction
- Random Forest classifier
- Confusion matrix and probability-based confidence analysis

## Results
- Inner race faults detected with very high confidence
- Ball and outer race faults show partial overlap (realistic behavior)
- Model reflects real-world predictive maintenance scenarios

## Tools Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

## Author
Gowthami Srikanth
