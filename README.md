# Titanic Survival Prediction Using Logistic Regression

## Project Overview

This project focuses on predicting whether a passenger survived the Titanic disaster using Machine Learning.

The project uses the Titanic dataset from Kaggle and applies **Logistic Regression**, a supervised machine learning algorithm used for binary classification.

The model predicts:
- `0` – Passenger did not survive.
- `1` – Passenger survived.

## Dataset

**Source:** [Kaggle – Titanic: Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic/data)

The dataset contains passenger information such as:

- Passenger Class (`Pclass`)
- Gender (`Sex`)
- Age (`Age`)
- Number of Siblings/Spouses (`SibSp`)
- Number of Parents/Children (`Parch`)
- Ticket Fare (`Fare`)
- Port of Embarkation (`Embarked`)

The target variable is `Survived`.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Kaggle Notebook

## Machine Learning Algorithm

**Logistic Regression**

Logistic Regression is used to predict the probability of survival based on passenger characteristics.

The predicted probability is converted into a binary class:
- Probability greater than or equal to 0.5: Survived (1)
- Probability less than 0.5: Did not survive (0)

## Project Workflow

1. Import the required Python libraries.
2. Load the Titanic training and testing datasets.
3. Explore the dataset using Pandas.
4. Perform exploratory data analysis (EDA) using visualizations.
5. Handle missing values.
6. Select relevant features for prediction.
7. Encode categorical variables.
8. Scale numerical features.
9. Split the training dataset into training and validation sets.
10. Build and train the Logistic Regression model.
11. Evaluate the model using accuracy, precision, recall, F1-score and confusion matrix.
12. Generate survival predictions for the test dataset.

## Model Evaluation

The model is evaluated using the following metrics:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- ROC-AUC Score

*The evaluation scores will be added after running the complete model.*

## Expected Output

The final output is a CSV file named `submission.csv` containing:

- `PassengerId`
- `Survived`

This file can be submitted to the Kaggle Titanic competition.

## Project Objective

The main objective of this project is to understand the complete Machine Learning workflow, from data preprocessing and visualization to model training, evaluation and prediction using Logistic Regression.

## Author

Sree Ranga Priya S
