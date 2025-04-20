# Customer-Churn-Prediction
### Project Description: Bank Customer Churn Prediction

The **Bank Customer Churn Prediction** project focuses on predicting which customers are likely to leave (churn) a bank using machine learning models. The project leverages various classification algorithms to analyze historical customer data and make predictions. The goal is to help the bank proactively identify at-risk customers and implement strategies for customer retention.

#### Key Steps and Code Overview:

1. **Data Preprocessing**: 
   The project begins by loading and preparing the dataset using pandas. The data includes various features such as customer demographics, account details, transaction history, and service usage patterns.

2. **Model Training**:
   Several machine learning models are applied to predict customer churn:
   - **Logistic Regression (LR)**
   - **Support Vector Classifier (SVC)**
   - **K-Nearest Neighbors (KNN)**
   - **Decision Trees (DT)**
   - **Random Forests (RF)**
   - **Gradient Boosting Classifier (GB)**

3. **Model Evaluation**:
   After training the models, their performance is evaluated using metrics such as:
   - **Accuracy**: The proportion of correct predictions.
   - **Precision**: The ability of the model to correctly identify churn cases.
   - **Recall**: The ability of the model to capture all churn cases.
   - **F1-Score**: A balanced measure of precision and recall.

   The **Gradient Boosting Classifier (GB)** showed an accuracy of 82.36%, precision of 82.28%, recall of 81.33%, and an F1-score of 81.80%, making it one of the top-performing models in this project.

4. **Final Model Comparison**:
   The performance of all models was compared and summarized in a DataFrame, which shows the accuracy of each model. The **Random Forest (RF)** model had the highest accuracy at 85.47%, followed by **SVC** and **Gradient Boosting (GB)** models.

5. **Outcome**:
   The outcome of this project is a predictive model that can identify at-risk customers, helping banks take proactive measures to improve customer retention and reduce churn. The project involves using a variety of machine learning techniques to demonstrate their effectiveness in solving real-world business problems.

By analyzing key customer behavior patterns, this model supports the decision-making process for customer retention strategies.
