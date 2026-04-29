# StarScope Exoplanet Detection

This project uses Kepler light curve data to predict whether a star has an exoplanet.

## Team
- Van Nguyen
- Mohit Yadav Palam
- Aarej Syed
- Joshua Alvarado

## Dataset
Dataset is from Kaggle:
https://www.kaggle.com/datasets/keplersmachines/kepler-labelled-time-series-data

The full data files are not uploaded to GitHub because they are too large.

## Current Progress
- loaded data from Google Drive
- checked missing values
- checked class imbalance
- plotted sample light curves
- split train into train/validation using stratify
- standardized data with no leakage
- reshaped data for 1D CNN
- saved scaler
