# Employee Promotion Prediction using Random Forest

## Project Overview

This project uses a Random Forest Classification model to predict whether an employee will be promoted based on their work-related and personal information.

The model learns patterns from employee data and predicts the promotion status of a new employee.

## Objective

The objective of this project is to build a Random Forest classification model that predicts whether an employee will be promoted.

The model uses the following information:

- Age
- Experience
- Performance Score
- Training Hours
- Projects Completed
- Job Satisfaction

The target variable is:

- 0 → Not Promoted
- 1 → Promoted

## Dataset Description

The dataset contains information about employees and their work-related characteristics.

### Features

- **Age** – Age of the employee
- **Experience** – Years of work experience
- **Performance_Score** – Employee performance score
- **Training_Hours** – Number of training hours completed
- **Projects_Completed** – Number of projects completed
- **Job_Satisfaction** – Employee job satisfaction score

### Target Variable

- **Promoted** – Promotion status
  - 0 → Not Promoted
  - 1 → Promoted

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

## Machine Learning Model

A Random Forest Classifier was used to predict employee promotion status.

Random Forest is an ensemble learning algorithm that combines multiple Decision Trees and uses majority voting to make classification predictions.

## Project Workflow

1. Create the dataset
2. Understand the dataset
3. Perform Exploratory Data Analysis
4. Select features and target
5. Split the data into training and testing sets
6. Train the Random Forest model
7. Make predictions
8. Evaluate the model
9. Analyze feature importance
10. Perform Out-of-Bag evaluation
11. Perform hyperparameter tuning using GridSearchCV
12. Perform hyperparameter tuning using RandomizedSearchCV
13. Evaluate the final model
14. Predict a new employee's promotion status

## Model Evaluation

The model was evaluated using:

- Accuracy
- Confusion Matrix
- Precision
- Recall
- F1 Score
- OOB Score

The final Random Forest model achieved:

- **Accuracy:** 1.0
- **Precision:** 1.0
- **Recall:** 1.0
- **F1 Score:** 1.0

### Confusion Matrix

```text
[[2 0]
 [0 4]]
```

The model correctly classified all 6 test employees in this particular test split.

## Feature Importance

Feature importance was used to understand which features contributed most to the model's predictions.

Feature importance indicates how useful a feature was to the model's decision-making process. It does not mean that the feature causes the prediction.

## Hyperparameter Tuning

Two hyperparameter tuning techniques were used:

### GridSearchCV

GridSearchCV was used to systematically evaluate specified combinations of Random Forest hyperparameters using cross-validation.

### RandomizedSearchCV

RandomizedSearchCV was used to randomly sample combinations from a larger hyperparameter search space.

The best model obtained through hyperparameter tuning was used as the final model.

## Prediction

The trained Random Forest model was used to predict the promotion status of a new employee based on their employee-related information.

## Conclusion

In this project, we built a Random Forest Classification model to predict whether an employee will be promoted.

The project demonstrated the complete machine learning workflow, including data creation, exploratory data analysis, feature selection, train-test splitting, model training, prediction, evaluation, feature importance analysis, OOB evaluation, and hyperparameter tuning.

GridSearchCV and RandomizedSearchCV were also used to find better Random Forest hyperparameters.

Finally, the best Random Forest model was used to predict the promotion status of a new employee.

## Note

This project uses a small synthetic dataset created for learning and demonstration purposes. The results should not be considered suitable for real
