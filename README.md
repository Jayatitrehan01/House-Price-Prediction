# House Price Prediction
This repository contains my work on data preprocessing and feature engineering using the Housing Price dataset, aimed at preparing the data for predictive modelling of house prices.

OBJECTIVE

To clean and transform the dataset to make it model-ready by handling missing values, encoding categorical variables, scaling features, and removing outliers.

TASKS PERFORMED
1. Data Cleaning
Identified and filled in missing values using appropriate strategies:

    Median for numerical columns (e.g., LotFrontage)

    Mode or "None" for categorical columns (e.g., GarageType, BsmtQual)

   Removed irrelevant or duplicate records (if any)

 2. Feature Engineering
Created new features where necessary (e.g., total basement area, age of house)

Converted time-based fields to numeric features for modelling

 3. Encoding Categorical Variables
Used LabelEncoding or OneHotEncoding for converting object types intoa  numeric format

 4. Feature Scaling
Applied StandardScaler to normalise numerical columns

 5. Outlier Detection & Removal
Used the Z-score method to identify and remove extreme outliers

6. Feature Selection
Dropped irrelevant or redundant columns that don't contribute to the prediction
