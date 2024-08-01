# Housing Price Prediction (Using Multiple Linear Regression Model)

## Introduction

In real estate, linear regression helps in understanding property prices by analyzing various factors that influence them.

This project aims to predict house prices based on different features of the property. The dataset includes several variables that can affect house prices, such as the property's area, the number of bedrooms and bathrooms, the number of stories, and the presence of amenities like parking, air conditioning, and heating.

## Problem Statement

A real estate company in Delhi wants to optimize the selling price of its properties by considering critical factors such as the area, number of bedrooms, and various amenities. The objective is to build a multiple linear regression model that can accurately predict property prices based on these factors.

## Dataset Description

The dataset includes the following columns:

- **price:** The target variable representing the price of the property.
- **area:** The area of the house or apartment.
- **bedrooms:** The number of bedrooms.
- **bathrooms:** The number of bathrooms.
- **stories:** The number of stories.
- **mainroad:** Indicates if the property is close to a main road (yes/no).
- **guestroom:** Indicates if there is a guestroom (yes/no).
- **basement:** Indicates if there is a basement (yes/no).
- **hotwaterheating:** Indicates if hot water heating is available (yes/no).
- **airconditioning:** Indicates if air conditioning is present (yes/no).
- **parking:** Indicates if parking space is available (yes/no).
- **prefarea:** Indicates if the property is in a preferred area (yes/no).
- **furnishingstatus:** Shows the furnishing status of the property (furnished, semi-furnished, or unfurnished).

## Model Approach

The multiple linear regression model will be developed using backward selection. This method involves:

1. Starting with all potential predictor variables.
2. Iteratively removing the least significant variables based on statistical criteria.
3. Retaining the most important variables that significantly impact the model's predictive accuracy.

This technique helps in creating a robust model that effectively captures the factors influencing property prices while eliminating less relevant variables.



## Dependencies

- pandas
- numpy
- matplotlib
- seaborn
- sklearn
- statsmodel


