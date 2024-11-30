# Data-Science

# **Big Sales Prediction Using Random Forest Regressor**

This project demonstrates how machine learning can be used to predict product sales across various stores using a **Random Forest Regressor** model. The goal is to help businesses optimize inventory, marketing strategies, and staffing by accurately predicting future sales based on historical data.

## **Table of Contents**
- [Objective](#objective)
- [Data Source](#data-source)
- [Data Preprocessing](#data-preprocessing)
- [Modeling](#modeling)
- [Evaluation](#evaluation)
- [Results](#results)
- [License](#license)

## **Objective**
The goal of this project is to predict sales of products in various stores by analyzing product features, store characteristics, and location data. By building a robust sales prediction model, businesses can optimize their operations, including inventory management, marketing, and staffing.

## **Data Source**
The dataset used in this project, **Big Sales Data**, is sourced from the YBI Foundation GitHub repository.

## **Data Preprocessing**
- Missing values in the `Item_Weight` column are filled using the mean weight of the respective item type.
- Categorical variables such as `Item_Fat_Content`, `Item_Type`, and `Outlet_Identifier` are encoded into numerical values to make them suitable for machine learning models.
- Selected features are standardized to have zero mean and unit variance.

## **Modeling**
A **Random Forest Regressor** model is trained on the data to predict the sales. The data is split into a training set (70%) and a test set (30%), and the model is evaluated using metrics like **Mean Squared Error**, **Mean Absolute Error**, and **R-squared**.

## **Evaluation**
The model’s performance is assessed using the following metrics:
- **Mean Squared Error (MSE)**
- **Mean Absolute Error (MAE)**
- **R-squared (R²) score**

A scatter plot is created to compare actual vs. predicted sales values.

## **Results**
The model provides accurate sales predictions, helping businesses forecast sales trends and optimize operations. The evaluation metrics confirm that the model performs well on unseen data, demonstrating its reliability.
 
