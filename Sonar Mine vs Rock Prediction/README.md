# Sonar Rock vs Mine Prediction

This project aims to predict whether an object detected by sonar is a rock or a mine based on various features.

## Introduction

This project utilizes machine learning techniques, specifically logistic regression, to predict whether an object detected by sonar is a rock or a mine. The dataset used for this project contains sonar readings along with corresponding labels indicating whether the detected object is a rock (R) or a mine (M).

## Getting Started

To get started with this project, follow these steps:

1. **Data Collection**: The dataset used in this project is available at `/content/dataset.csv`. Ensure that you have access to this dataset.

2. **Environment Setup**: You can run the provided Jupyter notebook `SONAR Rock vs Mine Prediction.ipynb` in a suitable environment. The notebook is designed to be executed in a Google Colab environment.

3. **Libraries Used**: The project utilizes the following Python libraries:
   - NumPy
   - Pandas
   - scikit-learn (for model training and evaluation)

## Model Training and Evaluation

The project follows these steps for model training and evaluation:

1. **Data Preprocessing**: The dataset is preprocessed to handle any missing values and to separate features (`x`) from labels (`y`).

2. **Model Training**: Logistic regression model is trained on the training data (`x_train`, `y_train`).

3. **Model Evaluation**: The accuracy of the trained model is evaluated using both training and test data. The accuracy scores are printed to assess the model's performance.

## Making Predictions

The trained model is capable of making predictions on new data. To make predictions, follow these steps:

1. **Input Data**: Provide the features of the object detected by sonar as input. The features should be in the same format as the original dataset.

2. **Prediction**: The model predicts whether the object is a rock or a mine based on the provided input data.

