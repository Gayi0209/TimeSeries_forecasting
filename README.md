# PJME Energy Usage Forecasting

## Overview

This project focuses on forecasting **PJME (Pennsylvania, Jersey, Maryland Electric)** energy usage using a time series analysis and machine learning approach. By leveraging historical energy usage data, we aim to build a predictive model to forecast future energy consumption. The model is implemented using Python and XGBoost, a powerful gradient boosting algorithm.

## Getting Started

To run this project locally, follow these steps:

### Prerequisites

- Python 3.7+
- Pandas
- NumPy
- Matplotlib
- Seaborn
- XGBoost
- Scikit-learn

## Project Structure

1. **Data Loading and Preprocessing**: 
   - Load the dataset and perform preprocessing, such as setting the correct datetime index and splitting the data into training and testing sets.

2. **Exploratory Data Analysis (EDA)**:
   - Visualize trends, seasonality, and other patterns in the energy usage data.

3. **Feature Engineering**:
   - Create time-based features such as hour, day of the week, month, and year to enhance the model's ability to capture temporal patterns.

4. **Model Training**:
   - Train an XGBoost regressor on the features, fine-tuning hyperparameters such as `n_estimators` and `learning_rate` for optimal performance.

5. **Model Evaluation**:
   - Evaluate the model's performance using Root Mean Squared Error (RMSE) and visual comparisons between the predicted and actual energy usage.

6. **Error Analysis**:
   - Analyze prediction errors to identify areas where the model may be underperforming.

## Usage

1. **Data Preprocessing**: 
   - Ensure your dataset is properly formatted and stored in the correct directory.

2. **EDA**: 
   - Explore the data using the visualizations provided in the EDA script.

3. **Feature Engineering**: 
   - Create additional features if necessary to improve the model.

4. **Model Training**: 
   - Train the model on the training data and evaluate it using the testing data.

5. **Error Analysis**: 
   - Analyze errors to gain insights into the model's performance.

## Key Features

- **Time Series Analysis**: Utilizes various time-based features such as hour, day of the week, month, and year to capture seasonal patterns in energy usage.
- **Machine Learning with XGBoost**: Employs XGBoost, a powerful gradient boosting algorithm, to train the model on historical data and predict future energy consumption.
- **Data Visualization**: Includes detailed visualizations to explore the data, understand trends, and evaluate model performance.

## Benefits of the Project

- **Improved Forecast Accuracy**: By leveraging XGBoost, the model achieves a high level of accuracy, reducing the Root Mean Squared Error (RMSE) on the test set.
- **Scalability**: The model is capable of handling large datasets and can be easily adapted to other regions or sectors.
- **Energy Management**: Provides valuable insights that can be used by energy providers to optimize resource allocation and improve grid stability.
- **Cost Efficiency**: Accurate forecasts help in reducing energy wastage and managing demand, leading to cost savings for both providers and consumers.

## Results

The model successfully predicts future energy usage with an RMSE score on the test set, indicating strong performance in capturing trends and seasonal patterns in the data.
