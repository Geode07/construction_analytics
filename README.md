# construction_analytics
A construction project health classification and prognostication study

## Overview
This project explores machine learning methods for classifying **Primavera construction projects** using predictive modeling techniques. The goal is to evaluate how well different models can predict project characteristics based on historical project data.

The notebook compares several classification models and evaluates their performance using standard machine learning metrics.

## Objectives
- Explore the structure of Primavera construction project data
- Build predictive models to classify projects
- Compare multiple machine learning algorithms
- Evaluate model performance using standard metrics
- Identify which algorithm performs best for this dataset

## Models Compared
The following classification models were implemented and evaluated:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Gradient Boosting Classifier

Each model was trained on the same dataset and evaluated using consistent metrics.

## Workflow

The project follows a standard machine learning workflow:

### 1. Data Preparation

- Import Primavera project data
- Clean and preprocess features
- Encode categorical variables
- Split the dataset into training and testing sets

### 2. Model Training

Each model was trained using the training dataset:

- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boosting

### 3. Model Evaluation

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

## Results Summary

Across the models tested, **Random Forest** produced the strongest overall performance in the notebook run.

Random Forest typically performs well for tabular datasets like project management data because it can capture nonlinear relationships and interactions between variables.

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Example Use Cases
This type of model could be useful for:
- Early identification of project risk categories
- Forecasting project characteristics
- Portfolio analysis of construction programs
- Supporting construction management decision making

## Future Improvements
Potential extensions to this project include:
- Hyperparameter tuning
- Cross-validation
- Feature importance analysis
- Additional models (XGBoost, LightGBM)
- SHAP explainability analysis
- Deployment as an API or dashboard

## How to Run
1. Clone the repository
2. Install dependencies
3. Unzip the zip file
4. Run the notebook

![Project Workflow](images/roc_compare.png)
