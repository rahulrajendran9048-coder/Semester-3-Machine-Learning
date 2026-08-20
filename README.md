# Semester 3 Machine Learning Lab

This repository contains the **Machine Learning Lab experiments** completed as part of Semester 3.

The repository currently includes experiments on:

1. **Data Preprocessing using the Google Play Store Dataset**
2. **Logistic Regression using the Diabetes Dataset**

---

## Repository Structure

```text
Semester-3-Machine-Learning/
│
├── Data_Preprocessing/
│   ├── Google_Play_Store_1.ipynb
│   └── google_playstore_preprocessed.csv
│
├── Logistic_Regression/
│   ├── Logistic_Regression.ipynb
│   └── heart (1).csv
│
└── README.md
```

---

# Experiment 1 — Data Preprocessing

### Objective

To perform essential **data preprocessing techniques** on the Google Play Store dataset using Python and Pandas.

### Dataset

The experiment uses a Google Play Store dataset containing information about applications available on the Google Play Store.

### Preprocessing Steps

The experiment covers common data preprocessing operations such as:

* Loading the dataset using Pandas
* Exploring the dataset
* Understanding the structure and data types
* Handling missing values
* Identifying and handling duplicate records
* Cleaning inconsistent data
* Converting columns to appropriate data types
* Processing categorical and numerical attributes
* Removing unwanted or invalid values
* Preparing the cleaned dataset for further machine learning tasks

### Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib / Seaborn, where required

### Files

**`Google_Play_Store_1.ipynb`**
Contains the complete preprocessing implementation and analysis.

**`google_playstore_preprocessed.csv`**
Contains the resulting preprocessed dataset.

---

# Experiment 2 — Logistic Regression

### Objective

To implement a **Logistic Regression classification model** using Python and evaluate its performance.

### Dataset

The experiment uses a diabetes-related dataset containing medical attributes such as:

* Pregnancies
* Glucose
* Blood Pressure
* Skin Thickness
* Insulin
* BMI
* Diabetes Pedigree Function
* Age

The target variable is:

* **Outcome**

where the class represents the corresponding binary outcome.

### Machine Learning Workflow

The experiment demonstrates the typical machine learning workflow:

1. Importing the required libraries
2. Loading the dataset
3. Exploring the dataset
4. Checking data types and dataset information
5. Separating features and target variable
6. Splitting the dataset into training and testing sets
7. Feature preprocessing and scaling
8. Training the Logistic Regression model
9. Making predictions
10. Evaluating model performance

### Evaluation Metrics

The Logistic Regression model can be evaluated using:

* Accuracy
* Confusion Matrix
* Precision
* Recall
* F1-Score

### Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

### Files

**`Logistic_Regression.ipynb`**
Contains the complete Logistic Regression implementation and evaluation.

**`heart (1).csv`**
Dataset used in the Logistic Regression experiment.

---

# Learning Outcomes

Through these experiments, the following concepts are practiced:

* Data loading and exploration
* Data cleaning
* Handling missing and duplicate data
* Numerical and categorical data preprocessing
* Feature scaling
* Train-test splitting
* Supervised machine learning
* Binary classification
* Logistic Regression
* Model evaluation
* Confusion matrix analysis

---

## Environment

The experiments can be executed using **Jupyter Notebook** with the required Python libraries installed.

Install the commonly required libraries using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

---

## Author

**Rahul Raj R**

B.Tech CSE (Artificial Intelligence)
TKM College of Engineering
