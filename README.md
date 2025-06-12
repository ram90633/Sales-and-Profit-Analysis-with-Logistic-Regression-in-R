# 🛒📈 Superstore Sales & Profit Analysis with Predictive Modeling 💰🧠

## 📌 Overview

Welcome to the **Superstore Sales & Profit Analysis** project — a powerful data analytics and prediction solution using R. This project performs comprehensive exploratory data analysis (EDA) on retail sales data, visualizes insights across various business dimensions, and builds a **logistic regression model** to predict high-profit transactions.

---

## 🎯 Objectives

- Explore and understand the performance of a retail superstore across various dimensions like region, segment, category, and state.
- Use `ggplot2` visualizations to highlight sales and profit trends.
- Build a **logistic regression model** to predict whether a transaction yields high profit.
- Evaluate the predictive model using standard metrics and interpret the outcomes effectively.

---

## 📦 Dataset Summary

The dataset is a retail transaction record from a **superstore**, consisting of various fields including sales, profit, discount, region, category, and more.

> **Note**: The dataset is a local CSV file named `Super Store.csv`, not hosted publicly.

### 🧬 Description

This dataset contains transactional data with the following key fields:  
- **Sales, Profit, Discount, Quantity**  
- **Region, Segment, State, Category, Sub-Category**  
- **Ship Mode, Order Date, Customer Details**

It enables both **descriptive analysis** (via visualization) and **predictive modeling** (via logistic regression).

### 🔍 Key Technical Highlights

- 📊 **Categorical Analysis**: Visual insights based on Region, Segment, Category, and State.
- 🔢 **Preprocessing**: Checked for missing values, unique values, and summary statistics.
- 🌐 **Visualization**: Used bar and pie charts for deeper understanding of sales and profit distribution.
- 📉 **Modeling**: Binary classification model to predict if a transaction is high profit based on `Sales`, `Discount`, and `Quantity`.
- 🧪 **Train-Test Split**: Used 70:30 split via `caTools` for modeling.
- 🧠 **Evaluation Metrics**: Accuracy, Precision, Recall, F1-Score, and Confusion Matrix.

---

## 🧠 Model Summary

This project uses a **logistic regression model** built using base R's `glm()` function to classify high-profit transactions.

### 🏗️ Architecture Overview

- 📥 **Input Features**: `Sales`, `Discount`, `Quantity`
- 🧮 **Output Variable**: `High_Profit` (Binary: 0 or 1)
- 🔀 **Data Split**: 70% training, 30% testing
- 🧪 **Thresholding**: Median profit value used to define high vs low profit
- 📦 **Evaluation**:
  - **Confusion Matrix**
  - **Precision, Recall, F1 Score**
  - **Accuracy**
- 📊 **Extra**: Heatmap of correlations among numerical variables

---

## 🎯 Model Evaluation on Test Set

- **Precision:** 0.70  
- **Recall:** 0.80  
- **F1 Score:** 0.74  
- **Accuracy:** 0.73

---

## 📊 Visualizations Included

- 🌍 **Sales & Profit by Region** – Bar & Pie Charts
- 👥 **Sales & Profit by Segment** – Bar Charts
- 🧺 **Sales & Profit by Category** – Bar & Pie Charts
- 🗺️ **Sales & Profit by State** – Horizontal Bar Charts
- ♨️ **Correlation Matrix Heatmap** – Between numerical columns
- 🎯 **Prediction Histogram** – Actual outcome vs predicted probability

