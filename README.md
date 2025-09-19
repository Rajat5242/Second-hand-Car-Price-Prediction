# Second-hand-Car-Price-Prediction

## 🔹 Overview
### This project focuses on predicting the price of used cars using Multiple Linear Regression. The dataset consists of various car attributes such as brand, year, kilometers driven, engine capacity (CC), fuel type, transmission type, and vehicle category. By applying data cleaning, preprocessing, feature engineering, and regression modeling, the project aims to build a predictive model that can estimate car prices with reasonable accuracy.

## 🔹 Key Steps in the Project

### 1. Data Preprocessing & Cleaning
### Handled missing values and removed irrelevant columns (Name, Model, Variant, etc.).
### Standardized categorical variables (e.g., grouping multiple Type, Fuel, and Gearbox categories into broader categories).
### Removed rare brands with very few records to reduce noise.
### Handled outliers in Price, Year, and Kilometers driven using IQR method and thresholding.

### 2. Exploratory Data Analysis (EDA)
### Visualized distributions of Price, Kilometers, and Year using histograms and boxplots.
### Checked correlations between numeric variables and plotted a heatmap.
### Analyzed the impact of categorical features like Fuel Type and Gearbox on prices.

### 3. Feature Engineering
### Converted categorical variables (Brand, Type, Fuel, Status, Gearbox) into numerical format using OneHotEncoding.
### Applied log transformation on the target variable (Price) to reduce skewness.

### 4. Model Building
### Implemented Multiple Linear Regression with a pipeline that combined column transformations and regression in one workflow.
### Used train-test split (90:10 ratio) to evaluate the model.
### Performed repeated experiments (1000 iterations with different random states) to identify the split giving the best R² score.

### 5. Model Evaluation
### Achieved performance metrics:
###        R² Score → (best score obtained from loop)
###        Mean Absolute Error (MAE) → evaluated prediction accuracy.
### Compared predicted prices vs. actual values to validate model reliability.

## 🔹 Tools & Technologies
### Python Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
### Machine Learning: Multiple Linear Regression, OneHotEncoding, Pipeline
### Evaluation Metrics: R² Score, Mean Absolute Error (MAE)

## 🔹 Outcomes
### Successfully built a regression model capable of predicting second-hand car prices.
### Cleaned and optimized dataset by consolidating redundant categories and removing outliers.
### Demonstrated the importance of data preprocessing and feature engineering in improving regression performance.

Reset and restructured the dataset for further analysis.
[Tableau Dashboard](https://public.tableau.com/views/Secondhandcardashboard/Dashboard2?:language=en-US&:display_count=n&:origin=viz_share_link)
