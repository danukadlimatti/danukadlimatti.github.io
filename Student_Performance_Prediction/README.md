<p align="center">
  <img src="https://media.giphy.com/media/3oEjI6SIIHBdRxXI40/giphy.gif" width="300" alt="Student studying animation"/>
</p>


# 🎓 Student Performance Prediction




## 📌 Project Overview
This project aims to predict student academic performance using machine learning techniques. The goal is to identify key factors affecting performance and help educators and institutions intervene early for better outcomes.

---

## 🎯 Problem Statement
Given a dataset of student records including demographic, academic, and behavioral attributes, develop a model that predicts whether a student is likely to score well, underperform, or fail.

---

## 🧰 Tools & Technologies Used
- **Languages & Libraries**: Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Machine Learning Models**: Logistic Regression, Decision Tree, Random Forest, XGBoost
- **Development Environment**: Jupyter Notebook

---
## Data preprocessing
Before working with any dataset we have to process that dataset so it will be ready for training our models. All functions that will be used will be described in the following cell.

1) Sometimes, datasets came up with non numerical values and it is impossible to give it to any classifier. So our job is to convert non numeric values to numerical ones. And we will do that by calling:
def numerical_data()
 - This function will map each string to an appropriate integer. 

2) But we can do another thing which is feature scaling. Feature scaling is a method used to normalize the range of independent variables or features of data. In data processing, it is also known as data normalization and is generally performed during the data preprocessing step. This will help our learning algorithms to converge quickly. Just by calling :
def feature_scaling(df)
   - This function take the dataset as an argument and replace each column, let's say 'col',to :    
 
, where 
 : the mean or the average.

    - But this is not the only scaling you do, it turns out the following equation works well to:    
 
, where 
 : the standard deviation.

## 📊 Exploratory Data Analysis (EDA)
- Analyzed the distribution of scores based on gender, parental education, test preparation, and more
- Checked correlations between input features and final grades
- Visualized score patterns using bar charts, histograms, and heatmaps

---

## ⚙️ Feature Engineering
- Converted categorical variables using Label Encoding and One-Hot Encoding
- Created new features like average score, pass/fail status
- Handled missing values and outliers

---

## 🤖 Model Building
- **Classification Models**: Logistic Regression, Random Forest, Decision Tree, XGBoost
- Split data into training and test sets using `train_test_split`
- Performed hyperparameter tuning using `GridSearchCV`

---

## 📈 Model Evaluation
- Accuracy, Precision, Recall, F1-Score
- Confusion Matrix and ROC Curve to evaluate performance
- Best model: **Random Forest** with ~90% accuracy

---

## ✅ Key Outcomes
- Built a predictive model to classify student performance
- Identified impactful features such as test preparation, parental education, and study time
- Delivered insights that can be used to improve educational strategies

---

## 📂 Dataset
- Features include gender, race/ethnicity, parental level of education, lunch type, test preparation course, and scores in math, reading, and writing
- Target variable: Pass/Fail or Score Category (based on thresholds)

---

## 📁 Project Structure
Student_Performance_Prediction/ │ ├── data/ # Dataset files ├── notebooks/ # Jupyter notebooks ├── models/ # Trained models ├── README.md # Project documentation
