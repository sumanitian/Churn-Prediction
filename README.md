# Churn-Prediction
This project aims to predict customer churn in a bank using a Support Vector Machine (SVM) model. By analyzing customer data and applying machine learning techniques, we can anticipate whether customers are likely to churn or not.

<h1>Overview</h1>
Customer churn refers to the phenomenon where customers discontinue their relationship with a company or service. Predicting customer churn is essential for businesses, especially in the banking industry, as it allows proactive measures to retain customers and improve customer satisfaction.

In this project, we have developed an SVM model to predict whether customers will churn or not. The SVM algorithm is a powerful machine learning technique used for classification tasks. It works by finding the optimal hyperplane that separates different classes with the maximum margin.

<h1>Data Preparation</h1>
To build an effective churn prediction model, we gathered relevant data from the bank's customer records. The dataset included various features such as customer demographics, transaction history, account details, and other relevant attributes.

Before applying the SVM algorithm, we performed extensive data preprocessing and feature engineering. This involved handling missing values, encoding categorical variables, and normalizing numerical features. Additionally, we conducted exploratory data analysis to gain insights into the data distribution and identify any patterns or correlations.

<h1>Model Development</h1>
Once the data was prepared, we split it into training and testing sets. The training set was used to train the SVM model, while the testing set was used to evaluate its performance.

To improve the model's predictive capabilities, we conducted hyperparameter tuning. By systematically searching and testing different combinations of hyperparameters, we identified the optimal set of parameters for our SVM model. This process involved techniques such as grid search or random search.

Furthermore, to address the issue of class imbalance, where the number of churned customers is significantly lower than non-churned customers, we applied random oversampling. This technique artificially increased the number of churned instances in the training data, allowing the model to learn better from minority class samples.

<h1>Model Evaluation</h1>
The tuned SVM model demonstrated strong performance in predicting customer churn. By evaluating the model's performance metrics, we observed significant improvements. The precision increased from 76% to 86%, indicating a reduction in false positives. The recall also improved from 77% to 97%, indicating a reduction in false negatives.

The model achieved an overall accuracy of 91%, which signifies its ability to correctly classify both churned and non-churned customers. However, it's important to note that accuracy alone might not be the sole criterion for evaluating the model's effectiveness, especially when dealing with imbalanced datasets. Precision, recall, and other metrics provide a more comprehensive evaluation of the model's performance.

<h1>Conclusion</h1>
In conclusion, this project successfully developed an SVM model for predicting customer churn in a bank. By leveraging machine learning techniques, we were able to anticipate whether customers are likely to churn or not. Through hyperparameter tuning and random oversampling, we significantly improved the model's precision and recall, leading to enhanced performance.

Moving forward, this churn prediction model can provide valuable insights to the bank's customer retention strategies. By identifying potential churners in advance, appropriate measures can be taken to retain customers, improve customer satisfaction, and optimize business outcomes.
