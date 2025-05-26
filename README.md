Titanic Dataset Preprocessing Project

This project was completed as part of my internship to practice data cleaning and preparation for machine learning. The goal was to transform the raw Titanic dataset into a clean and usable format by handling missing values, encoding categorical variables, scaling numerical features, and removing outliers.
Files Included:
Titanic-Dataset.csv – Original/raw Titanic dataset
Titanic-Cleaned.csv – Final cleaned dataset
titanic_data_prep.py – Python script for preprocessing

Tools Used:
Python
pandas
NumPy
matplotlib
seaborn
scikit-learn

Preprocessing Steps:
Handled Missing Values
Filled missing Age values with the median.
Filled missing Embarked values with the most common value (mode).
Dropped the Cabin column due to too many missing values.
Encoded Categorical Data
Converted Sex into numeric (0 = male, 1 = female).
Used one-hot encoding for the Embarked column.
Standardized Numeric Columns
Scaled Age and Fare using StandardScaler for better model performance.
Outlier Detection & Removal
Visualized outliers using boxplots.
Removed outliers from Age and Fare using the IQR method.
Saved Cleaned Data
Final cleaned dataset saved as Titanic-Cleaned (1).csv.

What I Learned:
How to clean a real-world dataset for machine learning
Handling missing values using median and mode
Encoding categorical data using mapping and one-hot encoding
Standardizing numerical data
Detecting and removing outliers using boxplots and IQR
Writing a complete data preprocessing script in Python
