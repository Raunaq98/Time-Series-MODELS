# Time-Series-MODELS

For ***mostly or completely random*** ata, simple time series forecasting models work the best while advanced models are used to exploit trends, seasonality etc. There are 3 simple time series models:

      1. Naive Method
      2. Average Method
      3. Drift Method
      
# Simple Methods

## Naive Method

It is a ***last observation carried forward*** method. It projects the last known observation into thee future. 
For Example, to forecast Feb 2018, we usee the value of last observed Feb 2017.
This method works **remarkably well** for many economic and financial time series

## Average Method

It calculates the mean of the datapoint and projects it into the future.

## Drift Method

It calculates the difference between the first and last observation and projects it into the future.

# Akaike Information Criterion (AIC)

Akaike’s information criterion (AIC) compares the quality of a set of statistical models to each other. The AIC will take each model and rank them from best to worst. The “best” model will be the one that neither under-fits nor over-fits.

**Min AIC is the score for the “best” model.**
