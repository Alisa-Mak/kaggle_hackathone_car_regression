# 2024 Kaggle Playground Series - Car Price Prediction

This repository contains the code and resources for the Kaggle competition ["Predict Used Car Prices."](https://www.kaggle.com/competitions/playground-series-s4e9/overview) The goal is to predict the prices of used cars based on various attributes provided in the dataset.

## Used Car Price Prediction

- The used car market is growing rapidly, with millions of transactions happening every year. Given the sheer volume of cars available, determining the appropriate price for a used car can be quite challenging. Prices are influenced by various factors such as brand, model, year, mileage, fuel type, and accident history, among others.

- Accurately estimating the price of a used car is crucial for both sellers and buyers. However, manually analyzing all these factors to set the right price is time-consuming. This is where Artificial Intelligence (AI) comes into play.

## Competition Overview

- **Competition Start**: August 31, 2024
- **Competition End**: September 30, 2024
- **Evaluation Metric**: Root Mean Squared Error (**RMSE**)
- **Goal**: Predict the price of used cars based on the provided attributes.

## Dataset

The dataset used in this competition was generated from a deep learning model trained on the original [Used Car Price Prediction Dataset](https://www.kaggle.com/datasets). While the feature distributions are similar to the original dataset, they are not identical. Participants can use both the original and the competition-specific datasets for training and analysis.

## Column Descriptions

| Column        | Description                                                         |
|---------------|---------------------------------------------------------------------|
| `id`          | Unique identifier for each car                                      |
| `brand`       | The brand or manufacturer of the car                                |
| `model`       | The specific model of the car                                       |
| `model_year`  | The year the car model was manufactured                             |
| `mileage`     | The total distance the car has traveled (in kilometers/miles)       |
| `fuel_type`   | The type of fuel the car uses (e.g., petrol, diesel, electric)      |
| `engine`      | Engine capacity, typically measured in liters                       |
| `transmission`| The type of transmission (e.g., manual, automatic)                  |
| `ext_col`     | The exterior color of the car                                       |
| `int_col`     | The interior color of the car                                       |
| `accident`    | Whether the car has been involved in an accident                    |
| `clean_title` | Whether the car has a clean title (i.e., no legal issues)           |
| `price`       | The target variable representing the car's price                    |

Here’s a concise summary of the models used and their predictions that you can include in your README:

### Models Used:
- **Random Forest**: Implemented for initial predictions based on ensemble learning.
- **XGBoost (XGB)**: Utilized for its high performance in regression tasks.
- **Neural Networks (NN)**: Developed multiple architectures:
  - **NN1**: Basic structure with standard layers.
  - **NN2**: Enhanced with dropout layers for regularization.
  - **NN3**: Deeper architecture for improved learning capacity.
- **TabNet**: Applied for its ability to handle tabular data efficiently.
- **CatBoost**: Used for its effectiveness with categorical features.

### Predictions:
- Generated predictions from the Random Forest, Neural Networks, and TabNet models to compare performance and accuracy.
