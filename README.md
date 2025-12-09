# Homogeneous Interval Temporal Aggregation with Application in Trip-Based Fuel Consumption Prediction

**Author**: Mahnaz Golshan  
**Contact**: mahnaz.golshan@hec.ca

## Overview

This repository contains the Python code and data used in the research article:

> _Homogeneous Interval Temporal Aggregation with Application in Trip-Based Fuel Consumption Prediction_

Many forecasting tasks in transportation, energy, and environmental domains require estimating the **total value** of a time series under different input scenarios. In such cases, while the target series is unknown, covariates can be specified or simulated—making **total-series prediction** a central part of scenario-based analysis.

This work introduces a novel Temporal Aggregation (TA) method called **Homogeneous Interval Aggregation (HIA)**. Unlike traditional TA techniques that use fixed-length intervals, HIA uses covariate patterns to define **variable-length temporal intervals** where covariate behavior is relatively stable. Within each interval, both the target and covariates are summarized using multiple statistical features, and a predictive model estimates total values by summing interval-level predictions.

The method is applied to second-by-second vehicle trip data to predict **total fuel consumption** using features like speed, acceleration, slope, and vehicle characteristics. Empirical results on 394 gasoline vehicle trips show that HIA outperforms benchmark methods in both **prediction accuracy** and **computation time**.

## Repository Contents

- `code/` — Python (Colab) notebook implementing the HIA method and experiments  
- `data/` — Excel files containing vehicle trip data used in the study

## How to Use

1. Open the Colab notebook in the `/code/` folder using [Google Colab](https://colab.research.google.com/).
2. Follow the instructions in the notebook to run the full pipeline.
3. Make sure to upload the Excel data files from the `/data/` folder when prompted in Colab.

## Reproducibility

This repository is intended to support transparency, reproducibility, and further development. Users are encouraged to reuse and adapt the method for other time series forecasting tasks involving scenario-based total prediction.

## Citation

If you use this code or data in your own research, please cite the corresponding article (citation info to be added once available).
