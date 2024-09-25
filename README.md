# Squarrel_Color_Prediction
Toy case to predict the primary colour of a squarrel


# Machine Learning Project: Predictive Modeling

This project involves building a predictive model using various machine learning algorithms on a dataset imported from the web. The workflow is outlined below:

## 1. Dataset Import and Preprocessing
- The dataset was **imported directly from a web source**.
- **Data cleaning** was performed by dismissing irrelevant or redundant variables that would not contribute meaningful information to the model.
- Variables that could be **determined by the target variable** were removed to prevent **reverse causality**.
- To ensure all features were on the **same scale**, **standardization** was applied across all numerical features.

## 2. Model Selection and Training
Several machine learning algorithms were tested to identify the best-performing model:
- **Logistic Regression**
- **XGBoost**
- **Decision Tree**
- **Neural Network** with a **Softmax output layer** for classification.

## 3. Handling Class Imbalance
- The dataset was **highly imbalanced**, which could negatively impact model performance. 
- To address this, **class weights** were adjusted in the algorithms to ensure a fairer classification of the minority class.

## 4. Performance Evaluation
- After training the models, all relevant **performance metrics** were computed, including:
  - **Accuracy**
  - **Precision**
  - **Recall**
  - **F1-Score**
  - **ROC AUC score**.
- A **Confusion Matrix** was also generated to better understand the classification performance across different classes.

## 5. Results and Conclusion
The results from different models were compared, and based on the performance metrics, the most suitable model for this dataset was identified. Adjustments to class weights improved the handling of the imbalanced data, leading to more accurate predictions.
