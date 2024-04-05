# Gen AI-8138
# Loan Approval Prediction using Artificial Neural Network (ANN)
- Introduction
- Requirements
- Installation
- Dataset
- Usage
## Introduction
This project implements an Artificial Neural Network (ANN) to predict loan approval status based on various features such as education, employment status, and other relevant factors. The dataset used for this project contains information about loan applicants and whether their loans were approved or not.
## Requirements
- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- TensorFlow
- Keras
## Install the required packages using pip
pip install pandas numpy matplotlib seaborn scikit-learn tensorflow
## Dataset
The dataset used in this project is stored in the file loan_approval_dataset.csv. It contains the following columns:

- Education: Education level of the loan applicant.
- Self_Employed: Employment status of the loan applicant.
- Loan_Status: Approval status of the loan (target variable).
   Other relevant columns (e.g., income, credit history, etc.).
## Usage
- 1.Ensure you have all the required dependencies installed (see Requirements section).
- 2.Run the Python script loan_approval_prediction.py:
python loan_approval_prediction.py
- 3.The script will load the dataset, preprocess the data, build and train the ANN model, and evaluate its performance.
- 4.After training, the accuracy of the ANN model will be displayed, and a plot showing the training history will be generated.
