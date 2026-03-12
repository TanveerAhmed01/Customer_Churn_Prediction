# Customer_Churn_Prediction

# Overview
This project focuses on predicting customer churn using various machine learning classification algorithms. By analyzing customer demographics and account information, the models identify patterns that indicate whether a customer is likely to leave the service (churn) or stay.

# Dataset
The analysis is based on the Churn_Data.csv dataset, which contains 10,000 customer records. Key features include:

Demographics: Geography, Gender, Age

Account Info: CreditScore, Tenure, Balance, NumOfProducts, HasCrCard, IsActiveMember, EstimatedSalary

Target Variable: Exited (1 = Churned, 0 = Retained)

# Methodology
The project follows a standard data science pipeline:

Data Preprocessing: Dropping irrelevant columns (RowNumber, CustomerId, Surname), handling missing values, and encoding categorical variables using LabelEncoder and pd.get_dummies.

Exploratory Data Analysis (EDA): Visualizing the churn count and plotting a feature correlation heatmap.

Model Building & Evaluation: The data is split into training and testing sets, and the following classifiers are trained and compared:

K-Nearest Neighbors (KNN)

Decision Tree Classifier

Random Forest Classifier

AdaBoost Classifier

Gradient Boosting Classifier

# Technologies Used
-Python 3

-Pandas & NumPy: Data manipulation

-Matplotlib & Seaborn: Data visualization

-Scikit-Learn: Machine learning modeling and evaluation metrics (Accuracy, Precision, Recall, F1-Score, ROC Curve)

# How to Run
-Clone this repository to your local machine.

-Ensure you have the required libraries installed.

-Open Customer_Churn_Prediction.ipynb in Google Colab or Jupyter Notebook.

-Upload the Churn_Data.csv file when prompted by the notebook.

-Run all cells to see the data visualizations and model comparisons.
