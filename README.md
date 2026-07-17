# California Housing Price Prediction Using Linear Regression & K-Means Clustering

## Overview

This project explores the California Housing dataset using both supervised and unsupervised machine learning techniques.

The project focuses on predicting housing prices with **Linear Regression** and discovering hidden patterns in the data using **K-Means Clustering**. It also includes data preprocessing, feature engineering, visualization, and model evaluation.

---

## Dataset

The project uses the **California Housing** dataset, which contains information about housing districts in California.

### Features

- Longitude
- Latitude
- Housing Median Age
- Total Rooms
- Total Bedrooms
- Population
- Households
- Median Income
- Ocean Proximity

### Target Variable

- **Median House Value**

---

## Project Workflow

### 1. Data Loading

- Load the dataset
- Display sample records
- Inspect dataset dimensions

### 2. Exploratory Data Analysis (EDA)

- Explore data types
- Generate descriptive statistics
- Check for missing values
- Detect duplicate records

### 3. Data Preprocessing

- Handle missing values
- Encode categorical variables
- Select features and target variable
- Split the dataset into training and testing sets
- Standardize numerical features

### 4. Linear Regression

A Linear Regression model is trained to predict housing prices.

The model is evaluated using:

- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

### 5. K-Means Clustering

K-Means Clustering is applied to group similar housing districts.

The process includes:

- Selecting clustering features
- Feature scaling
- Determining the optimal number of clusters using the Elbow Method
- Training the K-Means model
- Assigning cluster labels

### 6. Data Visualization

The notebook includes several visualizations to better understand:

- Data distribution
- Feature relationships
- Cluster formation
- Model performance

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## Machine Learning Techniques

### Supervised Learning

- Linear Regression

### Unsupervised Learning

- K-Means Clustering

---

## Results

This project demonstrates the complete workflow of a machine learning pipeline, from data preprocessing to model training and evaluation.

- Linear Regression was used to predict median house values.
- K-Means Clustering was used to identify groups of similar housing districts.
- Feature scaling improved the performance of both machine learning models.
- The Elbow Method was used to determine an appropriate number of clusters.
- K-Means Clustering was used to identify groups of similar housing districts.
- Feature scaling improved the performance of both machine learning models.
- The Elbow Method was used to determine an appropriate number of clusters.
