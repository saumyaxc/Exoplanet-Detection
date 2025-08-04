# Exoplanet Detection

This project explores the use of machine learning techniques to identify potential exoplanets using data from NASA's Kepler Space Telescope. The dataset includes observed light curves and associated stellar properties, which are used to train models for binary classification of exoplanet candidates.

## Overview

The Kepler telescope monitored the brightness of stars to detect periodic dips that may indicate a planet transiting in front of the star. Using extracted features such as orbital period, transit depth, and stellar radius, this project builds classifiers to predict the presence of an exoplanet.

## Dataset

We use the [Kepler Labelled Time Series Data](https://www.kaggle.com/datasets/keplersmachines/kepler-labelled-time-series-data) hosted on Kaggle. It includes:
- Pre-processed light intensity curves for each star
- **Labels**: 2 (confirmed exoplanet), 1 (candidate), 0 (false positive)

> Note: The data is originally from the NASA Kepler Mission.
