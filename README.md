# Skillytix – Task 01: Data Cleaning and Preprocessing

## Objective
Clean and preprocess the "Mall Customer Segmentation Data" to ensure it's ready for further analysis.

## Dataset Used
- **Name:** Mall Customer Segmentation Data  
- **Source:** Kaggle  
- **Columns:**
  - CustomerID  
  - Gender  
  - Age  
  - Annual Income (k$)  
  - Spending Score (1–100)

## Steps Performed
1. Loaded the dataset and explored the data structure.
2. Checked for missing values and handled them using `fillna()` and `dropna()`.
3. Removed duplicate records using `drop_duplicates()`.
4. Standardized the text formatting in the Gender column.
5. Cleaned column names by converting to lowercase and replacing spaces with underscores.
6. Verified and corrected data types for each column.
7. Exported the final cleaned dataset as `cleaned_dataset.csv`.

## Deliverables
- `cleaned_dataset.csv` - Cleaned and preprocessed dataset.
- `task_1_data_cleaning.ipynb` - Code notebook containing all steps.
- `README.md` - Documentation of the process.

## Tools Used
- Python
- Pandas
- Jupyter Notebook
- VS Code
