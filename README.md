# Short-Term Solar Irradiance Forecasting and Agent-Based Energy Management

This repository contains the source code developed for the study:

**“Short-Term Solar Irradiance Forecasting Using Deep Learning Models and an Agent-Based Decision Support Framework for Localized Energy Management.”**

The project implements deep learning models for short-term Global Horizontal Irradiance forecasting and an agent-based decision-support framework for localized solar energy management.

## Features

The repository includes:

- Data cleaning and preprocessing
- Missing-value imputation
- Outlier handling
- Feature engineering
- Cyclical time encoding
- Robust scaling
- Time-series sequence generation
- LSTM, GRU, and TCN forecasting models
- Single-station RNN and LSTM forecasting
- Agent-based battery and grid decision simulation
- Model evaluation using MAE, RMSE, and R²
- Statistical significance analysis

## Dataset

The dataset used in this study is publicly available from the World Bank Energy Sector Management Assistance Program, ESMAP.

Dataset name:

**Pakistan Solar Radiation Measurement Data**

The dataset contains ground-based solar radiation and meteorological measurements recorded at 10-minute intervals from nine stations in Pakistan between 2014 and 2017.

The original dataset is not redistributed in this repository.

Download data from;

https://datacatalog.worldbank.org/search/dataset/0038550/pakistan-solar-radiation-measurement-data

After downloading, place the dataset files inside the following folder:

```text
data/raw/

## Code Availability

The source code associated with this study is archived on Zenodo.

**Version 1.0.0 DOI:** https://doi.org/10.5281/zenodo.21461511
