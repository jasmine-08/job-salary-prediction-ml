# Job Salary Prediction Using Machine Learning

## Project Overview

This project focuses on predicting employee salaries using machine learning techniques.

The project uses job-related and employee-related features to build and compare different regression models for salary prediction.

## Objective

The main objective of this project is to develop a machine learning model that can predict employee salaries and compare the performance of different regression algorithms.

## Dataset

The dataset contains job-related and employee-related information such as:

- Job Title
- Experience
- Education Level
- Skills Count
- Industry
- Company Size
- Location
- Remote Work
- Certifications

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab
- GitHub

## Project Workflow

1. Data Loading
2. Data Exploration
3. Data Preprocessing
4. Exploratory Data Analysis
5. Feature Encoding
6. Correlation Analysis
7. Train-Test Split
8. Model Training
9. Model Evaluation
10. Model Comparison

## Machine Learning Models

The following regression models were implemented and compared:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

## Model Performance

| Model | R² Score |
|---|---:|
| Linear Regression | 0.4560 |
| Decision Tree Regressor | 0.9309 |
| Random Forest Regressor | 0.9689 |

## Best Model

The **Random Forest Regressor** achieved the best performance with an **R² score of 0.9689**.

Other evaluation metrics included:

- MAE: approximately 5195
- RMSE: approximately 6573

## Key Finding

The analysis showed that **location** was the most influential feature in the model, followed by experience, company size, and job title.

## Project Notebook

The complete Python implementation, analysis, visualizations, and model evaluation are available in the Jupyter Notebook included in this repository.

## Google Colab

The project was developed using Google Colab.

[Open Project in Google Colab](https://colab.research.google.com/drive/1xQtcLDWbE4TfUxVcAiCwhNrEGEJdEoL6?usp=sharing)

## Future Improvements

- Hyperparameter tuning
- Feature selection
- Cross-validation
- Testing additional machine learning algorithms
- Deployment as a web application
