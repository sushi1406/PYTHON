
# Titanic Survival Prediction

This project uses the Titanic dataset to build a predictive model that determines whether a passenger on the Titanic survived or not. The Titanic dataset is a well-known dataset in the machine learning community, often used as a beginner project due to its rich data and clear objectives.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Data Preprocessing](#data-preprocessing)
- [Modeling](#modeling)
- [Evaluation](#evaluation)
- [Results](#results)
- [Conclusion](#conclusion)
- [How to Use](#how-to-use)
- [Dependencies](#dependencies)
- [Acknowledgements](#acknowledgements)

## Introduction

The goal of this project is to predict the survival of passengers on the Titanic using a dataset that includes various features such as age, gender, ticket class, and fare. This project demonstrates the application of machine learning techniques to classify whether a passenger survived or not.

## Dataset

The dataset typically contains the following features:
- **PassengerId**: Unique identifier for each passenger
- **Survived**: Survival status (0 = No, 1 = Yes)
- **Pclass**: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
- **Name**: Name of the passenger
- **Sex**: Gender of the passenger
- **Age**: Age of the passenger
- **SibSp**: Number of siblings or spouses aboard the Titanic
- **Parch**: Number of parents or children aboard the Titanic
- **Ticket**: Ticket number
- **Fare**: Passenger fare
- **Cabin**: Cabin number
- **Embarked**: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

## Data Preprocessing

Data preprocessing steps include:
- Handling missing values
- Encoding categorical variables
- Feature scaling
- Feature selection

## Modeling

Several machine learning algorithms were used to build predictive models, including:
- Logistic Regression

## Evaluation

The models were evaluated based on various metrics, including:
- Accuracy
- Precision
  

Cross-validation was used to ensure the robustness of the models.

## Results

The results of the models, including their performance metrics, are documented and compared to identify the best-performing model.

## Conclusion

The project provides insights into the factors that influenced survival on the Titanic and demonstrates the application of machine learning techniques to a classification problem.


Open the notebook `Titanic_Survival_Prediction.ipynb` to see the analysis and model training.

## Dependencies

- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Acknowledgements

The dataset used in this project is provided by [Kaggle](https://www.kaggle.com/c/titanic/data). Special thanks to the Kaggle community for providing the data and resources for this classic machine learning project.


