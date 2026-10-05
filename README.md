# Machine Learning Analysis of Sleep Health

This project investigates how lifestyle and health-related variables are connected to sleep duration and sleep disorders.

The work was completed in two stages as part of the DTU course **02452 Machine Learning**:

1. Exploratory data analysis and Principal Component Analysis (PCA)
2. Predictive modelling using regression and classification methods

The second stage builds directly on the first, using the cleaned data and PCA results as input for the machine learning models.

## Project Workflow

- Data preprocessing and cleaning
- Descriptive statistics
- Data visualisation
- Correlation analysis
- Principal Component Analysis (PCA)
- Linear and Ridge Regression
- Artificial Neural Network
- Logistic Regression
- K-Nearest Neighbors
- Nested cross-validation
- Statistical model comparison

## Regression

The regression task focused on predicting **sleep duration**.

Models compared:

- Ridge Regression
- Artificial Neural Network
- Baseline model

Results from the submitted project:

| Model | Mean Test MSE |
|---|---:|
| Artificial Neural Network | 0.0737 |
| Ridge Regression | 0.1019 |
| Baseline | 0.6345 |

The Artificial Neural Network achieved the lowest average test error.

## Classification

The classification task focused on predicting three sleep-disorder categories:

- No Disorder
- Insomnia
- Sleep Apnea

Models compared:

- Logistic Regression
- K-Nearest Neighbors
- Baseline model

Results:

| Model | Mean Error | Approx. Accuracy |
|---|---:|---:|
| Logistic Regression | 0.107 | 89.3% |
| KNN | 0.115 | 88.5% |
| Baseline | 0.414 | 58.6% |

Logistic Regression achieved the lowest average classification error, although its performance was not statistically significantly different from KNN.

## Repository Contents

- `sleep_health_machine_learning.ipynb` — complete project code
- `Sleep_health_and_lifestyle_dataset.csv` — dataset
- `project_1_exploratory_analysis.pdf` — exploratory analysis and PCA report
- `project_2_predictive_modelling.pdf` — regression and classification report
