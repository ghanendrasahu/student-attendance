# Student Attendance Prediction

A machine learning project that predicts whether a student is likely to have **high** or **low** attendance based on student-related inputs.

## Project Objective

The goal of this project is to build a classification pipeline that helps identify attendance risk early. This can support schools and instructors in:

- spotting students who may need intervention,
- improving retention and classroom engagement,
- making data-informed decisions for academic support.

## Algorithms Used

The notebook includes and/or experiments with the following algorithms:

- **Linear Support Vector Classifier (LinearSVC)** (primary trained classifier)
- **K-Nearest Neighbors (KNN)** (imported for model comparison/experimentation)

## Workflow

1. Load attendance dataset using `pandas`.
2. Prepare features (`X`) and target (`y`).
3. Convert categorical labels using `LabelEncoder`.
4. Split data into training and testing sets (`train_test_split`).
5. Train classifier (`LinearSVC`).
6. Evaluate model using:
   - Accuracy score
   - Classification report
   - Confusion matrix

## Tech Stack

- **Language:** Python
- **Environment:** Jupyter Notebook
- **Libraries:**
  - `pandas`
  - `numpy`
  - `scikit-learn`

## How to Run

1. Clone the repository.
2. Install dependencies:

```bash
pip install pandas numpy scikit-learn jupyter
```

3. Place dataset file in the project folder (or update the dataset path in the notebook).
4. Start Jupyter:

```bash
jupyter notebook
```

5. Open `finalprojectsahu.ipynb` and run all cells.

## Future Improvements

- Compare more models (Logistic Regression, Random Forest, XGBoost).
- Add cross-validation and hyperparameter tuning.
- Improve feature engineering for stronger predictive signal.
- Package notebook workflow into reusable Python scripts.
- Build a simple dashboard/web app for attendance risk insights.
- Add model persistence and inference pipeline for deployment.

## Project Status

This is an actively improvable portfolio project and a strong base for end-to-end ML workflow expansion.
