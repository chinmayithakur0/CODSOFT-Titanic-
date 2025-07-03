# Titanic Survival Prediction

This project is a machine learning model that predicts whether a passenger survived the Titanic shipwreck based on various features such as age, class, sex, fare, etc. It uses a Random Forest Classifier and includes preprocessing steps like label encoding and missing value imputation.

## Dataset
This code expects a CSV file named `Titanic-Dataset.csv` with relevant passenger information. Make sure it is in the same directory as the script.

## Features Used
- Pclass
- Sex
- Age
- SibSp (Number of siblings/spouses aboard)
- Parch (Number of parents/children aboard)
- Fare
- Embarked

## Model
- **Algorithm:** Random Forest Classifier
- **Metrics:** Accuracy, Classification Report, Confusion Matrix

## Requirements
Install dependencies using:

```bash
pip install -r requirements.txt
