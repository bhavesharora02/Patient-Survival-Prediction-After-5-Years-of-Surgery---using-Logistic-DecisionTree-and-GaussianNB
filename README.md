# Patient-Survival-Prediction-After-5-Years-of-Surgery---using-Logistic-DecisionTree-and-GaussianNB

The goal is to build a predictive model using machine learning techniques to assist in identifying patients at higher risk post-surgery.

**Patient Survival Prediction After 5 Years of Surgery**

**Project Overview**

This project aims to predict whether a patient will survive for 5 years after surgery based on their age, the year of operation, and the number of positive axillary nodes detected. 
**Dataset**

The dataset consists of the following columns:

**age**: Age of the patient at the time of surgery

**operational_year**: Year of the surgery

**exil_node**: Number of positive axillary lymph nodes detected

**survival**: Survival status (1 = survived 5 years or longer, 0 = died within 5 years)

**Steps Involved**

**1. Data Preprocessing**

Checked for Null Values: Verified the dataset for any missing values and handled them appropriately.
Data Exploration: Used describe() and info() functions to understand the data distribution and characteristics.
Distribution Plots: Created distribution plots (distplots) to check the normal distribution of the data for different features.

**2. Feature and Target Splitting**

Split the dataset into features (independent variables) and target (dependent variable) for model training and testing.

**3. Model Training**

**Logistic Regression:**

Trained the logistic regression model on the training data.
Achieved an accuracy of 72% on the training set.

**Decision Tree Classifier:**

Trained the decision tree model on the training data.
Achieved an accuracy of 67% on the training set.
Gaussian Naive Bayes (GaussianNB):
Trained the GaussianNB model on the training data.
Achieved an accuracy of 72% on the training set.

**4. Model Evaluation and Prediction**

**Predictive System Development:**

**Logistic Regression:** Tested on new input data, but it provided an incorrect prediction.

**Decision Tree:** Successfully predicted the outcome on the new input data, indicating better performance in this specific scenario.

**GaussianNB**: Tested on new input data, but it also provided an incorrect prediction.

**Conclusion**
The decision tree classifier, despite having lower training accuracy (67%), was the only model that provided a correct prediction on the new input data, suggesting it may have a better understanding of the underlying patterns in this specific case. Logistic regression and GaussianNB, while showing similar accuracies (72%) during training, failed to generalize effectively to the new data. Therefore, the decision tree classifier was selected as the final model for this task.
