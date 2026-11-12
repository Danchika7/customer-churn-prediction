# Customer Churn Prediction Using Machine Learning

## Project Overview

This project focuses on predicting customer churn using machine learning techniques. The main objective is to identify customers who are likely to discontinue a service by developing and comparing two classification models: XGBoost and Multilayer Perceptron (MLP).

The project involves data analysis, preprocessing, exploratory data analysis (EDA), model development, hyperparameter optimization, and performance evaluation.

## Objectives

- Analyze customer data and identify important patterns.
- Perform data preprocessing and exploratory data analysis.
- Build machine learning classification models.
- Optimize model hyperparameters to improve performance.
- Evaluate and compare the performance of different models.
- Identify the best-performing model for customer churn prediction.

## Machine Learning Models

Two machine learning models were implemented:

### 1. XGBoost Classifier

- Developed using the XGBoost library.
- Hyperparameter optimization performed using RandomizedSearchCV.
- Five-fold cross-validation used.
- F1-score selected as the optimization metric.

### 2. Multilayer Perceptron (MLP)

- Developed using TensorFlow and Keras.
- Dense layers with ReLU activation.
- Dropout layers for regularization.
- Sigmoid activation in the output layer.
- Adam optimizer and binary cross-entropy loss.
- Hyperparameter optimization performed by evaluating different configurations.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- TensorFlow
- Keras

## Model Performance

The optimized models were evaluated using four classification metrics: Accuracy, Precision, Recall, and F1-score.

### Performance Comparison

| Evaluation Metric | XGBoost | MLP |
|---|---:|---:|
| Accuracy | 97.14% | 94.92% |
| Precision | 89.32% | 92.41% |
| Recall | 92.93% | 73.74% |
| F1-score | 91.09% | 82.02% |

### Best Performing Model

The optimized XGBoost model achieved the best overall performance based on the F1-score.

- Accuracy: 97.14%
- Precision: 89.32%
- Recall: 92.93%
- F1-score: 91.09%

Although MLP achieved higher precision, XGBoost demonstrated better recall and F1-score.

## Project Results and Output

The project output report contains:

- Final model performance comparison.
- Classification reports for both models.
- Confusion matrices.
- Model comparison and discussion.
- Final conclusion.

**View the complete project output report:**

[Customer Churn Prediction - Output Report (PDF)][customer_churn.pdf](https://github.com/user-attachments/files/34752763/customer_churn.pdf)


## Conclusion

In this project, XGBoost and Multilayer Perceptron (MLP) models were successfully developed for customer churn prediction.

Both models were optimized and evaluated using different classification metrics. Based on the experimental results, XGBoost outperformed MLP in terms of accuracy, recall, and F1-score.

Therefore, the optimized XGBoost model was identified as the best-performing model for this customer churn prediction task.

## Project Type

University Academic Project

## Author

**Karunanithy Danchika**

Computer Science and Statistics Undergraduate  
University of Peradeniya
