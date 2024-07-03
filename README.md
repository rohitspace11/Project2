# Credit Card Fraud Detection

This repository contains the code and resources for a Credit Card Fraud Detection project. The goal of this project is to detect fraudulent credit card transactions using machine learning algorithms.

## Introduction
Credit card fraud is a significant problem in the financial industry, resulting in substantial financial losses each year. This project aims to build a machine learning model to identify fraudulent transactions accurately. The models used in this project include Logistic Regression, Decision Tree, Random Forest, and TensorFlow-based neural networks.

## Dataset
The dataset used in this project is a well-known credit card fraud detection dataset available on Kaggle. It contains transactions made by credit cards in September 2013 by European cardholders. The dataset is highly imbalanced, with 492 frauds out of 284,807 transactions.

- **Number of transactions:** 284,807
- **Number of fraudulent transactions:** 492
- **Features:** 30 (including 'Time', 'Amount', and 28 anonymized features)

## Algorithms Used
- **Logistic Regression**
- **Decision Tree**
- **Random Forest**
- **TensorFlow Neural Network**

## Results
The Random Forest model achieved the highest accuracy on the test data. Here are the evaluation metrics for each model:

- **Logistic Regression**
  - Accuracy: 0.9471363207762201
    
- **Decision Tree**
  - Accuracy:  0.9960843496349472

- **Random Forest**
  - Accuracy:  0.9976103016154457

- **TensorFlow Neural Network**
  - Accuracy: 0.9975335001945496

  

## Installation
To run this project locally, please follow these steps:

1. Clone this repository:
    ```bash
    git clone https://github.com/your-username/credit-card-fraud-detection.git
    ```

2. Navigate to the project directory:
    ```bash
    cd credit-card-fraud-detection
    ```

3. Create a virtual environment:
    ```bash
    python3 -m venv venv
    source venv/bin/activate   # On Windows, use `venv\Scripts\activate`
    ```

4. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. Preprocess the data:
    ```bash
    python preprocess_data.py
    ```

2. Train the models:
    ```bash
    python train_models.py
    ```

3. Evaluate the models:
    ```bash
    python evaluate_models.py
    ```

4. Predict fraud on new data:
    ```bash
    python predict.py --input data/new_transactions.csv
    ```

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements, bug fixes, or new features.

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.
