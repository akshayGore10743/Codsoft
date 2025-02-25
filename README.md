Titanic Survival Prediction

This repository contains a Jupyter Notebook for predicting survival on the Titanic using machine learning techniques. The project involves data preprocessing, feature engineering, model training, and evaluation.

Table of Contents

Introduction

Dataset

Installation

Project Structure

Usage

Model Training & Evaluation

Results

Contributing

License

Introduction

The Titanic Survival Prediction project uses machine learning to predict whether a passenger survived the Titanic disaster based on factors such as age, sex, passenger class, and fare. The project follows these steps:

Data Collection and Preprocessing

Feature Engineering

Model Training and Evaluation

Performance Analysis

Dataset

The dataset used in this project is the Titanic dataset from Kaggle, which contains information about passengers, including:

Passenger ID

Survival status (0 = No, 1 = Yes)

Passenger class (Pclass)

Name

Sex

Age

Siblings/Spouses aboard

Parents/Children aboard

Ticket number

Fare price

Cabin

Embarkation port

Installation

To run this project, follow these steps:

Clone this repository:

git clone https://github.com/your-username/Titanic_Survival_Prediction.git
cd Titanic_Survival_Prediction

Install the required dependencies:

pip install -r requirements.txt

Launch Jupyter Notebook:

jupyter notebook

Open Titanic_Survival_Prediction.ipynb in Jupyter Notebook.

Project Structure

Titanic_Survival_Prediction/
│── data/
│   ├── train.csv
│   ├── test.csv
│── Titanic_Survival_Prediction.ipynb
│── requirements.txt
│── README.md

Usage

Run the Jupyter Notebook step by step to:

Load and preprocess the dataset

Handle missing values

Encode categorical features

Train different machine learning models

Evaluate model performance

Model Training & Evaluation

The project uses various machine learning models including:

Logistic Regression

Decision Trees

Random Forest Classifier

Support Vector Machine (SVM)

The models are evaluated based on metrics such as accuracy, precision, recall, and F1-score.

Results

The best-performing model achieves an accuracy of 78% on the test set.

Contributing

Contributions are welcome! Feel free to fork the repository and submit pull requests with improvements.

License

This project is licensed under the MIT License.

