<p align="center">
  <img src="https://media.giphy.com/media/3oEjI6SIIHBdRxXI40/giphy.gif" width="300" alt="Airplane flying animation"/>
</p>

# ✈️ Flight Price Prediction


## 📌 Project Overview
This project focuses on predicting airline ticket prices based on features such as airline, source, destination, stops, duration, and departure time. The goal is to build machine learning models that accurately forecast ticket prices to help travelers make informed booking decisions and assist companies in dynamic pricing strategies.

---

## 🔍 Problem Statement
Given a dataset of historical flight bookings, develop a regression model that predicts the price of a flight using relevant features like:
- Airline
- Number of stops
- Journey date and time
- Duration
- Source and Destination

---

## 🧰 Tools & Technologies Used
- **Languages & Libraries**: Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost
- **Machine Learning**: Regression models (Linear Regression, Random Forest, XGBoost)
- **Jupyter Notebook** for development

---

## 📊 Exploratory Data Analysis (EDA)
- Extracted and transformed date, month, and time features from journey columns
- Visualized relationships between price and various categorical features (e.g., airline, stops)
- Checked for outliers and handled missing/null values

---

## ⚙️ Feature Engineering
- Extracted hours and minutes from "Dep_Time" and "Arrival_Time"
- Converted categorical variables using One-Hot Encoding and Label Encoding
- Dropped irrelevant features like "Route" and "Additional_Info"

---

## 🤖 Model Building
- **Baseline Models**: Linear Regression
- **Tree-based Models**: Random Forest Regressor, XGBoost Regressor
- Hyperparameter tuning using `GridSearchCV` and `RandomizedSearchCV`

---

## 📈 Model Evaluation
- Metrics used: R² Score, Mean Absolute Error (MAE), Root Mean Squared Error (RMSE)
- XGBoost gave the best performance with an R² score of ~0.92 on test data

---

## ✅ Key Outcomes
- Built a robust flight price prediction system with high accuracy
- Gained experience in regression modeling, feature engineering, and model evaluation
- Created a reusable pipeline for real-world regression problems

---

## 📂 Dataset
- Source: Provided dataset (`Clean_Dataset.csv`, `economy.csv`, `business.csv`)
- Contains flight details such as airline, stops, source, destination, timings, duration, and prices

---

## 📌 Future Improvements
- Deploy the model using Flask or Streamlit
- Integrate live airline data via APIs
- Use NLP techniques on airline reviews to improve prediction

---

