# Student Performance Prediction System

A clean, lightweight machine learning project that predicts whether a student will **pass** or **fail** based on academic activity and prior performance.

## Overview

This project is built for **Module 11 – Applied AI** and follows the required workflow from the assignment:

1. Create a GitHub repository
2. Load and explore the dataset
3. Preprocess the data
4. Train a machine learning model
5. Push the code and collaborate

The model uses basic student-related features such as study hours, attendance, and previous scores to classify the final result as pass or fail.

## Problem Statement

The objective is to create a machine learning solution that can predict a student's result using historical academic features. This helps demonstrate the full ML workflow from data loading to model training and version control.

## Project Features

* Loads a student performance dataset
* Explores dataset structure and missing values
* Encodes the target variable for classification
* Trains a machine learning model
* Evaluates model performance using accuracy
* Supports GitHub-based version control and collaboration

## Dataset

The dataset contains student performance records with features such as:

* Study hours
* Attendance percentage
* Previous score
* Pass/Fail outcome

### Target Variable

* `pass_or_fail`

### Input Features

* `study_hours`
* `attendance_percentage`
* `previous_score`

## Project Workflow

### 1. Load and Explore Dataset

The dataset is imported into a Pandas DataFrame and checked for:

* Shape
* Column names
* Missing values
* Basic preview of records

### 2. Preprocess Data

The data is prepared for modeling by:

* Encoding the target column
* Selecting relevant feature columns
* Splitting data into training and testing sets

### 3. Train ML Model

A classification model is trained to predict whether a student will pass or fail.

### 4. Evaluate Model

The trained model is tested on unseen data and evaluated using accuracy score.

### 5. Push to GitHub

The final code is committed and pushed to a GitHub repository for version control and submission.

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Git and GitHub

## Files in the Project

```text
Student-Performance-Prediction-System/
│
├── student_performance_dataset.csv
├── notebook.ipynb
├── README.md
└── requirements.txt
```

## Installation

Install the required libraries:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

## How to Run

1. Clone the repository
2. Open the notebook or Python file
3. Run the cells or script in order:

   * Load dataset
   * Explore data
   * Preprocess data
   * Train model
   * Evaluate accuracy

## Model Output

The model predicts one of the following classes:

* `Pass`
* `Fail`

## Future Improvements

This project can be improved later by adding:

* More student features
* Larger dataset
* Better model comparison
* Confusion matrix visualization
* Web interface for predictions

## Learning Outcome

This project demonstrates the complete basics of applied machine learning, including:

* Dataset handling
* Data preprocessing
* Classification modeling
* Model evaluation
* GitHub workflow

## Author

**Winjeet Singh**

## License

This project is created for academic and learning purposes.
