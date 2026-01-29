🚢 Titanic Survival Prediction
📌 Project Overview

This project focuses on predicting passenger survival on the Titanic using Machine Learning.
The goal is to build a clean, well-structured pipeline that demonstrates data preprocessing, feature engineering, model training, and evaluation.

🧠 Problem Statement

Given passenger information such as age, gender, class, and fare,
can we predict whether a passenger survived the Titanic disaster?

📊 Dataset

Source: Titanic dataset

Rows represent passengers

Target variable: Survived

0 → Did not survive

1 → Survived

🔧 Data Preprocessing

Handled missing values:

Age filled using median to reduce the effect of outliers

Embarked filled using mode

Dropped irrelevant features:

Cabin, Ticket, Name

Encoded categorical variables using One-Hot Encoding

🏗 Feature Engineering

Converted categorical features (Sex, Embarked) into numerical format

Selected relevant features to improve model performance and generalization

🤖 Model Used

Logistic Regression

Chosen for its simplicity and interpretability in binary classification problems

📈 Model Evaluation

Train/Test split: 80% / 20%

Evaluation metrics:

Accuracy

Confusion Matrix

Classification Report

Result:
Train and test scores are close, indicating good generalization and minimal overfitting.

✅ Results

The model achieved stable accuracy on unseen data

Small gap between training and testing scores confirms that the model is not memorizing the data

🛠 Tools & Libraries

Python

Pandas

NumPy

sklearn

Matplotlib

🚀 Future Improvements

Add Exploratory Data Analysis (EDA) with visualizations

Try additional models (Decision Tree, Random Forest)

Perform hyperparameter tuning

Feature scaling and cross-validation

This project demonstrates a complete and clean Machine Learning workflow,
from raw data to evaluated model, with a strong focus on code quality and understanding.
