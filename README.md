# Salary Prediction with Decision Tree

## Overview
This project predicts whether a person's salary is more than $100k based on features like the company, job role, and degree. The prediction model is implemented using a Decision Tree Classifier.

## Dataset
The dataset (`salaries.csv`) consists of information about different job roles in various companies, the associated degree, and whether the salary is more than $100k.

## Preprocessing
1. Loaded the dataset using pandas.
2. Extracted input features (`company`, `job`, `degree`) and target variable (`salary_more_than_100k`).
3. Encoded categorical features using LabelEncoder.

## Model Training
1. Created a Decision Tree Classifier.
2. Trained the model on the preprocessed data.
3. Achieved 100% accuracy on the training data.

## Evaluation
1. Used confusion matrix to evaluate the model.
2. Plotted the confusion matrix using seaborn.
3. Visualized the decision tree.
4. Calculated precision, recall, and F1-score.
5. Displayed a classification report.

## Usage
1. Clone the repository.
2. Ensure you have Python and necessary libraries installed.
3. Run the script (`decision_tree_salary_prediction.py`).
4. Interact with the decision tree model for salary prediction.

Example:
```bash
python decision_tree_salary_prediction.py
