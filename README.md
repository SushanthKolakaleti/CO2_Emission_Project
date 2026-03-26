# 🚗 CO2 Emission Prediction using Machine Learning

## 📌 Overview
This project focuses on predicting CO2 emission levels of vehicles using machine learning techniques. The model analyzes various vehicle parameters such as engine size, fuel type, number of cylinders, and fuel consumption to estimate emission levels and classify them into categories.

The project also aims to identify whether a vehicle exceeds environmental emission standards, contributing to sustainable and eco-friendly transportation solutions.

---

## 🎯 Problem Statement
To develop a machine learning model that can accurately predict CO2 emissions of vehicles and classify them into emission categories (Low, Medium, High) based on vehicle performance parameters.

---

## 🌍 Motivation
- Increasing environmental pollution due to vehicle emissions  
- Need for automated and efficient emission prediction  
- Limitations of manual and traditional estimation methods  
- Importance of data-driven environmental analysis  

---

## 📂 Dataset Information
- Dataset: Vehicle CO2 Emissions Dataset (Canada - Kaggle)  
- Total Records: ~7000+ vehicles  
- Features include:
  - Engine Size  
  - Number of Cylinders  
  - Fuel Type  
  - Fuel Consumption  
  - Transmission  
  - CO2 Emissions (g/km)  

---

## ⚙️ Methodology

### 1. Data Collection
Collected dataset containing multiple vehicle specifications and emission data.

### 2. Data Preprocessing
- Removed duplicate records  
- Handled missing values  
- Dropped irrelevant features  
- Encoded categorical variables  

### 3. Exploratory Data Analysis (EDA)
- Scatter plots to analyze relationships  
- Box plots for outlier detection  
- Correlation matrix for feature relationships  

(📊 All graphs are available in the images/ folder)

### 4. Data Splitting
- Training Data: 80%  
- Testing Data: 20%  

### 5. Feature Engineering
- Converted CO2 emission values into categories:
  - Low  
  - Medium  
  - High  

---

## 🤖 Machine Learning Models Used

### 🔹 AdaBoost
- Focuses on misclassified data points  
- Improves performance iteratively  

### 🔹 Random Forest
- Ensemble of multiple decision trees  
- Reduces overfitting and improves accuracy  

### 🔹 XGBoost
- Gradient boosting algorithm  
- Handles complex relationships efficiently  
- High performance and speed  

### 🔹 Voting Classifier
- Combines multiple models  
- Final prediction based on majority voting  

---

## 📊 Results and Performance

- Best Model: *XGBoost Classifier*  
- Accuracy Achieved: *98%*  

### 📌 Evaluation Metrics Used
- Accuracy  
- Precision  
- Recall  
- F1-Score  
- Confusion Matrix  

📁 Detailed results, tables, and evaluation outputs are available in the results/ folder  
📊 Graphs and visualizations are available in the images/ folder  

---

## 📈 Visualizations
The project includes:
- Scatter Plots  
- Box Plots  
- Correlation Matrix  
- Confusion Matrix  

(All stored in the images/ directory)

---

## 🛠️ Technologies Used
- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- XGBoost  

---

## 📂 Project Structure
co2-emission-project/
│
├── data/
│   └── dataset.csv
│
├── notebooks/
│   ├── Analysis_and_Preprocessing.ipynb
│   └── Model_and_Evaluation.ipynb
│
├── images/
│   └── (EDA graphs, plots)
│
├── results/
│   └── (model outputs, evaluation metrics)
│
└── README.md
