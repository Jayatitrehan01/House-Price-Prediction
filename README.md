# House-Price-Prediction
This repository contains my work on data preprocessing and feature engineering using the Housing Price dataset, aimed at preparing the data for predictive modeling of house prices.

Objective
To clean and transform the dataset to make it model-ready by handling missing values, encoding categorical variables, scaling features, and removing outliers.

🔧 Tasks Performed
📌 1. Data Cleaning
Identified and filled missing values using appropriate strategies:

Median for numerical columns (e.g., LotFrontage)

Mode or "None" for categorical columns (e.g., GarageType, BsmtQual)

Removed irrelevant or duplicate records (if any)

📌 2. Feature Engineering
Created new features where necessary (e.g., total basement area, age of house)

Converted time-based fields to numeric features for modeling

📌 3. Encoding Categorical Variables
Used LabelEncoding or OneHotEncoding for converting object types into numeric format

📌 4. Feature Scaling
Applied StandardScaler to normalize numerical columns

📌 5. Outlier Detection & Removal
Used Z-score method to identify and remove extreme outliers

📌 6. Feature Selection
Dropped irrelevant or redundant columns that don't contribute to prediction
