# Emissions Forecasting Using ARIMA

## How to Use This Repository

This repository contains all the necessary components to forecast emissions from multiple sources (like flaring, venting, and power generation) using the ARIMA model. The structure of the repository is as follows:

### DATA

This folder contains the CSV file with historical emissions data for various sources. The data is crucial for running the forecasting models.

### NOTEBOOK

This folder includes the Jupyter notebook, which provides a step-by-step guide to loading the data, setting up ARIMA models, forecasting emissions for individual sources, and visualizing total emissions.

### DASHBOARD

This folder contains the scripts and visualizations that assist in analyzing emissions forecast results, offering insights through interactive dashboards.

----------

## Business Use Case

![enter image description here](https://i.pinimg.com/736x/60/60/f2/6060f272a12cc311bc7dfe6d13a19caa.jpg)

Forecasting emissions is critical for ADNOC to make data-driven decisions and meet regulatory requirements. This project enables ADNOC to:

-   **Forecast emissions for each source** (like flaring, venting, and power generation) to manage environmental impact.
-   **Plan proactively** to avoid regulatory breaches by forecasting total emissions.
-   **Optimize operations** by visualizing and predicting where emissions might spike in the future, allowing for better planning.

----------

## Project Structure

![enter image description here](https://i.pinimg.com/736x/44/da/14/44da1474bff6159da1fe39c7b4eba7ca.jpg)

### Step 1: Loading the Emissions Data

The first step is loading the emissions data into a pandas DataFrame. This data includes emissions from different sources (flaring, venting, power generation), providing a foundation for our forecasting efforts.

### Step 2: Understanding ARIMA

ARIMA (AutoRegressive Integrated Moving Average) is a time series forecasting technique that uses historical patterns to predict future values. This step explains how ARIMA works and why it's suitable for predicting emissions.

### Step 3: Setting Up the ARIMA Models for Each Emission Source

In this step, an ARIMA model is applied to each source of emissions. The notebook provides code to create subplots comparing actual vs. forecasted emissions, offering a clear view of future trends for each source.

### Step 4: Forecasting Total Emissions

Once individual sources are forecasted, the total emissions are summed up to predict overall emissions. A final plot compares observed and forecasted total emissions, with a safety limit marked to ensure ADNOC stays within regulatory compliance.

----------

## Dashboard

![enter image description here](https://i.pinimg.com/736x/89/25/bf/8925bfb9c94f73e5d66fe88f064bd864.jpg)

The dashboard section provides a visual overview of the emissions forecasts, allowing users to interact with the data and filter by emission source. This helps ADNOC prioritize areas of concern and focus on reducing emissions.

----------

## Conclusion

This project demonstrates how ARIMA can be leveraged to forecast emissions from multiple sources. With this forecasting model, ADNOC can make more sustainable and efficient decisions by staying ahead of environmental regulations and managing operational emissions effectively.
