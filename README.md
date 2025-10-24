Bank Churn Prediction using Artificial Neural Network
Overview
This project focuses on predicting customer churn for a bank using an Artificial Neural Network (ANN) built with TensorFlow and Keras. The goal is to classify whether a customer will exit the bank based on historical and demographic data.
The model is trained for 100 epochs using:

Activation Function: ReLU for hidden layers
Output Activation: Sigmoid for binary classification
Optimizer: Adam
Loss Function: Binary Crossentropy
Evaluation Metric: Accuracy


Dataset
The dataset used is the Binary Classification of Bank Churn Synthetic Data from Kaggle. It contains customer details and engineered features for better prediction.
Key Features

CreditScore: Customer’s credit score
Age: Customer’s age
Tenure: Number of years with the bank
Balance: Account balance
NumOfProducts: Number of bank products used
HasCrCard: Credit card ownership (1 = Yes, 0 = No)
IsActiveMember: Active membership status (1 = Yes, 0 = No)
EstimatedSalary: Estimated salary
Exited: Target variable (1 = Churned, 0 = Not churned)


Project Workflow

Data Preprocessing
Handle missing values
Scale numerical features



Model Building

Define ANN architecture with multiple dense layers
Use ReLU activation for hidden layers and Sigmoid for output
Compile with Adam optimizer and binary crossentropy loss



Training

Train for 100 epochs
Monitor accuracy and loss during training



Evaluation

Evaluate on test data
Generate confusion matrix and classification metrics



Visualization

Plot training accuracy and loss curves
Display confusion matrix for predictions



Predicting New Data

Process new sample input
Scale features and predict churn probability




Results

Achieved high accuracy on test data
Visualized performance using confusion matrix and training curves
Model successfully predicts churn for new customer data


Requirements

Python 
TensorFlow
Keras
Pandas
NumPy
Matplotlib
Scikit-learn
