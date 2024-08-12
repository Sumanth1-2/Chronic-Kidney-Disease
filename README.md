# Chronic-Kidney-Disease

**Problem Statement:**

Chronic Kidney Disease (CKD) is a significant health issue that requires early diagnosis to prevent severe outcomes. This study aims to apply various machine learning algorithms to improve the accuracy of early CKD diagnosis by analyzing relevant clinical features. The goal is to identify the most impactful features and develop predictive models that can aid in early detection, potentially improving patient outcomes.

**Tools Used:**

Programming Language: Python
Libraries:
Data Manipulation: Pandas, NumPy
Data Visualization: Matplotlib, Seaborn
Machine Learning: Scikit-learn, CatBoost, XGBoost, LightGBM
Evaluation Metrics: Accuracy, Precision, Recall, F1 Score, Confusion Matrix
Approach:

**Data Collection:**

The CKD dataset was collected and preprocessed to ensure data quality.

**Data Preprocessing:**

The dataset was cleaned, converted into a suitable format, and missing values were handled.
The data was then split into training and testing sets.
Principal Component Analysis (PCA) was applied to reduce dimensionality and focus on the most significant features, such as hemoglobin, albumin, and specific gravity.

**Model Implementation:**

Various machine learning algorithms were implemented, including ensemble methods like CatBoost, AdaBoost, and Gradient Boosting, as well as other classifiers like Decision Tree, Random Forest, and SVM.
The models were trained on the CKD dataset and validated using the test data.

**Evaluation:**

The models were evaluated based on accuracy, precision, recall, F1 score, and confusion matrix.
A comparison was made among the algorithms to identify the most effective model for CKD prediction.

**Conclusion:**

This study successfully applied various machine learning algorithms to diagnose Chronic Kidney Disease (CKD) at an early stage, focusing on key features such as hemoglobin, albumin, and specific gravity. The models were evaluated based on their accuracy, and the results are as follows:

**CatBoost:** Achieved the highest accuracy with a perfect score of 1.000 (100%).
**AdaBoost Classifier**: Also performed exceptionally well, with an accuracy of 0.9917 (99.17%).
**Gradient Boosting Classifier**: Matched the AdaBoost with an accuracy of 0.9917 (99.17%).
**Stochastic Gradient Boosting**: Scored slightly lower with an accuracy of 0.9833 (98.33%).
**Extra Trees Classifier**: Also achieved an accuracy of 0.9833 (98.33%).
**Decision Tree Classifier**: Showed strong performance with an accuracy of 0.9750 (97.50%).
**XGBoost:** Matched the Decision Tree Classifier with an accuracy of 0.9750 (97.50%).
**K-Nearest Neighbors (KNN):** Had the lowest accuracy among the models, scoring 0.7083 (70.83%).

These results demonstrate that ensemble methods like CatBoost, AdaBoost, and Gradient Boosting are particularly effective in accurately predicting CKD. The perfect accuracy achieved by CatBoost highlights its potential as a powerful tool for early CKD diagnosis. The identification of the most significant features and the application of these algorithms offer a promising approach to early intervention, which could greatly improve patient outcomes in healthcare settings.


