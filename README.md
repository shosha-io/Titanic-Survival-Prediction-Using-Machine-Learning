# Titanic Survival Prediction Using Machine Learning

## Overview

This project builds a complete Machine Learning pipeline to predict whether a Titanic passenger survived or not based on passenger information such as age, gender, ticket class, fare, and family size.

The project includes:

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Data Preprocessing
* Model Training
* Hyperparameter Tuning
* Model Evaluation
* GUI Application for Predictions

---

# Project Description

This project develops a machine learning model to predict Titanic passenger survival using multiple classification algorithms. The workflow includes preprocessing, visualization, feature engineering, training, tuning, and evaluation.

Several ML models were implemented and compared:

* Logistic Regression
* Support Vector Machine (SVM)
* Decision Tree
* Random Forest
* K-Nearest Neighbors (KNN)

The final selected model achieved high validation accuracy and was used to generate predictions for unseen test data.

---

# Dataset Information

The dataset used is the famous Titanic dataset from Kaggle.

## Features

* Passenger Class (Pclass)
* Sex
* Age
* Fare
* Embarked
* SibSp
* Parch
* Ticket
* Cabin
* Name

## Target

* Survived

  * 0 = Did Not Survive
  * 1 = Survived

---

# Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
---

# Machine Learning Workflow

## 1. Data Cleaning

* Handled missing values
* Removed unnecessary columns
* Fixed inconsistent data

## 2. Exploratory Data Analysis

* Survival distribution visualization
* Correlation heatmaps
* Age and fare distributions
* Survival by gender and class

## 3. Feature Engineering

* Extracted passenger titles
* Created FamilySize feature
* Created IsAlone feature
* Generated Age Bins

## 4. Preprocessing

* One-hot encoding
* Label encoding
* Feature scaling using StandardScaler

## 5. Model Training

The following classifiers were trained and evaluated:

* Logistic Regression
* SVM
* Decision Tree
* Random Forest
* KNN

## 6. Hyperparameter Tuning

GridSearchCV with 5-fold cross-validation was used to optimize model performance.

---

# GUI Application

A graphical user interface (GUI) was developed using Tkinter to allow users to enter passenger information and predict survival instantly.

## GUI Features

* User-friendly interface
* Passenger data input fields
* Real-time survival prediction
* Easy interaction without coding knowledge

## Example Inputs

* Age
* Gender
* Passenger Class
* Fare
* Family Size
* Embarkation Port

## Prediction Output

The GUI displays:

* Survived
* Did Not Survive

---

# Model Performance

| Model                       | Validation Accuracy |
| --------------------------- | ------------------- |
| Logistic Regression (Tuned) | 84.9%               |
| Decision Tree (Tuned)       | 84.3%               |
| KNN                         | 83.2%               |
| SVM                         | 82.6%               |
| Random Forest               | 82.1%               |

---

# Project Structure

```bash
Titanic-ML-Project/
│
├── data/
│   ├── train.csv
│   └── test.csv
│
├── notebooks/
│   └── Titanic_Analysis.ipynb
│
├── models/
│   └── trained_model.pkl
│
├── gui/
│   └── app.py
│
├── outputs/
│   ├── figures
│   └── predictions.csv
│
├── README.md
└── requirements.txt
```

---

# Installation

```bash
pip install -r requirements.txt
```

---

# Run the GUI

```bash
python app.py
```

---

# Future Improvements

* Improve GUI design
* Add deep learning models
* Deploy as a web application
* Add real-time analytics dashboards

---

# Author

TEAM HOLANDA

Machine Learning Project — Titanic Survival Prediction
