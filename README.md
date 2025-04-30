
#Titanic Survival Prediction

This project is part of the **CodSoft Data Science Internship** and focuses on predicting whether a passenger survived the Titanic disaster using machine learning techniques.

##Objective
To build a classification model using logistic regression that can accurately predict the survival of passengers based on features like age, gender, ticket class, etc.

##Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Data Preprocessing
- Dropped irrelevant columns: `PassengerId`, `Name`, `Ticket`, `Cabin`
- Filled missing values (`Age` with median, `Embarked` with mode)
- Encoded categorical columns (`Sex` and `Embarked`)

## Model Building
- Used `LogisticRegression` from Scikit-learn
- Trained the model on 80% of the data
- Evaluated with accuracy score and classification report

## Output
- Printed model accuracy and detailed performance metrics
- Visualized survival count based on gender

## Dataset
- [Titanic Dataset on Kaggle](https://www.kaggle.com/datasets/yasserh/titanic-dataset)

## Outcome
This beginner-friendly project showcases essential steps in the ML pipeline — cleaning, modeling, and evaluation — and lays a foundation for more advanced predictive modeling tasks.
