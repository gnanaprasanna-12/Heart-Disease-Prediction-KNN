# Heart-Disease-Prediction-KNN
Heart Disease Prediction using KNN Classification and different distance metrics
# Heart Disease Prediction using KNN Classification

## Project Overview
This project implements the K-Nearest Neighbors (KNN) classification algorithm to predict the presence of heart disease using patient health information.

The dataset is converted into a binary classification problem:
- 0 – No Heart Disease
- 1 – Heart Disease

## Dataset
- Source: UCI Machine Learning Repository
- Dataset: Heart Disease (Cleveland)
- Records: 303
- Input features: 13
- Target classes: 2

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow
1. Import required libraries
2. Load the Heart Disease dataset
3. Perform Exploratory Data Analysis (EDA)
4. Handle missing values
5. Convert the target into binary classes
6. Separate input features and target variable
7. Split data into training and testing sets
8. Apply StandardScaler
9. Implement KNN classification
10. Evaluate model performance
11. Compare different distance metrics
12. Predict using an unseen data point

## Distance Metrics
The following distance metrics are evaluated:
- Minkowski
- Manhattan
- Hamming
- Chebyshev

## Model Performance
- Algorithm: K-Nearest Neighbors
- Number of Neighbors (K): 5
- Minkowski Accuracy: 88.52%

Other distance metric results are included in the notebook.

## Conclusion
This project helped me understand KNN classification, feature scaling, distance metrics, and model evaluation through a practical machine learning application.

## Disclaimer
This project is for educational purposes only and is not intended for medical diagnosis.
