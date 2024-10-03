# CTC-Prediction-Based-on-Various-Factours-using-Machine-Learning

## Overview

This project aims to predict the Cost to Company (CTC) for employees based on various features such as their previous CTC, job change history, graduation marks, experience, and more. The goal is to provide an accurate estimation of an employee's potential CTC, which can be valuable for HR departments and recruitment agencies. This project is an unguided project and I made it on my own using datasets only.

## Problem Statement

In the competitive job market, predicting an employee's potential CTC is crucial for making informed hiring decisions. Various factors, such as previous CTC, job change history, educational background, and work experience, play a significant role in determining the CTC. This project focuses on developing a predictive model that leverages these features to estimate the CTC accurately. The key objectives include:

- Preprocessing and analyzing the employee, college, and city datasets.
- Encoding categorical variables into numerical formats.
- Normalizing and merging the datasets for model training.
- Training different regression models to predict CTC and then choosing best among them.
- Evaluating the model's performance and identifying areas for improvement.

## Dataset

The project uses three primary datasets:

1. **Employee Data**: Contains information about employees such as previous CTC, job change history, graduation marks, experience, and current role.
2. **College Data**: Contains information about colleges attended by the employees.
3. **Cities Data**: Contains information about the cities where the employees are located.

## Data Preprocessing

The preprocessing steps include:

- Checking for and handling missing values.
- Encoding categorical variables (colleges and cities) into numerical form.
- Normalizing the data using a scaler function.
- Merging the datasets into a unified DataFrame.
- Removing outliers.

## Model Training

The Random Forest algorithm was selected for model training due to its robustness and ability to handle both numerical and categorical features. The steps include:

- Splitting the data into training and test sets.
- Training the various Regression model on the training data.
- Saving the trained model for future use.

## Evaluation

The model was evaluated using the R² score, and the performance was visualized using various plots. The results indicated areas where the model can be further refined and improved.

## Results

- The Random Forest model provided a reasonable estimation of CTC based on the given features.
- The model's performance can be further improved by tuning hyperparameters or trying different algorithms.






