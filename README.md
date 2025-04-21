🧹 Task 1: Data Cleaning and Preprocessing
🎯 Objective
To perform essential data cleaning steps and generate a clean, analysis-ready dataset.
📂 Dataset
Customer Personality Analysis — downloaded from Kaggle
This dataset contains demographic and behavioral data of customers, useful for segmentation and targeting.
🛠️ Tools Used
    • Python (Pandas)
    • Jupyter Notebook / Colab
📋 Actions Performed
Following the task instructions, the following cleaning operations were completed:
    1. Identify and Handle Missing Values
        ◦ Used .isnull().sum() to identify missing values.
        ◦ Dropped rows with null values using dropna().
    2. Remove Duplicates
        ◦ Checked for duplicate rows using .duplicated().sum().
        ◦ Removed duplicates with .drop_duplicates().
    3. Standardize Text Values
        ◦ Converted values in Education and Marital_Status columns to lowercase using .str.lower() for consistency.
    4. Convert Date Format
        ◦ Converted the Dt_Customer column to datetime using pd.to_datetime().
        ◦ Standardized the format to dd-mm-yyyy.
    5. Rename Column Headers
        ◦ Renamed all columns to snake_case format:
            ▪ Replaced spaces and special characters with underscores.
            ▪ Converted to lowercase.
            ▪ Used Python's re module for regex-based renaming.
    6. Check and Fix Data Types
        ◦ Ensured all columns have correct data types.
        ◦ Converted Dt_Customer from object to datetime.
✅ Result
The final dataset is cleaned, formatted, and ready for further analysis or visualization. All inconsistencies, missing data, and formatting issues were resolved.
