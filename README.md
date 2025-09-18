# Bike-sharing Regression Analysis

Course project from **MSG400: Model Choice in Linear Regression**.  
The analysis uses London bike-sharing data (2015–2017) to study the relationship between rentals, weather conditions, and time of day.

## Contents
- **Exploratory Data Analysis (EDA):** seasonal and hourly rental patterns
- **Transformations:** Box–Cox transformation of the response, nonlinear covariate transformations (humidity^γ)
- **Prediction:** simulation-based prediction intervals
- **Model Validation:** comparison of models via predictive MSE (pMSE), repeated train/test splits
- **Inference:** empirical coverage rates of confidence intervals

## Technology
- **Language:** R  
- **Packages:** tidyverse, ggplot2, quantmod, rugarch

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/almidathorjesson/bike-sharing-regression.git
   cd bike-sharing-regression
