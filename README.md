# Anxiety Data Analysis and Machine Learning

## Overview

This project explores an anxiety dataset using data preprocessing, exploratory data analysis (EDA), feature scaling, regression, and classification techniques. The objective is to analyze the relationships between lifestyle and health factors and anxiety levels while applying various machine learning algorithms for prediction and classification.

The notebook demonstrates a complete machine learning workflow, from cleaning and encoding the data to training and evaluating multiple models.

---

## Features

- Data preprocessing using Pandas
- Encoding categorical variables with `LabelEncoder`
- Feature scaling using `MinMaxScaler`
- Correlation analysis with Seaborn heatmaps
- Exploratory Data Analysis (EDA)
- Linear Regression
- Support Vector Regression (SVR)
- Neural Network Regression (MLP Regressor)
- Decision Tree Classification
- K-Nearest Neighbors (KNN) Classification
- Neural Network Classification (MLP Classifier)
- Performance evaluation using:
  - Mean Squared Error (MSE)
  - R² Score
  - Accuracy Score

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Dataset

The dataset contains demographic, lifestyle, and physiological information related to anxiety, including:

- Age
- Gender
- Occupation
- Sleep Hours
- Physical Activity
- Caffeine Intake
- Alcohol Consumption
- Smoking Status
- Family History of Anxiety
- Stress Level
- Heart Rate
- Breathing Rate
- Sweating Level
- Medication
- Therapy Sessions
- Recent Major Life Event
- Diet Quality
- Anxiety Level
- Anxiety Category (if available)

---

## Machine Learning Models

### Regression

- Linear Regression
- Support Vector Regression (SVR)
- Multi-Layer Perceptron Regressor (MLPRegressor)

Evaluation Metrics:

- Mean Squared Error (MSE)
- R² Score

### Classification

- Decision Tree Classifier
- K-Nearest Neighbors (KNN)
- Multi-Layer Perceptron Classifier (MLPClassifier)

Evaluation Metric:

- Accuracy Score

---

## Data Visualization

The notebook includes:

- Lifestyle correlation heatmap
- Health factor correlation heatmap
- Actual vs Predicted regression plots
- Model comparison visualizations

---

## Installation

Clone the repository

```bash
git clone https://github.com/abdelrahmankhalaf139-star/Anxiety-Data-Analysis.git
```

Navigate into the project directory

```bash
cd Anxiety-Data-Analysis
```
---

## Results

The implemented models demonstrate different approaches to predicting anxiety levels and classifying anxiety categories. Performance is evaluated using standard regression and classification metrics to compare model effectiveness.

---

## Future Improvements

- Hyperparameter tuning
- Cross-validation
- Feature engineering
- Additional visualization techniques
- Model persistence using Joblib or Pickle
- Deployment as a web application using Flask or Streamlit

---

## License

This project is intended for educational and portfolio purposes.
