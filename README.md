# task-number-04
# Logistic Regression Binary Classifier

## Objective
This project aims to build a binary classifier using logistic regression to predict outcomes based on a binary classification dataset.

## Dataset
The dataset used for this task is the Breast Cancer Wisconsin Dataset.

## Tools Used
- Python
- Scikit-learn
- Pandas
- Matplotlib

## Steps
1. **Data Loading**: Load the dataset using Pandas.
2. **Data Preprocessing**:
   - Split the dataset into features (X) and target (y).
   - Perform a train/test split.
   - Standardize the features using StandardScaler.
3. **Model Training**: Fit a Logistic Regression model on the training data.
4. **Model Evaluation**:
   - Calculate and print the confusion matrix, precision, recall, and ROC-AUC score.
   - Plot the ROC curve.

## Evaluation Metrics
- **Confusion Matrix**: A table used to describe the performance of a classification model.
- **Precision**: The ratio of correctly predicted positive observations to the total predicted positives.
- **Recall**: The ratio of correctly predicted positive observations to all actual positives.
- **ROC-AUC**: A performance measurement for classification problems at various thresholds.

