# Task 1: Data Cleaning and Preprocessing

## Overview
This project focuses on cleaning and preprocessing a raw dataset using Python and Pandas. The objective is to improve data quality by handling missing values, removing unnecessary columns, checking for duplicate records, and converting data into appropriate formats for further analysis.

## Dataset
The dataset contains information about movies and TV shows, including details such as title, director, cast, country, release year, genres, ratings, popularity, budget, and revenue.

## Tools and Technologies
- Python
- Pandas
- NumPy
- Jupyter Notebook

## Data Cleaning Process

### 1. Data Loading
- Imported the dataset using Pandas.
- Examined the dataset structure and basic information.

### 2. Missing Value Handling
- Identified missing values using `isnull().sum()`.
- Filled missing values in:
  - Director
  - Cast
  - Country
  - Genres
  - Description
- Replaced missing values with meaningful placeholders such as "Unknown" and "No Description".

### 3. Column Removal
- Removed the `duration` column because it contained 100% missing values and provided no useful information.

### 4. Duplicate Check
- Checked for duplicate records using `duplicated().sum()`.
- Confirmed that the dataset contained no duplicate rows.

### 5. Data Standardization
- Standardized column names by converting them to lowercase.
- Replaced spaces with underscores for consistency.

### 6. Date Conversion
- Converted the `date_added` column to datetime format for easier date-based analysis.

### 7. Validation
- Verified that all missing values were handled.
- Confirmed data consistency after preprocessing.

### 8. Export
- Saved the cleaned dataset as `cleaned_dataset.csv`.

## Project Structure

```
Task-1-Data-Cleaning
│
├── task1dataset.csv
├── cleaned_dataset.csv
├── data_cleaning.ipynb
└── README.md
```

## Results
- Missing values handled successfully.
- Unnecessary column removed.
- Data types standardized.
- Dataset prepared for further analysis and visualization.
- Cleaned dataset exported successfully.

## Learning Outcomes
Through this project, I gained practical experience in:
- Data cleaning and preprocessing
- Handling missing values
- Data transformation
- Working with Pandas DataFrames
- Preparing datasets for analysis

## Author
**Madhu Mitha**  
B.Tech Computer Science and Business Systems (CSBS)
