# Cab Cancellation Prediction

This project focuses on predicting cab booking cancellations using machine learning techniques. The dataset contains booking details such as travel type, booking time, location information, and booking method.

## Project Objective
The goal of this project is to analyze cab booking data, perform data preprocessing, and build machine learning models to predict whether a cab booking will be cancelled or not.

## Key Steps in the Project
- Data Cleaning and Handling Missing Values
- Feature Engineering and Transformation
- Dataset Segmentation based on Travel Types
- Model Training and Evaluation

## Dataset Segmentation
The dataset is divided into three subsets based on `travel_type_id`:

- **Travel Type 1:** Long Distance Travel  
- **Travel Type 2:** Point-to-Point Travel  
- **Travel Type 3:** Hourly Rental  

Separate machine learning models are built for each subset to improve prediction accuracy.

## Feature Engineering
Important transformations include:
- Extracting time-based features (day, month, time of day)
- Calculating booking lead time
- Categorizing booking urgency
- Creating route-based features
- Handling location data and calculating travel distance

## Machine Learning Models Used
- Decision Tree
- Random Forest
- Naive Bayes Classifier

The performance of these models is compared to select the best-performing model for each travel type.

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

## Outcome
The project demonstrates how proper data preprocessing and segmentation can improve the performance of machine learning models in real-world prediction problems such as cab cancellation forecasting.# cab-cancellation-prediction-ml
Cab Cancellation Prediction using Machine Learning. Includes data cleaning, feature engineering, and classification models (Decision Tree, Random Forest, Naive Bayes) built separately for different travel types.
