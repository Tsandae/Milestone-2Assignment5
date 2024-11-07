# Milestone-2Assignment5
# Cancer Data Analysis Using PCA and Logistic Regression

## **Overview**
This project involves analyzing the Breast Cancer dataset from `sklearn.datasets` to reduce dimensionality and build a predictive model. Principal Component Analysis (PCA) is used to identify the most essential variables for donor funding, followed by a logistic regression model for classification.

## **Features**
1. **Principal Component Analysis (PCA)**: 
   - Reduces the dataset to 2 dimensions for visualization and essential feature extraction.
2. **Logistic Regression**: 
   - Implements a classification model to predict breast cancer classes (malignant/benign).
3. **Visualizations**:
   - Decision boundary visualization with accuracy information.
   - Confusion matrix heatmap.
   - Receiver Operating Characteristic (ROC) curve.

## **Files**
- `Milestone2.ipynb`: Python script containing all the code for PCA, logistic regression, and visualizations.
- `README.md`: Instructions and details about the project.


## **Dataset**
The dataset is part of `sklearn.datasets`:
- **Features**: 30 numeric features representing cell nucleus measurements.
- **Target**: Two classes: 
  - `0`: Malignant 
  - `1`: Benign

## **Setup Instructions**

### **Prerequisites**
Ensure Python is installed (>=3.7). Install the required libraries using:
```cmd
pip install 
