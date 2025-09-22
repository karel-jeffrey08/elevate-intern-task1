# elevate-intern-task1
Cleaned excel file for task1

# Mall Customers Data Cleaning - Internship Task

## Dataset
The dataset used for this task is the "Mall Customers" dataset sourced from Kaggle, containing customer details such as Customer ID, gender, age, annual income, and spending score.

## Objective
The objective was to clean and preprocess the raw dataset by handling missing values, duplicates, inconsistent formats, and preparing the data for further analysis.

## Cleaning Steps Performed

1. **Column Name Standardization**  
   - Renamed columns to lowercase with underscores for uniformity:  
     - `customer_id`, `gender`, `age`, `annual_income_k`, `spending_score_1_100`

2. **Handling Missing Values**  
   - Checked for missing data in all columns,no missing values were found.

3. **Duplicate Detection and Removal**  
   - Verified no duplicate records exist in the dataset using Excel's Remove Duplicates feature.

4. **Text Standardization**  
   - Standardized the `gender` column entries to lowercase values ("male", "female") for consistency.

5. **Data Type Formatting**  
   - Ensured numeric columns (`age`, `annual_income_k`, `spending_score_1_100`) are formatted as integers without decimals.

6. **Final Checks and Save**  
   - Saved the cleaned dataset as `Mall_Customers_Cleaned.xlsx` for subsequent analysis.

## Tools Used
- Excel Sheet from WPS was used for all data cleaning and preprocessing steps.

## Outcome
The dataset is now clean, consistent, and ready for further analysis or modeling tasks.
