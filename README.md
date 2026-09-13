# AI-ML Core — Student Performance Prediction System

## 📌 Project Description

The **Student Performance Prediction System** is an AI/ML project that predicts a student's **final academic grade** using factors such as study time, previous grades, failures, and absences.

This project demonstrates a complete Machine Learning workflow, starting from data loading and exploration and going through data preprocessing, visualization, model training, prediction, and evaluation.

A **Linear Regression** model is used to predict the student's final grade. The model is evaluated using **MAE, MSE, RMSE, and R² score**.

The project also includes reusable functions, unit testing, bug fixing, and documentation.

---

## 🎯 Project Objectives

The main objectives of this project are:

- Load and understand a real-world student dataset.
- Explore and visualize the data.
- Select useful features for prediction.
- Train a Machine Learning model.
- Predict students' final grades.
- Evaluate model performance.
- Create reusable prediction functions.
- Write unit tests for important functions.
- Find and fix bugs during testing.
- Document the project clearly.

---

## 📊 Dataset

This project uses the **Student Performance Dataset** from the **UCI Machine Learning Repository**.

The dataset contains information about students and their academic performance.

### Selected Features

| Feature | Description |
|---|---|
| `studytime` | Student's study-time category |
| `failures` | Number of previous class failures |
| `absences` | Number of school absences |
| `G1` | First-period grade |
| `G2` | Second-period grade |
| `G3` | Final grade (target) |

The model uses the selected features to predict **`G3`**, the student's final grade.

---

## 🔄 Project Workflow

Dataset
   ↓
Data Loading
   ↓
Data Exploration
   ↓
Data Cleaning
   ↓
Feature Selection
   ↓
Data Visualization
   ↓
Train/Test Split
   ↓
Model Training
   ↓
Prediction
   ↓
Model Evaluation
   ↓
Unit Testing
   ↓
Bug Fixing

## 🛠️ Technologies Used
Python
Jupyter Notebook
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
PyTest
Git
GitHub
## 🤖 Machine Learning Model

The project uses Linear Regression as the main Machine Learning model.

The model learns the relationship between the selected student features and the final grade.

After training, the model can be used to predict the expected final grade of a new student.

Example:

Student Information
Study Time: 3
Failures: 0
Absences: 5
G1: 14
G2: 15

## Predicted Final Grade: 14.52
Performance: Very Good

## 📈 Model Evaluation

The model is evaluated using the following metrics:
MAE — Mean Absolute Error

Measures the average difference between the actual and predicted grades.
MSE — Mean Squared Error

Measures the average squared difference between actual and predicted values.
RMSE — Root Mean Squared Error

Shows the prediction error in the same unit as the target value.
R² Score

Shows how well the model explains the variation in the final grades.

## 📊 Data Visualization

The project includes visualizations such as:

Distribution of final grades
Study time vs final grade
Previous grades vs final grade
Correlation heatmap
Actual vs predicted grades

These visualizations help us understand the data and the model's predictions more easily.

## 📁 Project Structure
student-performance-prediction/
│
├── data/
│   └── student-mat.csv
│
├── notebooks/
│   └── student_performance_prediction.ipynb
│
├── src/
│   └── model.py
│
├── tests/
│   └── test_model.py
│
├── README.md
├── requirements.txt
└── .gitignore                

## ▶️ How to Run the Project

Start Jupyter Notebook:

jupyter notebook

Then open:

notebooks/student_performance_prediction.ipynb

Run the notebook cells from top to bottom.

## 🧪 Running Unit Tests

The project includes unit tests for important functions.

Run the tests using:

pytest

If all tests pass, you should see a result similar to:

3 passed

## 🐛 Bug Fixing

During testing, bugs can be found in functions or data processing steps.

For example, an incorrect feature name or wrong input value can cause the prediction function to fail.

The identified bug is fixed and the tests are run again to make sure the solution works correctly.

## 📚 What I Learned

Through this project, I practiced:

Working with a real-world dataset
Data exploration and cleaning
Exploratory Data Analysis (EDA)
Data visualization
Feature selection
Train/test splitting
Linear Regression
Model evaluation
Creating reusable Python functions
Unit testing
Debugging and bug fixing
Git and GitHub
Writing project documentation

## 🚀 Future Improvements
In the future, this project can be improved by:

- Testing multiple Machine Learning models.
- Comparing Linear Regression with Random Forest and Decision Tree.
- Improving feature selection.
- Adding a user-friendly web interface.
- Deploying the model as a web application.
- Adding more student-related features.
- Using classification to predict categories such as Pass/Fail.

## 👨‍💻 Author
Mian Abdul Basit

BS Computer Science

AI-ML Core Mini Project
  
