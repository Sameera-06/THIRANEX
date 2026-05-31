# Titanic Survival Prediction Using Machine Learning

## Project Overview

This project focuses on building a machine learning model to predict whether a passenger survived the Titanic disaster based on various features such as age, gender, passenger class, fare, and embarkation port.

The project demonstrates the complete machine learning workflow, including data preprocessing, feature engineering, model training, prediction, and performance evaluation.

---

## Objectives

* Perform data cleaning and preprocessing
* Handle missing values
* Convert categorical data into numerical format
* Train a machine learning classification model
* Evaluate model performance using accuracy and confusion matrix
* Visualize model results

---

## Dataset

The Titanic dataset contains information about passengers aboard the Titanic, including:

* Passenger Class (Pclass)
* Gender (Sex)
* Age
* Number of Siblings/Spouses Aboard (SibSp)
* Number of Parents/Children Aboard (Parch)
* Fare
* Embarked Port
* Survival Status

Target Variable:

* Survived

  * 0 = Did Not Survive
  * 1 = Survived

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## Machine Learning Workflow

### 1. Data Collection

Loaded the Titanic dataset into a Pandas DataFrame.

### 2. Data Cleaning

* Filled missing values in Age using median values.
* Filled missing values in Embarked using mode values.
* Removed the Cabin column due to excessive missing data.

### 3. Data Preprocessing

* Converted categorical variables into numerical values.
* Selected relevant features for training.

### 4. Train-Test Split

* Training Data: 80%
* Testing Data: 20%

### 5. Model Training

Used the Decision Tree Classifier algorithm to train the predictive model.

### 6. Model Evaluation

Evaluated model performance using:

* Accuracy Score
* Confusion Matrix
* Classification Report

---

## Results

The Decision Tree Classifier achieved a prediction accuracy of approximately 75%–85%, depending on the train-test split.

Performance metrics included:

* Accuracy Score
* Precision
* Recall
* F1-Score
* Confusion Matrix Visualization

---

## Visualizations

The project includes:

* Confusion Matrix Heatmap
* Dataset Exploration Charts
* Feature Analysis Visualizations

---

## Project Structure

Task2/

├── Titanic_Prediction.ipynb

├── titanic.csv

├── cleaned_titanic.csv

└── README.md

---

## Key Learnings

* Data preprocessing techniques
* Handling missing values
* Feature encoding
* Supervised machine learning
* Classification algorithms
* Model evaluation and performance analysis
* Data visualization using Python

---

## Conclusion

This project successfully demonstrates the implementation of a supervised machine learning model for predictive analysis. By applying data cleaning, preprocessing, model training, and evaluation techniques, meaningful predictions were generated regarding passenger survival on the Titanic. The project provided practical experience in machine learning workflows and model performance assessment.
