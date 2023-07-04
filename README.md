# Time-Series-Analysis-on-Air-Quality-and-Weather-Prediction
This project focuses on the analysis and prediction of weather and air quality using various machine learning algorithms. The project employs linear regression, multilinear regression, decision tree, and LSTM (Long Short-Term Memory) models to predict weather and air quality parameters. Additionally, the project evaluates the models' performance by calculating error metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).

# Dataset
The project utilizes three dataset containing two historical weather dataset and one air quality data. The datasets include features such as temperature, humidity, wind speed, air pressure, and air quality index (AQI) etc. These features are used to train and test the machine learning models.All the datasets are available at kaggle (https://www.kaggle.com/)

# Algorithms and Techniques
The following algorithms and techniques are applied for weather and air quality prediction:

+ **Linear regression:**  Linear regression is used to model the linear relationship between the dependent variable (e.g., AQI) and independent variables (e.g., temperature, humidity). It helps in understanding the impact of individual features on the target variable.

+  **Multilinear Regression:** Multilinear regression extends linear regression to multiple independent variables. It considers the combined effect of multiple features on the target variable, enabling a more comprehensive analysis.
  
+  **Decision Tree:** Decision tree algorithms create a tree-like model of decisions and their possible consequences. Decision trees are used to capture non-linear relationships between the features and the target variable, providing a more accurate prediction.
  
+   **LSTM:** LSTM is a type of recurrent neural network (RNN) that excels at capturing temporal dependencies in time series data. LSTM models are specifically designed to handle sequence data and are well-suited for time series forecasting tasks.

# Evaluation Metrics
To assess the performance of the prediction models, the following error metrics are calculated:

+ **Mean Absolute Error (MAE):** MAE measures the average absolute difference between the predicted and actual values. It provides a measure of the average magnitude of errors.

+  **Mean Squared Error (MSE):** MSE measures the average squared difference between the predicted and actual values. It gives more weight to larger errors and is commonly used in regression tasks.

+  **Root Mean Squared Error (RMSE):** RMSE is the square root of the MSE. It represents the average magnitude of the prediction errors in the same units as the target variable.

# Usage 
To use this project and apply time series analysis on weather and air quality prediction:

1. Obtain the dataset containing historical weather and air quality data. Ensure that the dataset includes the required features and the target variable.
2. Prepare the dataset by cleaning the data, handling missing values, and performing feature engineering, if necessary. Split the dataset into training and testing sets.
3. Implement the desired machine learning algorithms (linear regression, multilinear regression, decision tree, LSTM) for weather and air quality prediction. Train the models using the training dataset.
4. Evaluate the trained models by calculating error metrics such as MAE, MSE, and RMSE. Compare the performance of different models to determine the most accurate prediction model.
5. Analyze the results and interpret the findings. Identify the factors that significantly influence weather and air quality and understand the models' predictive capabilities.
6. Optionally, visualize the predicted values against the actual values using plots or charts to gain further insights.

# License
This project is licensed under the [MIT License]
