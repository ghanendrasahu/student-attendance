# Student Attendance Prediction

This is my machine learning project on student attendance analysis and prediction.

## Project Goal

The objective is to predict student attendance performance and identify whether a student falls into a high-attendance or low-attendance category based on academic and behavioral features.

## Project Files

- `attendance.csv` - dataset with 1000 student records
- `finalprojectsahu.ipynb` - complete notebook with data analysis, model training, evaluation, and plots

## Features Used

- `Math_Score`
- `Science_Score`
- `English_Score`
- `Study_Hours_Per_Week`
- `Assignments_Completed`
- `Participation_Score`
- `Absences`
- `Previous_Attendance_Percentage`

Targets:
- Regression target: `Attendance_Percentage`
- Classification target: `Attendance_Label` (`High` / `Low`)

## Models Implemented

### Regression Models

- Linear Regression
- Ridge Regression
- Lasso Regression
- K-Nearest Neighbors Regressor
- Support Vector Regressor (SVR)
- Random Forest Regressor
- Gradient Boosting Regressor

### Classification Models

- Logistic Regression
- K-Nearest Neighbors Classifier
- Support Vector Classifier (SVC)
- Random Forest Classifier
- Gradient Boosting Classifier

## Visualizations Included

- Attendance percentage distribution
- Attendance label count plot
- Correlation heatmap
- Regression model comparison charts (R2 and RMSE)
- Actual vs predicted attendance plot
- Classification model comparison charts (Accuracy and F1-score)
- Confusion matrix of the best classifier

## How to Run

1. Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

2. Start Jupyter Notebook:

```bash
jupyter notebook
```

3. Open `finalprojectsahu.ipynb` and run all cells.
