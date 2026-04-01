# 📈 ASELSAN Stock Price Prediction Project

## 🎯 Goal

The main goal of this project is to build a machine learning model that can predict the stock prices of ASELSAN, which is a well-known defense technology company in Turkey.

---

## 🧵 Dataset

For this project, I used a dataset from Kaggle that contains historical stock price data of ASELSAN.

---

## 🧾 Project Overview

In this project, I worked on analyzing and predicting ASELSAN stock prices using data from **2017 to 2022**.

I started by understanding the dataset, then performed data cleaning and visualization, and finally applied different machine learning models to compare their performance and find the best one.

---

## 🧮 What I Did in This Project

### 🔹 1. Data Preprocessing

* Imported all required libraries and loaded the dataset
* Removed unnecessary columns to keep the data clean
* Converted data types wherever required
* Set the **Date column as index** for better time-series handling

---

### 🔹 2. Exploratory Data Analysis (EDA)

To understand the data better, I performed multiple visualizations:

* 📊 **Opening Price Trend** → Checked how opening price changes over time
* 🔥 **Heatmap** → To understand correlation between features
* 📉 **Closing Price Trend** → Observed long-term price movement
* 📦 **Volume Traded** → Analyzed trading activity
* 📊 **Price Distribution** → Checked how prices are distributed
* 📈 **Daily Returns** → Measured stock volatility
* 📅 **Yearly Trends** → Compared performance across years
* 🔗 **Correlation Matrix** → Identified relationships between variables

👉 This step helped me understand patterns and relationships in the data before building models.

---

## 🚀 Models Used

I applied different regression models to compare their performance:

* **Linear Regression** → Simple and easy to understand baseline model
* **Lasso Regression** → Helps in feature selection using L1 regularization
* **Ridge Regression** → Uses L2 regularization to reduce overfitting
* **Decision Tree Regressor** → Captures non-linear relationships

---

## 📚 Libraries Used

* numpy → for numerical operations
* pandas → for data handling
* matplotlib → for plotting graphs
* seaborn → for better visualization
* scikit-learn → for machine learning models

---

## 📊 Model Performance

### 🔸 Linear Regression

* Train Score: **99.77%**
* Test Score: **99.74%**
  👉 Performed very well and gave consistent results

---

### 🔸 Lasso Regression

* Train Score: **99.75%**
* Test Score: **99.61%**
  👉 Performance is very close to Linear Regression

---

### 🔸 Ridge Regression

* Train Score: **37.57%**
* Test Score: **-71.23%**
  👉 Performed very poorly (not suitable for this dataset)

---

### 🔸 Decision Tree Regressor

* Train Score: **99.93%**
* Test Score: **86.52%**
  👉 High training accuracy but lower test accuracy → **overfitting**

---

## 📢 Final Conclusion

After comparing all models:

👉 **Linear Regression performed the best** with very high and consistent accuracy on both training and testing data.

👉 **Lasso Regression also performed well**, but slightly lower than Linear Regression.

👉 **Decision Tree showed overfitting**, meaning it learned training data too well but didn’t generalize properly.

👉 **Ridge Regression performed poorly**, so it is not suitable for this dataset.

---

## 🔑 Key Learnings

* Importance of **data preprocessing and EDA**
* How to compare different ML models
* Understanding **overfitting and underfitting**
* Role of regularization (Lasso & Ridge)
* Importance of time-based data handling in stock prediction

---

## 👨‍💻 Author

**Akash Deep**
Aspiring Data Scientist

