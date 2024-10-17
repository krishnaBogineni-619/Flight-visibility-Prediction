# Flight Visibility Prediction Based on Weather Factors

## Overview

This project aims to predict flight visibility based on various weather factors such as temperature, humidity, wind speed, pressure, and precipitation. The dataset used contains several meteorological variables, and machine learning techniques are employed to model visibility and identify key influencing factors.

## Dataset

The dataset used for this project includes the following features:

- **VISIBILITY**: Visibility in miles (target variable)
- **DRYBULBTEMPF**: Dry bulb temperature in Fahrenheit
- **WETBULBTEMPF**: Wet bulb temperature in Fahrenheit
- **DewPointTempF**: Dew point temperature in Fahrenheit
- **RelativeHumidity**: Relative humidity as a percentage
- **WindSpeed**: Wind speed in miles per hour
- **WindDirection**: Wind direction in degrees
- **StationPressure**: Station pressure in inches of Hg
- **SeaLevelPressure**: Sea level pressure in inches of Hg
- **Precip**: Precipitation amount in inches

## Libraries and Tools

This project uses the following libraries and tools:

- **Pandas**: Data manipulation and analysis
- **Matplotlib** and **Seaborn**: Data visualization
- **Plotly**: Interactive plotting
- **NumPy**: Numerical operations
- **Scikit-learn**: Machine learning algorithms, including:
  - **StandardScaler**: Data normalization
  - **PCA**: Principal Component Analysis for dimensionality reduction
  - **KMeans**: Clustering
- **MLxtend**: Association rule learning (optional)
- **Warnings**: For handling warnings in code

## Methodology

1. **Data Preprocessing**: 
   - Handle missing values.
   - Standardize the features using  for consistency.
   - Perform exploratory data analysis (EDA) to understand the relationships between variables.
   
2. **Principal Component Analysis (PCA)**:
   - Use PCA to reduce the dimensionality of the dataset, ensuring the major variance in the data is captured.

3. **Clustering (Optional)**:
   - Apply KMeans clustering to group similar weather conditions based on the input features.

4. **Modeling**:
   - Train a regression model (such as Linear Regression or Decision Trees) to predict visibility based on the weather factors.
   
5. **Evaluation**:
   - Evaluate model performance using metrics such as Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R-squared.

## Results

- **Prediction Accuracy**: Summary of the model's accuracy in predicting flight visibility.
- **Key Features**: Identify the most significant weather factors that influence visibility.
