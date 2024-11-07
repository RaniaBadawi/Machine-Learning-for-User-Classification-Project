# Machine-Learning-for-User-Classification-Project
This project aims to predict whether students on an online education platform will upgrade from a free plan to a paid plan based on their engagement metrics. By utilizing data such as days on platform, content-watched minutes, and courses started, I trained and evaluated several machine learning models to identify the most effective one for this classification task.
# Business Objective
For online companies , predicting potential customers is valuable for targeted marketing and personalized offers. Knowing which users are more likely to upgrade can help allocate marketing resources more effectively and increase revenue. This project can serve as a template for similar business applications across various industries.
# Project Overview
This project explores different machine learning techniques to classify users based on engagement metrics. The dataset is imbalanced, as most users remain on the free plan while a minority upgrade.

# Models Used:

1. Logistic Regression
2. K-Nearest Neighbors (KNN)
3. Support Vector Machine (SVM)
4. Decision Tree
5. Random Forest

# Best Model:
- Logistic Regression achieved the highest accuracy of 97.5%, making it the preferred model for this classification problem.

# Dataset Features:
The dataset used for this project contains the following features:

1. Days on Platform: Number of days a user has been active on the platform.
2. Content-Watched Minutes: Total minutes of content watched by the user.
3. Courses Started: Number of courses the user has started.
4. Practice Exams Started: Number of practice exams the user has started.
5. Practice Exams Passed: Number of practice exams the user has passed.
6. Minutes Spent on Exams: Total minutes spent by the user on practice exams.
7. Purchases: Number of purchases made by the user.

# Evaluation Metrics
The performance of the models was evaluated using the following metrics:

- Accuracy: The percentage of correct predictions.
- Precision: The proportion of positive predictions that were correct.
- Recall: The proportion of actual positives correctly identified by the model.
- F1-Score: The harmonic mean of precision and recall.

# Usage
1. Data Preprocessing:
 - Load the dataset and perform any necessary preprocessing steps (e.g., handling missing values, encoding categorical features).
2. Model Training:
 - Train multiple models and evaluate their performance.
3. Model Evaluation:
 - Evaluate the model using various metrics such as accuracy, precision, recall, and F1-score.

# Results
After training and evaluating all models, Logistic Regression performed the best with an accuracy of 97.5%, outperforming other models. The decision tree-based models (like Random Forest) also performed well but did not achieve the same level of accuracy as Logistic Regression.

# Conclusion
This project demonstrates the effectiveness of using machine learning to predict user behavior based on engagement data. The successful application of Logistic Regression to predict whether a user will upgrade from a free plan to a paid plan can help businesses target users more effectively, optimizing marketing strategies and increasing potential revenue.
