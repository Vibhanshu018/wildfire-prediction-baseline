# Wildfire Prediction Baseline

This project implements a simple machine learning model to predict wildfire risk using weather data such as temperature, humidity, and wind.

## Approach

* Used RandomForestClassifier
* Features: temperature, humidity, wind
* Binary classification: fire / no fire

## Results

* Model trained and evaluated using train-test split
* Feature importance analysis performed

## Motivation

This serves as a baseline model for a larger wildfire prediction system that can later incorporate:

* Satellite imagery (NDVI, Sentinel data)
* Deep learning (CNN for spatial features)
* Time-series models (LSTM)

## Future Work

* Add satellite-based vegetation indices
* Improve temporal modeling
* Handle real-world geospatial data
