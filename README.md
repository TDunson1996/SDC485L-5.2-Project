# SDC485L-5.2-Project
Scenario Analysis and Business Insights

# Heart Disease Prediction Using Machine Learning and Neural Networks

## Project Overview

This project applies machine learning and neural network techniques to the UCI Heart Disease dataset to predict heart disease risk, analyze patient characteristics, and evaluate how changes in health conditions impact model predictions.

The project was completed in three phases:

* Project 3.2 – Basic Machine Learning Implementation
* Project 4.2 – Advanced Modeling and Optimization
* Project 5.2 – Scenario Analysis and Business Insights

The goal was to demonstrate the complete machine learning workflow including data preparation, model development, optimization, evaluation, and business-focused scenario analysis.

---

## Dataset

Dataset: UCI Heart Disease Dataset

The dataset contains patient demographic and clinical information including:

* Age
* Sex
* Chest Pain Type
* Resting Blood Pressure
* Cholesterol
* Fasting Blood Sugar
* Resting ECG Results
* Maximum Heart Rate
* Exercise-Induced Angina
* ST Depression (Oldpeak)
* Heart Disease Diagnosis

---

# Project 3.2 – Basic Machine Learning Implementation

### Objectives

Develop machine learning models for:

1. Classification
2. Regression
3. Clustering

### Models Used

#### Classification

* MLPClassifier (Neural Network)

#### Regression

* MLPRegressor (Neural Network)

#### Clustering

* K-Means Clustering

### Results

#### Classification

* Accuracy: 0.86
* Precision: 0.82
* Recall: 0.84
* F1 Score: 0.83

#### Regression

* MSE: 8768
* MAE: 74.97
* R²: 0.29

#### Clustering

* Silhouette Score: 0.23

### Key Findings

The classification model produced the strongest overall performance and successfully identified patients at risk for heart disease.

---

# Project 4.2 – Advanced Modeling and Optimization

### Objectives

Improve model performance using:

* Hyperparameter Tuning
* Early Stopping
* Regularization
* Grid Search
* Randomized Search

### Optimization Techniques

#### Classification

* GridSearchCV
* Early Stopping
* L2 Regularization

#### Regression

* RandomizedSearchCV
* Early Stopping
* Regularization

#### Clustering

* Silhouette Score Optimization

### Results

| Metric           | Original | Optimized |
| ---------------- | -------- | --------- |
| Accuracy         | 0.86     | 0.88      |
| MSE              | 8768     | 8125      |
| MAE              | 74.97    | 69.42     |
| R²               | 0.29     | 0.35      |
| Silhouette Score | 0.23     | 0.29      |

### Key Findings

Optimization improved performance across all analytical tasks, with the largest gains observed in the regression model.

---

# Project 5.2 – Scenario Analysis and Business Insights

### Objectives

Evaluate how changes in patient characteristics affect heart disease risk predictions.

### Scenarios

#### Scenario 1 – Aging Population

* Average age increased by 10 years

#### Scenario 2 – Improved Cholesterol Management

* Cholesterol reduced by 20%

#### Scenario 3 – Improved Cardiovascular Fitness

* Maximum heart rate increased by 10%
* Oldpeak reduced by 20%

### Scenario Results

| Scenario             | Predicted Risk |
| -------------------- | -------------- |
| Baseline             | 0.50           |
| Aging Population     | 0.65           |
| Improved Cholesterol | 0.42           |
| Improved Fitness     | 0.37           |

### Business Insights

The analysis suggests:

* Older populations face increased cardiovascular risk.
* Cholesterol management can significantly reduce risk.
* Improved cardiovascular fitness produced the largest reduction in predicted risk.
* Machine learning can support preventative healthcare decision-making.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-Learn
* TensorFlow/Keras
* Jupyter Notebook

---

## Repository Contents

```text
Project_3_2_Heart_Disease_Tavis_Dunson.ipynb
Project_4_2_Advanced_Modeling_and_Optimization_REVISED.ipynb
Project_5_2_Scenario_Analysis_and_Business_Insights.ipynb
heart_disease_uci.csv
README.md
```

---

## How to Run

1. Clone or download the repository.
2. Install required packages.

```bash
pip install pandas numpy matplotlib scikit-learn tensorflow
```

3. Place the dataset file in the project directory.
4. Run the notebooks in numerical order:

* Project 3.2
* Project 4.2
* Project 5.2

---

## Author

Tavis Dunson

## Course

SDC485L – Artificial Intelligence and Machine Learning

## Final Conclusion

This project demonstrates the complete machine learning lifecycle, beginning with model development, progressing through optimization, and ending with scenario analysis and business-focused recommendations. The results show that machine learning can effectively identify patterns associated with heart disease and provide meaningful insights that support healthcare decision-making.

