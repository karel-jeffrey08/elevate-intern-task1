# Marketing Campaign Data Cleaning - Internship Task

## Dataset
- Dataset Name: Marketing Campaign  
- Source: Kaggle dataset provided for Elevate Labs internship task.  
- Contains customer demographic details, purchase information, and campaign responses.

## Objective
The objective was to clean and preprocess the raw marketing campaign dataset by handling missing values, duplicates, data formatting inconsistencies, and preparing the data for further analysis.

## Initial Observations
- Columns include: id, year_birth, education, marital_status, income, kidhome, teenhome, dt_customer, recency, amounts spent on various products, purchase counts, response to campaigns, etc.  
- File was initially tab-separated CSV with messy appearance.

## Steps Performed

1. **File Parsing**  
   - Imported the dataset correctly by handling tab delimiters in WPS Spreadsheet.

2. **Missing Values Check**  
   - Filtered each column to identify missing values and addressed appropriately.

3. **Duplicate Removal**  
   - Verified and removed any duplicate records.

4. **Date Column Conversion**  
   - Converted `dt_customer` column from serial number to readable date format.

5. **Text Standardization**  
   - Standardized categorical columns (`education`, `marital_status`) by converting text to lowercase.

6. **Data Type Formatting**  
   - Ensured numeric columns are correctly formatted as numbers without text.

7. **Column Renaming**  
   - Renamed columns to lowercase with underscores for consistency and ease of analysis.

8. **Final Checks**  
   - Verified cleaned data integrity and saved as `marketing_campaign_cleaned.xlsx`.

## Tools Used
- WPS Office Spreadsheet application for data cleaning and preprocessing.

## Outcome
The dataset is now clean, consistent, and ready for downstream data analysis or machine learning tasks.

---

*Prepared for Elevate Labs Data Analyst Internship submission*
