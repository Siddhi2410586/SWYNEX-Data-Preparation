# SWYNEX-Data-Preparation
Task 1 - Titanic Data Cleaning | SWYNEX Internship
# SWYNEX Internship - Task 1: Data Preparation

**Name:** SIDDHI BORADE
**Internship:** Data Science @ SWYNEX Technologies

### Dataset
Titanic - Machine Learning from Disaster (Kaggle Public Dataset)
Source: https://www.kaggle.com/c/titanic/data
Rows: 891 passengers, 12 columns

### Problem Found (Before Cleaning)
- Age: 177 missing values
- Cabin: 687 missing values (77% empty)
- Embarked: 2 missing values

### Solution (After Cleaning)
- Age -> Filled with Median = 28.0
- Embarked -> Filled with Mode = S (Southampton)
- Cabin -> Dropped column (too many missing)
- Duplicates: 0 found
- Final: 0 missing values ✅

### Files in Repo
- raw_titanic.csv (original train.csv)
- cleaned_titanic.csv (after cleaning)
- data_preparation.ipynb (Colab notebook)

### Tools
Python, Pandas, Google Colab

### Learning
Learned how to handle missing data using median/mode and decision making for dropping high-missing columns.
