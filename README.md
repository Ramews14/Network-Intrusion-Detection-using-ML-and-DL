# NID Prediction Using Machine Learning and Deep Learning

## Project Overview
This project focuses on predicting the likelihood of a Non-Invasive Diagnostic (NID) outcome using machine learning and deep learning models. The dataset consists of various features relevant to diagnosing a condition, and the goal is to build predictive models that can identify whether a given instance results in a positive or negative NID diagnosis.

## Dataset
The dataset contains the following key features:

- `Feature1`: Description of feature 1
- `Feature2`: Description of feature 2
- `Feature3`: Description of feature 3
- ... (Include all relevant features here)
- `Class`: Target variable, where 0 indicates negative outcome and 1 indicates positive outcome.

## Objective
The goal of this project is to predict whether a given instance will result in a positive or negative NID outcome based on the provided features.

## Project Workflow

1. **Data Loading**: 
   - The dataset is loaded into a pandas DataFrame for processing.
   
2. **Data Preprocessing**:
   - Categorical features are one-hot encoded.
   - Missing values are handled for relevant columns.
   - Features are scaled using StandardScaler for numerical features.
   - Target labels are encoded.

3. **Model Building**:
   - **Random Forest Classifier**: A random forest model is trained as an initial model for classification.
   - **Deep Neural Network (DNN)**: A feedforward neural network model

   - A confusion matrix is generated for better understanding of correct and incorrect predictions.
   
5. **Model Performance**:
   - Comparison of model performance based on accuracy and other metrics such as precision, recall, and F1-score.
   - Training loss and accuracy plots for the deep learning model to visualize model convergence.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/nid-prediction-ml-dl.git

pip install -r requirements.txt
pandas
numpy
scikit-learn
tensorflow
