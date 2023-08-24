# Kaggle Titanic Competition Project

Welcome to my first Kaggle competition project for the [Titanic: Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic) competition. This project marks my entry into the world of Kaggle and serves as an exciting opportunity to apply machine learning techniques to a real-world dataset. Below, I outline the general workflow I followed throughout this project.

## 1. Feature Engineering

In my opinion, feature engineering is the most crucial part of this project. Creating meaningful and relevant features is often more important than hyperparameter tuning and model selection. After all, the quality of the data sets the upper limit on model performance. Here are some of the methods I've accumulated:

- **1.1** Removing irrelevant features: For example, the 'Cabin' feature might not significantly contribute to survival prediction.
- **1.2** Extracting additional information: Utilizing existing information to generate new features, such as extracting titles ('Miss', 'Mrs', etc.) from the 'Name' column.
- **1.3** Keeping relevant information: Retaining only certain parts of a feature, such as the suffix of the 'Ticket' column.
- **1.4** Encoding categorical features: Transforming non-numeric categorical features into numerical values.

## 2. Data Preprocessing

Data preprocessing involves handling missing values (NaN) and normalizing numerical features. For handling NaN values, I replaced them with the average value of similar data points (paying attention to the order). For normalization, I used the MinMaxScaler to scale numerical features.

## 3. Model Selection and Training

I explored several classification models during this project:

- **Adaboost**: A boosting algorithm that combines weak learners to form a strong classifier.
- **Random Forest**: A powerful ensemble learning method based on decision trees.
- **Logistic Regression**: A simple yet effective linear classification algorithm.

To find the best-performing model configuration, I used **GridSearchCV** to perform hyperparameter tuning. This involved trying out different combinations of hyperparameters and evaluating their performance using cross-validation.

## Conclusion

Participating in this competition has been a valuable learning experience. I've gained insights into various aspects of machine learning, from feature engineering to model evaluation. While this project marked my first full Kaggle competition, it won't be my last. I look forward to further refining my skills and tackling more complex challenges in the future.
