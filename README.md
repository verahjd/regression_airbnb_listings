# Airbnb Listing Demand Forecasting

A regression analysis project focused on predicting the popularity of Airbnb 
listings using review frequency as a demand proxy across 7 major cities worldwide.

## Overview

This project provides an end-to-end regression pipeline for:

- **Data Acquisition:** Dataset sourced from the Airbnb Listings dataset on Kaggle.
- **Exploratory Data Analysis (EDA):** Statistical exploration of listing features 
  and their correlation with review frequency.
- **Preprocessing:** Handling missing values, log transformation of skewed target 
  variable, and one-hot encoding of categorical features.
- **Modeling:** Multiple Linear Regression to predict `reviews_per_month` as a 
  proxy for listing demand.

## Technical Stack

- **Language:** Python 3.12
- **Environment:** Google Colab / Jupyter
- **Primary Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, 
  `statsmodels`

## Dataset Information

The analysis utilizes the 
[Airbnb Listings: NYC, London, Paris, Tokyo & More](https://www.kaggle.com/datasets/darkmatternet/airbnb-listings-nyc-london-paris-tokyo-and-more) 
dataset from Kaggle. Key features include:

- **Listing Attributes:** Room type, price, minimum nights, availability.
- **Host Information:** Calculated host listings count.
- **Location:** City (London, Paris, Rome, Bangkok, Barcelona, Sydney, Amsterdam).
- **Target Variable:** `reviews_per_month` (used as a proxy for booking demand).

## Key Findings

- The model achieved an **R² of 0.074**, indicating that basic listing 
  characteristics explain approximately 7.4% of the variance in review frequency.
- Listing popularity is likely driven by factors outside this dataset such as 
  photo quality, host responsiveness, and guest experience.
- The low R² is itself a meaningful finding, suggesting that demand forecasting 
  for Airbnb listings requires richer, non-structured data.

## Execution Instructions

1. Open the Google Colab Notebook.
2. Upload the dataset CSV from Kaggle to your Colab environment.
3. Select **Runtime** > **Run all**.

---

**Author:** Verah Dulay  
**Date:** April 2026
