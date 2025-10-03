### 🤖 NEXUS-AI ML INTERNSHIP
## 🆔 ID: NEXUS-079
# 🛍️ Retail Analytics Data Science Portfolio

This repository contains a collection of **Jupyter notebooks** demonstrating various data science tasks applied to retail datasets.  
The tasks cover exploratory data analysis (EDA), interactive dashboards, machine learning models for customer churn prediction, product recommendation systems, and time series forecasting for sales.  

These notebooks are designed to provide **actionable insights** for a fictional retail company like GlobalMart, focusing on customer behavior, sales trends, and predictive modeling.

📂 The notebooks are self-contained, with code, explanations, visualizations, and interpretations.  
📊 They use real-world datasets such as Online Retail, TMDB Movies, Telco Customer Churn, and Superstore Sales.

---

## 📑 Table of Contents
- [📖 Overview](#overview)
- [📝 Tasks and Notebooks](#tasks-and-notebooks)
- [📂 Datasets](#datasets)
- [⚙️ Requirements](#requirements)
- [💻 Installation](#installation)
- [▶️ Usage](#usage)
- [📜 License](#license)

---

## 📖 Overview
This project showcases end-to-end **data science workflows**:
- 🧹 **Data Cleaning and EDA**: Understanding datasets through statistics and visualizations.
- 📊 **Interactive Dashboards**: Building user-friendly visualizations with filtering capabilities.
- 🤖 **Machine Learning**: Classification models for churn prediction, recommendation systems, and time series forecasting.
- 💡 **Business Insights**: Interpretations and recommendations tied to business goals, such as customer retention, product recommendations, and sales forecasting.

The notebooks are numbered as tasks (1-6) and can be run independently.

---

## 📝 Tasks and Notebooks
1. **Task 1: Exploratory Data Analysis (EDA) on Online Retail Dataset**  
   📂 File: `task1.ipynb`  
   🔍 Description: Loads, cleans, and analyzes the Online Retail dataset. Includes descriptive statistics, visualizations (histograms, bar charts, line plots), and insights on customer spending, top products, seasonal trends, and geographic sales.

2. **Task 2: Interactive Dashboard for Retail Sales Insights**  
   📂 File: `task2.ipynb`  
   📊 Description: Builds an interactive Dash dashboard with Plotly visualizations. Features include a country filter, histogram of customer sales, bar chart of top products, and a line chart of sales trends. Includes a 🎥 demo video.

3. **Task 3: Predicting Customer Churn for GlobalMart**  
   📂 File: `task3.ipynb`  
   🤖 Description: Uses Logistic Regression to predict customer churn on the Telco dataset. Includes preprocessing, model training, evaluation (accuracy, confusion matrix), and visualizations. Focuses on identifying at-risk customers.

4. **Task 4: Optimizing Churn Prediction (Advanced Classification)**  
   📂 File: `task4.ipynb`  
   ⚡ Description: Improves the churn model with Random Forest, SMOTE for class imbalance, and scaling. Compares models with metrics (accuracy, precision, recall, F1-score). Recommends the best model for business goals.

5. **Task 5: Building a Product Recommendation System**  
   📂 File: `task5.ipynb`  
   🎬 Description: Implements a content-based recommendation system for movies using TF-IDF and cosine similarity on the TMDB dataset. Recommends similar movies based on user input.

6. **Task 6: Forecasting Future Sales (Time Series Analysis)**  
   📂 File: `task6.ipynb`  
   ⏳ Description: Uses SARIMA for sales forecasting on the Superstore dataset. Includes aggregation, stationarity checks, model training, evaluation (MAE, RMSE), and a 30-day forecast with confidence intervals.

---

## 📂 Datasets
- 🛒 **Online Retail Dataset**: Used in Tasks 1-2 (`OnlineRetail.csv` / `Cleaned_OnlineRetail.csv`)
- 📞 **Telco Customer Churn**: Used in Tasks 3-4 (`WA_Fn-UseC_-Telco-Customer-Churn.csv`)
- 🎬 **TMDB 5000 Movies**: Used in Task 5 (`tmdb_5000_movies.csv`)
- 🏪 **Superstore Sales**: Used in Task 6 (`train.csv`)

Datasets are assumed to be in the same directory as the notebooks. They can be downloaded from Kaggle or UCI repositories.

---

## ⚙️ Requirements
- 🐍 Python 3.9+
- 📦 Libraries:
  - pandas
  - numpy
  - scikit-learn
  - matplotlib
  - seaborn
  - plotly
  - dash
  - statsmodels
  - imbalanced-learn
  - jupyter

📌 See `requirements.txt` for the full list.

---

## 💻 Installation
1. Clone the repository:
```git clone https://github.com/Hamna902/NEXUS-AI-ML-Tasks.git
cd NEXUS-AI-ML-Tasks
```
2. Install dependencies:
```
pip install -r requirements.txt
```
3. Download datasets and place them in the root directory.
## ▶️ Usage
1. Open Jupyter Notebook:
2. Navigate to and run each taskX.ipynb.
3. For Task  (Dashboard): Run the notebook to start the Dash server → open http://127.0.0.1:8050/. Use the dropdown for country filter.
4. Ensure datasets are loaded correctly (paths may need adjustment).

## 📜 License

This project is by HAMNA NAZAR ✨