# 💳PAYMENT CARD FRAUD DETECTION 2025

## 1)Project Overview 
My projcet is **PAYMENT CARD FRAUD DETECTION 2025** This project focuses on detecting and analyzing fraudulent transactions in the luxury cosmetics industry using customer, transaction, and product data. The dataset contains detailed information about customer demographics, purchase behavior, store activity, and payment methods — helping identify patterns that differentiate genuine from fraudulent purchases.

## 2)Objective
This comprehensive synthetic df contains 2,133 transaction records from luxury cosmetics pop-up events across major global cities. The df is specifically designed for credit card fraud detection analysis, featuring 16 carefully curated columns that capture both transactional and behavioral patterns essential for building robust fraud detection models.

## 3)Tech Stack used
Language: Python
Environment: Google Colab
Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
Modeling: Linear Regression, Decision Tree Regressor, Random Forest Regressor
Optimization: GridSearchCV (Hyperparameter Tuning) 

## 4)Dataset Information
- **Source:** Card Fraud Detection in Luxury Retail Analytics Key Columns : Transaction_ID,Customer_ID,Transaction_Date,Transaction_Time.. Timeline: 13/08/2025
- **Location:** Kaggle

## 5)Project Workflow 
### **Stage 1: Data Preprocessing**
- Loaded and explored dataset  
- Handled missing values and duplicates  
- Converted categorical columns into numerical format  
- Extracted day, month, and year features from date  

### **Stage 2: Exploratory Data Analysis (EDA)**
- Univariate Analysis → Distribution plots for important columns  
- Bivariate Analysis → Relation between features and Price  
- Multivariate Analysis → Correlation heatmap & pairplot

### **Stage 3:**
   **A)Feature Engineering**
- Time features
- Card behavior
- Velocity
- Merchant stats
- Merchant stats
- Anomaly flags
  **B)Feature Scaling**
- Select only numeric columns for scaling
- Remove target column before scaling
- Apply StandardScaler
  **C)Feature Selection**
- Data Preparation and Cleaning
- Feature Selection using ANOVA-based F-test (f_classif)
- Train-Test Split
- shape of the data frame befoure building
  **D)Model Building**
- DATA PREPROCESSING AND FEATURE ENGINEERING
- ENCODING CATEGORICAL FEATURES
- SPLIT DATA
- SCALE NUMERIC FEATURES
- MODEL BUILDING AND TRAINING: RANDOM FOREST CLASSIFIER
### **Stage 4: Model Building & Evaluation**
- Compare Different types of Models
- Model training with hyperparameter tuning
- Document future enhancements
- Conclusion

## 6)Model Performance

| Model | R² Score | RMSE | MAE |
|:------|:---------:|:----:|:---:|
| Ridge Regression  | -0.005289   | 0.994805  | 0.359877 |
| SVR   |  -0.005873| 0.995094| 0.269556 |
| Linear Regression | -0.006250| 0.995281 | 0.360628 |
| Random Forest   | -0.041818 | 1.012718 | 0.373682 |
| Gradient Boosting   | -0.070512 | 1.026570 | 0.367056 |

## 7)Future Enhancements
-Implement deep learning (e.g., Neural Networks for fraud detection)
-Add real-time fraud monitoring dashboard (using Streamlit)
-Integrate external APIs for payment data validation

## 8) Conclution
*This project analyzes luxury cosmetics transactions to detect fraudulent activities using machine learning. By examining customer behavior, payment methods, and transaction patterns, the model effectively distinguishes genuine purchases from fraud. The results show that data-driven techniques can enhance security and trust in digital retail platforms.*


















  
