Deep Learning for Fraud Detection in Cryptocurrency Financial Transactions

This repository contains the code and resources needed to build a Deep Learning model for detecting potential fraud in cryptocurrency financial transactions. The project covers everything from data preprocessing to model building and final deployment.

Overview

In this project, you will learn how to:

Build a data preprocessing pipeline using object-oriented programming principles.
Train a Deep Learning model using Keras and TensorFlow.
Evaluate model performance using metrics such as accuracy and AUC.
Deploy the trained model to make predictions on new data.
Files Included

cripto_proj.ipynb: The main Jupyter Notebook containing the code for data preprocessing, model training, evaluation, and deployment.
dataset.csv: The dataset used for training and testing the model.
new_data.csv: A sample file with new transaction data for testing the deployed model.
How to Run the Project

Clone this repository:
bash
Copy code
git clone <repository-url>
Navigate to the project directory:
bash
Copy code
cd <project-directory>
Open the Jupyter Notebook:
bash
Copy code
jupyter notebook cripto_proj.ipynb
Follow the steps in the notebook to preprocess the data, train the model, and evaluate its performance.
Requirements

Make sure you have the following Python libraries installed:

numpy
pandas
matplotlib
scikit-learn
tensorflow
keras
You can install all required libraries using:

bash
Copy code
pip install -r requirements.txt
How It Works

Data Preprocessing: The project includes a comprehensive pipeline that handles missing data, feature selection, and data scaling.
Model Training: The model architecture consists of dense layers optimized for binary classification (fraudulent or non-fraudulent transactions).
Evaluation: The model is evaluated using accuracy and AUC to ensure it can generalize well to unseen data.
Deployment: The trained model is used to predict the probability of fraud in new transactions.
Results

The model achieves high accuracy and AUC, indicating its effectiveness in detecting fraudulent transactions.

References

Ethereum Network
Ethereum Transactions
