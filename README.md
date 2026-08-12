
# Case Studies in Data Science — Individual Task 1

This repository contains the data cleaning and machine learning code developed for Individual Task 1 (Part 1) of Case Studies in Data Science at RMIT University.

## Contents
- `analysis.ipynb` — Jupyter notebook containing data loading, cleaning, and two machine learning models

## Datasets
- **Pedestrian Counting System – Monthly Counts per Hour** (City of Melbourne Open Data)[https://data.melbourne.vic.gov.au/explore/dataset/pedestrian-counting-system-monthly-counts-per-hour/]
- **On-Street Parking Bay Sensors** (City of Melbourne Open Data)[https://data.melbourne.vic.gov.au/explore/dataset/on-street-parking-bay-sensors/]

## Models
- **Decision Tree Classifier** — predicts parking bay occupancy (occupied/unoccupied) from location and zone features
- **Random Forest Regressor** — predicts hourly pedestrian counts from time and location features

## Process notes
The notebook includes the cleaning steps applied to each dataset (handling missing values, converting date fields, splitting combined location fields into latitude/longitude), model training, evaluation, and issues encountered during development (e.g. a deprecated scikit-learn parameter) along with how they were resolved.
