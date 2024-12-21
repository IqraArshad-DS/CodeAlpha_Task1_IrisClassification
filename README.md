# Iris Flower Classification 

This repository contains the implementation of the Iris Flower Classification task, completed as part of Task 1 for the CodeAlpha internship.

## Overview
The Iris dataset, containing three flower species (`Setosa`, `Versicolor`, `Virginica`), is used to train and evaluate machine learning models for classification. The best-performing model, **Gradient Boosting Classifier**, achieved an accuracy of **86%**.

## Workflow
1. **Data Preprocessing**:
   - Removed duplicates, handled encoding, scaled features, and removed outliers.
2. **Visualization**:
   - Explored data relationships using pair plots and box plots.
3. **Model Training**:
   - Tested multiple ML models, including Decision Tree, Random Forest, SVM, KNN, Gradient Boosting, and XGBoost.
4. **Final Model**:
   - Selected Gradient Boosting Classifier as the final model due to its simplicity and high accuracy.
5. **Model Deployment**:
   - Saved the trained model and demonstrated its usage for new predictions.

## How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/IqraArshad-DS/Iris_Flower_Classification.git
2. Open the Jupyter Notebook (Iris_Flower_Classification.ipynb) and run the cells sequentially.
3. Use the saved model (final_gradient_boosting_model.pkl) for predictions.

**Technologies Used:**  
  Python
  Scikit-learn
  Matplotlib, Seaborn
  Gradient Boosting Classifier
