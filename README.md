# Fore Casting Emissions - Upstream Use Case

## How to Use This Repository

This repository contains all the components necessary to predict flaring emissions using operational data from oil rigs with a **Random Forest Regressor**. The structure of the repository is as follows:

-   **Data**: This folder contains the **adnoc_flaring_emissions_data.csv** file. This dataset includes features such as production volume, gas flaring rates, maintenance status, equipment health scores, and more. These features are critical inputs for predicting flaring emissions.
    
-   **Notebook**: This folder contains the Jupyter notebook that walks you through the entire process, from loading the data to preprocessing it, building a Random Forest model, and making predictions for emission reductions.
    
-   **Dashboard**: This folder includes any Power BI or other visualization dashboards used for monitoring predicted emissions and identifying trends.
    

## Business Use Case

Effective monitoring and prediction of flaring emissions are critical for optimizing upstream oil operations, reducing environmental impact, and ensuring compliance with regulatory requirements. This project leverages operational data and machine learning techniques to:

-   **Predict flaring emissions** based on real-time operational data, allowing ADNOC to optimize rig operations and reduce emissions.
-   **Enhance compliance** with local and international environmental regulations by providing accurate emission forecasts.
-   **Identify critical factors** affecting emissions, such as equipment health and flaring rates, enabling proactive interventions to minimize emissions.

## Project Structure

### Step 1: Loading and Analyzing Operational Data

The first step involves loading the operational data into a pandas DataFrame. This dataset forms the foundation for analyzing flaring activities. Instructions for loading the dataset are provided in the notebook, along with an initial exploration of the data to ensure it's ready for modeling.

### Step 2: Preprocessing the Data

Once the data is loaded, the next step is to preprocess the dataset. This includes removing irrelevant columns, scaling the features for better model performance, and splitting the data into training and testing sets. Proper preprocessing is crucial for building an accurate predictive model.

### Step 3: Building and Training the Random Forest Model

In this step, the notebook walks you through building the **Random Forest Regressor** model. You’ll learn how to select the right hyperparameters, fit the model to the training data, and make predictions on the test data. This model is the backbone of the flaring emissions prediction process.

### Step 4: Evaluating the Model’s Performance

After training the Random Forest model, you will evaluate its performance using key metrics like **Mean Squared Error (MSE)** and **R-squared (R²)**. These metrics help measure how well the model predicts emissions compared to actual flaring data. This step ensures that the model is reliable and can be used to guide operational decisions.

### Step 5: Visualizing Predicted vs. Actual Emissions

Visualizations play a key role in understanding the accuracy of the model’s predictions. In this step, the notebook guides you through creating scatter plots and residual plots to compare the predicted flaring emissions with actual values, providing insights into any discrepancies.

### Step 6: Analyzing Feature Importance

This step explores the factors that have the greatest impact on flaring emissions, such as equipment health scores or gas flaring rates. By analyzing feature importance, ADNOC can focus on improving the operational factors that most significantly affect emissions.

## Dashboard

The **Dashboard** folder contains the Power BI dashboard used to visualize predicted emissions, identify trends, and monitor key indicators in real-time. The dashboard provides actionable insights to optimize operations and reduce flaring emissions.

## Conclusion

This project demonstrates how operational data combined with machine learning techniques can significantly improve the accuracy of flaring emissions predictions. By integrating data analysis, preprocessing, model training, and visualization, this approach enables more informed upstream operational decisions, ultimately saving time, resources, and reducing the environmental impact of oil extraction activities.
