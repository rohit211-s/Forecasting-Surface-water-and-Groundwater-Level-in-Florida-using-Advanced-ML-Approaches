# Forecasting-Surface-water-and-Groundwater-Level-in-Florida-using-Advanced-ML-Approaches

## Abstract

Effective water resource management and planning rely heavily on accurate forecasting of surface water discharge and groundwater levels, particularly in hydrologically intricate regions like Florida. This study conducts a large-scale analysis across the entire state of Florida, systematically evaluating the efficacy of five advanced deep learning models—Long Short-Term Memory (LSTM), Neural Basis Expansion Analysis for Interpretable Time Series Forecasting (N-BEATS), Neural Hierarchical Interpolation for Time Series (N-HiTS), Temporal Fusion Transformers (TFT), and Informer—using extensive datasets from 45 surface water stations and 45 groundwater monitoring wells, spanning 23 years (2001-2023). Unlike traditional methods that use different models for predicting surface water and groundwater, we demonstrate that the same models can effectively forecast both surface water discharge and groundwater levels. After rigorous data preprocessing, including cleaning and normalization, these models were trained and tested to predict daily water dynamics. Our analysis reveals that the N-HiTS model consistently delivers superior performance for both surface water discharge and groundwater levels. Specifically, N-HiTS was the best-performing model in 23 out of 45 groundwater wells based on Root Mean Square Error (RMSE), and in some wells, it achieved an RMSE that was 70% less than that of the next best model, TFT. N-HiTS led 34 out of 45 stations using Normalized RMSE (NRMSE) for surface water discharge, consistently achieving at least a 20% lower NRMSE than the next-best model in all leading stations. These findings demonstrate N-HiTS's exceptional ability to capture temporal dynamics in hydrological data, offering a powerful tool for enhancing predictive accuracy in water resource management. This research provides crucial insights into the application of deep learning models in hydrological forecasting, with significant implications for resource planning in Florida and similar regions.

