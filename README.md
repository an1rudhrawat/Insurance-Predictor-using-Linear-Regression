# Insurance Cost Predictor using Linear Regression

## Overview

This project was created as part of my Machine Learning learning journey. The main goal was to understand how Linear Regression works by applying it to a real-world dataset containing health insurance information.

Using factors such as age, BMI, smoking habits, gender, and region, the model predicts an individual's insurance charges.

## Why I Made This Project

I built this project to:

- Learn the fundamentals of Machine Learning.
- Understand the complete workflow of a regression problem.
- Practice data preprocessing and feature engineering.
- Gain hands-on experience with Scikit-Learn.
- Learn how model performance is evaluated using the R² score.

As one of my first Machine Learning projects, this helped me move beyond theory and apply concepts to a real dataset.

## Dataset Features

The dataset contains the following information:

- Age
- Sex
- BMI (Body Mass Index)
- Number of Children
- Smoker Status
- Region
- Insurance Charges (Target Variable)

## Technologies Used

- Python
- Pandas
- Seaborn
- Scikit-Learn
- Jupyter Notebook

## Project Workflow

### 1. Data Loading
The insurance dataset is loaded using Pandas.

### 2. Data Exploration
Basic inspection and visualization are performed to understand relationships between features and insurance charges.

### 3. Data Preprocessing
- Categorical variables are converted into numerical values.
- Region data is encoded using one-hot encoding.
- Features and target variables are separated.

### 4. Train-Test Split
The dataset is split into training and testing sets to evaluate model performance.

### 5. Model Training
A Linear Regression model is trained using Scikit-Learn.

### 6. Feature Engineering
Additional interaction features are created:

- age × smoker
- bmi × smoker

These features help capture the stronger effect smoking has on insurance costs.

### 7. Model Evaluation
Performance is measured using the R² Score on both training and testing datasets.

## Results

The model demonstrates how Linear Regression can be used to predict continuous values such as insurance charges. Feature engineering further improves the model by capturing important relationships within the data.

## What I Learned

Through this project, I learned:

- Data preprocessing techniques
- Handling categorical variables
- Train-test splitting
- Building Linear Regression models
- Feature engineering
- Model evaluation using R² Score
- End-to-end Machine Learning workflow

## Future Improvements

- Try advanced regression models such as Random Forest and XGBoost.
- Perform hyperparameter tuning.
- Build a web interface using Flask or Streamlit.
- Deploy the model online.
- Compare multiple algorithms and evaluation metrics.

## Author

Anirudh Singh Rawat

This project is part of my Machine Learning learning journey and serves as a foundation for more advanced ML projects.
