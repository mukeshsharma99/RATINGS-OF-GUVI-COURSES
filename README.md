# 📚 Ratings of GUVI Courses - Regression Analysis

## 🎯 Project Goal

This project aims to **analyze and predict course ratings** on the GUVI platform using machine learning. By building a regression model, we can uncover what makes a course successful and how different features influence learner ratings.

--- 

## 🧾 About the Dataset

The dataset provides detailed information about various GUVI courses, including:

- 🎓 **Course Title**  
- 🌐 **URL**  
- 💲 **Price**  
- 👨‍🎓 **Number of Subscribers**  
- 📝 **Number of Reviews**  
- 🎥 **Number of Lectures**  
- 🧩 **Course Level**  
- ⭐ **Rating (Target Variable)**  
- ⏱️ **Content Duration**  
- 📅 **Published Timestamp**  
- 📚 **Subject Category**

With these features, we can assess what factors drive **high course ratings** and how to improve course offerings.

---

## 🧠 Problem Statement

> **Design a regression model** that accurately predicts **ratings given by learners** to GUVI courses based on available course attributes.

---

## 🔍 Workflow

### 📊 1. Data Exploration & Cleaning
- Inspected null values and data types
- Converted timestamps and durations to usable formats
- Filtered unrealistic or biased data entries

### 📈 2. Exploratory Data Analysis (EDA)
- Analyzed the distribution of ratings
- Examined relationships between price, duration, reviews, and rating
- Visualized course trends by category and level

### ⚙️ 3. Feature Engineering
- Encoded categorical variables (e.g., course level, subject)
- Created new features (e.g., reviews-to-subscriber ratio)

### 🤖 4. Model Building
- Applied and compared multiple regression models:
  - Linear Regression
  - Decision Tree Regressor
  - Random Forest Regressor
  - XGBoost Regressor

### 📏 5. Evaluation
- Metrics used:
  - Mean Absolute Error (MAE)
  - Root Mean Squared Error (RMSE)
  - R² Score
- Visualizations of predicted vs actual ratings

---

## 🧰 Tech Stack

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook

---


