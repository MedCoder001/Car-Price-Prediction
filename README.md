# Car Price Prediction

## Introduction
This project focuses on predicting car prices using a machine learning model. The dataset used for this task contains various features such as engine specifications, mileage, and car details. By analyzing these features, the goal is to build a model that can accurately predict the price of a car.

## Data Source
The dataset used in this project is sourced from [this Link](https://raw.githubusercontent.com/alexeygrigorev/mlbookcamp-code/master/chapter-02-car-price/data.csv). It contains information about various cars including their specifications and prices.

## Approaches
- First the project starts by importing the dataset and performing initial data preprocessing steps. The dataset is cleaned, and features are standardized to ensure uniformity and consistency in the data.
  
- Exploratory data analysis is conducted to gain insights into the dataset and understand the distribution of car prices. Visualizations such as histograms are utilized to analyze the distribution of car prices and identify any potential patterns or trends.
  
- Feature engineering was done and it includes handling missing values, encoding categorical variables, and creating new features to improve the performance of the machine learning model.
  
- To the model building, a **linear regression model** is built to predict car prices based on the engineered features. The model is trained using the training dataset and evaluated using validation data to assess its performance.
  
- To prevent overfitting and improve generalization, regularized linear regression techniques such as Ridge regression are employed. Various regularization parameters are tested to find the optimal value that minimizes the model's error.

- The trained models are evaluated using the test dataset to assess their performance on unseen data. Evaluation metrics such as root mean squared error (RMSE) are used to quantify the models' accuracy in predicting car prices.

## Conclusion
This project was part of the **ML Zoomcamp Course** by DataTalksClub lessons taken by Alexey Grigorev. It demonstrates the process of building a machine learning model for car price prediction. By leveraging data preprocessing, feature engineering, and model building techniques, accurate predictions can be made regarding car prices and also further improvements and optimizations can be explored to enhance the model's performance and reliability.
