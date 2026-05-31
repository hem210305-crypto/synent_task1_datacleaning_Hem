Task 1 – Data Cleaning & Preprocessing
Problem Statement:
Raw datasets often contain missing values, duplicates, and inconsistent formatting that make them unreliable for analysis. The goal is to clean the Titanic dataset and prepare it for further use.

Dataset:
Name: Titanic Dataset
Source: Kaggle
Size: 891 rows × 11 columns (after cleaning)

Approach:
Handled missing values (filled Age with median, Embarked with mode, dropped Cabin)
Removed duplicate records
Converted columns to correct data types
Renamed columns to snake_case (e.g. PassengerId → passenger_id, Pclass → passenger_class)

Results:
Produced a clean, analysis-ready CSV (titanic_cleaned.csv) with 891 rows and 11 properly named and typed columns — no nulls in key fields.
