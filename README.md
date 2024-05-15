<p align="center">
  <img src="https://github.com/AkshayAdapa/Industrial_Copper_Modeling/blob/main/industrial%20copper%20image.jpg" alt="Copper Tubing Image" width="500" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);">
</p>

<h1 align="center" style="color: #009999; font-weight: bold;">🛠️ Industrial Copper Modeling Application 🛠️</h1>
<p align="center"><i>A Machine Learning Project</i></p>
<p align="center"><i>Manufacturing Domain</i></p>
<p align="right">Created by Akshay Kumar</p>

## 🧰 Skills
- Python scripting
- Data preprocessing
- Exploratory Data Analysis (EDA)
- Machine Learning modeling (Regression and Classification)
- Web application development using Streamlit

## ❓ Problem Statement
The copper industry deals with less complex data related to sales and pricing. However, this data may suffer from issues such as skewness and noisy data, which can affect the accuracy of manual predictions. Dealing with these challenges manually can be time-consuming and may not result in optimal pricing decisions. A machine learning regression model can address these issues by utilizing advanced techniques such as data normalization, feature scaling, and outlier detection, and leveraging algorithms that are robust to skewed and noisy data. Another area where the copper industry faces challenges is in capturing the leads. A lead classification model is a system for evaluating and classifying leads based on how likely they are to become a customer. The solution must include the following steps: Exploring skewness and outliers in the dataset. Transforming the data into a suitable format and performing any necessary cleaning and pre-processing steps. ML Regression model which predicts continuous variable ‘Selling_Price’. ML Classification model which predicts Status: WON or LOST. Creating a Streamlit page where you can insert each column value and you will get the Selling_Price predicted value or Status (Won/Lost).

## 🌟 Project Overview
This project aims to develop machine learning models for the copper industry to predict selling prices and classify leads' status. The models utilize advanced techniques to address challenges such as data skewness, outliers, and noisy data. Additionally, a Streamlit-based web application is created to provide an interactive interface for users to make predictions.

## 📊 Project Approach
### 📊 Data Understanding
Identify the types of variables (continuous, categorical) and their distributions. Treat reference columns as categorical variables.

### 🛠️ Data Preprocessing
- Handle missing values with mean/median/mode.
- Treat outliers using IQR or Isolation Forest from the sklearn library.
- Identify Skewness in the dataset and treat skewness with appropriate data transformations, such as log transformation.
- Encode categorical variables using suitable techniques, such as one-hot encoding or label encoding.

### 📈 Exploratory Data Analysis (EDA)
Visualize outliers and skewness (before and after treating skewness) using Seaborn’s boxplot, distplot, violinplot.

### 🧪 Model Building and Evaluation
- Split the dataset into training and testing/validation sets.
- Train and evaluate different classification models, such as ExtraTreesClassifier, XGBClassifier, or Logistic Regression, using appropriate evaluation metrics such as accuracy, precision, recall, F1 score, and AUC curve.
- Optimize model hyperparameters using techniques such as cross-validation and grid search to find the best-performing model.

### 🖥️ Streamlit Application Overview
Create an interactive Streamlit page where users can input each column value except ‘Selling_Price’ for regression model and except ‘Status’ for classification model. Perform the same feature engineering, scaling factors, log/any transformation steps used for training ML model and predict the new data from Streamlit, displaying the output.

## 🎉 Advantages of the Project
- Provides accurate predictions for selling prices and lead status in the copper industry.
- Saves time and effort compared to manual prediction methods.
- Utilizes advanced machine learning techniques to handle data skewness, outliers, and noisy data.
- Offers an interactive web application for easy access and usability.

## 🏁 Conclusion
The Industrial Copper Modeling Application equips users with practical skills in Python programming, data preprocessing, machine learning modeling, and web application development. By leveraging advanced techniques and Streamlit, this project provides a robust solution for predicting selling prices and lead status in the manufacturing domain, particularly in the copper industry.
</p>
