# StarScope Exoplanet Detection

## Goal
Build a model to classify stars as having exoplanets based on light curves

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
- standardized data (fit on train only to avoid leakage)
- reshaped data for 1D CNN
- saved scaler
- ready for model training

## How to Run

1. Download dataset from Kaggle link above
2. Upload to Google Drive under:
   Colab Notebooks/CS4375_Project/data/
3. Open notebook in Colab and run all cells
