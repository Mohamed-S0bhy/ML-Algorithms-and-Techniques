# Salary Prediction Using Linear Regression

This project aims to predict salaries based on various features such as age, gender, education level, job title, and years of experience using a linear regression model. The dataset used for this project is provided in the repository.

## Project Overview

The primary goal of this project is to build a linear regression model to predict the salary of individuals based on their demographic and professional information. This project includes data preprocessing, exploratory data analysis (EDA), model building, and evaluation.

## Dataset

The dataset contains the following columns:
- `Age`: Age of the individual
- `Gender`: Gender of the individual
- `Education Level`: Highest education level attained by the individual
- `Job Title`: Job title of the individual
- `Years of Experience`: Number of years of professional experience
- `Salary`: Annual salary of the individual (target variable)

## Project Steps

1. **Data Loading and Preprocessing**
    - Handle missing values
    - Encode categorical variables
    - Scale/normalize the data if necessary

2. **Exploratory Data Analysis (EDA)**
    - Understand the distribution and relationships of the data

3. **Model Building**
    - Split the data into training and testing sets
    - Build and train a linear regression model

4. **Model Evaluation**
    - Evaluate the model’s performance using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared
    - Visualize the actual vs predicted salaries

## Requirements

- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib

## Installation

Clone the repository and install the necessary dependencies:

```bash
git clone https://github.com/your-username/salary-prediction.git
cd salary-prediction
pip install -r requirements.txt
	