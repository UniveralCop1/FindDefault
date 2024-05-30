# FindDefault (Prediction of Credit Card fraud)



# Problem Statement:
        A credit card is one of the most used financial products to make online purchases and payments. Though the Credit cards can be a convenient way to manage your finances, they can also be risky. Credit card   fraud is the unauthorized use of someone else's credit card or credit card information to make purchases or withdraw cash.
It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase. 
The dataset contains transactions made by credit cards in September 2013 by European cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.
We have to build a classification model to predict whether a transaction is fraudulent or not.
In this project we want to identify fraudulent transactions with Credit Cards. Our objective is to build a Fraud detection system using Machine learning techniques. In the past, such systems were rule-based. Machine learning offers powerful new ways.

# Techniques used in the project

1.Data Manipulation:
 - Using NumPy for efficient numerical operations and array manipulation
 - Using Pandas for loading, cleaning, and transforming tabular data
 
2.Data Visualization:
 - Using Matplotlib for creating static, customizable plots and figures
 - Using Seaborn for creating high-level, aesthetically pleasing data visualizations
 - 
**Some common techniques that may be employed in this project using these libraries:**

**Exploratory Data Analysis (EDA):**
- Generating descriptive statistics
- Creating univariate and multivariate plots (e.g., histograms, scatter plots, heatmaps)
- Identifying patterns, trends, and relationships in the data
- 
**Feature Engineering:**
- Creating new features from the existing data
- Handling missing values
- Encoding categorical variables

**Model Building and Evaluation:**
- Applying machine learning algorithms (e.g., regression, classification, clustering)
- Splitting the data into training and testing sets
- Evaluating model performance using appropriate metrics
  
**Data Reporting and Presentation:**
- Generating informative and visually appealing plots and figures
- Combining visualizations and insights to tell a story with the data

**Some Screenshots**
![Screenshot 2024-05-29 224405](https://github.com/UniveralCop1/FindDefault/assets/170419127/99501bab-ecdd-4596-801c-aadc4e2114ae)
![Screenshot 2024-05-29 224436](https://github.com/UniveralCop1/FindDefault/assets/170419127/97a074d4-2902-451f-b047-ab26ad1b0bae)
![Screenshot 2024-05-29 225058](https://github.com/UniveralCop1/FindDefault/assets/170419127/8161cf6a-0738-44c4-9f20-09ca06b5b4b1)
![Screenshot 2024-05-29 225114](https://github.com/UniveralCop1/FindDefault/assets/170419127/12c9e2f9-f434-4859-a1c5-b3e97e94e1ff)

# Results
The classification report indicates that the SVM model has performed well in identifying both the non-fraud and fraud transactions, with high precision, recall, and F1-score for both classes.
The overall accuracy of the SVM model is 0.99, meaning that it correctly classified 99% of the transactions in the test set.
macro avg 0.99 0.98 0.99 176 weighted avg 0.99 0.99 0.99 176
This report provides the following metrics:
1. Precision: The precision is the ratio of true positives to the sum of true positives and false positives. It measures the model's ability to avoid false positives.
   - For the non-fraud class (0), the precision is 0.99, indicating that 99% of the transactions predicted as non-fraud are actually non-fraud.
   - For the fraud class (1), the precision is 1.00, meaning that all transactions predicted as fraud are actually fraud.
2. Recall: The recall is the ratio of true positives to the sum of true positives and false negatives. It measures the model's ability to detect all the positive instances.
   - For the non-fraud class (0), the recall is 1.00, indicating that the model correctly identified all the non-fraud transactions.
   - For the fraud class (1), the recall is 0.96, meaning that the model correctly identified 96% of the fraud transactions.
3. F1-score: The F1-score is the harmonic mean of precision and recall. It provides a balanced measure of the model's performance.
   - For the non-fraud class (0), the F1-score is 0.99.
   - For the fraud class (1), the F1-score is 0.98.
4. Support: The support is the number of actual occurrences of the class in the test dataset.
   - There are 151 non-fraud transactions and 25 fraud transactions in the test set.
