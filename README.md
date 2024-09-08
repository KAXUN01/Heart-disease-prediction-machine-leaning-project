
# Heart Disease Prediction Project

A heart disease prediction machine learning project is a machine learning initiative designed to predict heart disease risk by analyzing a comprehensive dataset of 13 medical attributes. These attributes include demographic, physiological, and clinical data points that are critical in assessing cardiovascular health.


## Table of Contents

- [Features](#features)
- [Dataset](#dataset)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Running the Application](#running-the-application)
- [Usage](#usage)


## Features
- **Data Analysis**: Comprehensive analysis of medical datasets to identify crucial patterns.
- **Predictive Modeling**: Utilization of advanced machine learning algorithms for accurate predictions.
- **Health Indicator Insights**: Detailed examination of individual health metrics and their impact on heart health.

## Dataset
Our model is trained on a dataset comprising the following columns:
1. **Age**: The age of the individual.
2. **Sex**: Biological sex (male/female).
3. **Chest Pain Type**: Categorized into 4 distinct types.
4. **Resting Blood Pressure**: The blood pressure readings at rest.
5. **Serum Cholesterol**: Measured in mg/dl.
6. **Fasting Blood Sugar**: Indicates if fasting blood sugar is greater than 120 mg/dl.
7. **Resting Electrocardiographic Results**: Values of 0, 1, or 2.
8. **Maximum Heart Rate Achieved**: Peak heart rate during exercise.
9. **Exercise Induced Angina**: Presence or absence of chest pain during exercise.
10. **Oldpeak**: ST depression induced by exercise relative to rest.
11. **Slope of the Peak Exercise ST Segment**: The slope of the ST segment during peak exercise.
12. **Number of Major Vessels**: Number of major vessels (0-3) colored by fluoroscopy.
13. **Thal**: Thalassemia effect with values indicating normal (3), fixed defect (6), or reversible defect (7).


## Prerequisites

- Python
- Jupyter Notebook


## Installation

This code is part of a machine learning web app built with Streamlit for predicting heart disease. It uses a saved machine learning model (`heart_disease_model.sav`) to make predictions based on user inputs. Here's how you can run it:

1. **Ensure Python is Installed**:
   Make sure Python is installed by running:
   ```bash
   python --version
   ```

2. **Install Required Dependencies**:
   Since this project uses `streamlit`, `streamlit-option-menu`, and likely `scikit-learn` (for `predict` function), you need to install these packages. Run:
   ```bash
   pip install streamlit streamlit-option-menu scikit-learn
   ```

3. **Place the Model File**:
   The script is trying to load a model named `heart_disease_model.sav`. Ensure that the model file is available in the same directory as `main.py`. If you don't have the model file, the prediction part won't work.


## Running the Application

**Run the Streamlit Application**:
   Navigate to the folder where `main.py` is located and run:
   ```bash
   streamlit run main.py
   ```

## Usage

**Access the Web Application**:
   - After running the above command, Streamlit will launch a server at `http://localhost:8501`.
   - Open the browser and access this URL to interact with the heart disease prediction app.


The app provides input fields for various health metrics like age, cholesterol, blood pressure, etc., and predicts the likelihood of heart disease based on these inputs.