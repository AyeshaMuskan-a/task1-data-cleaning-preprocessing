# Task 1: Data Cleaning and Preprocessing

##  Internship
DataX Labs — Data Analyst Internship

## 📌 Objective
Clean and prepare a raw dataset by handling missing values, removing duplicates,
standardizing text values, fixing data types, and engineering new features.

## 🛠️ Tools Used
- Python (Pandas, NumPy)
- Jupyter Notebook (VS Code)

## 📂 Dataset
- **Name:** Customer Personality Analysis
- **Source:** [Kaggle](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis)
- **Size:** 2240 rows × 29 columns

## 🔧 Cleaning Steps Performed
1. Loaded dataset and inspected shape, dtypes, and missing values
2. Filled 24 missing `Income` values with median
3. Removed duplicate rows
4. Fixed inconsistent `Marital_Status` values (Alone/Absurd/YOLO → Single)
5. Converted `Dt_Customer` column to datetime format
6. Standardized `Education` and `Marital_Status` text to title case
7. Created new `Age` column derived from `Year_Birth`
8. Dropped constant columns: `Z_CostContact` and `Z_Revenue`
9. Saved cleaned dataset as `customer_cleaned_data.csv`

## 📁 Files in This Repository
| File | Description |
|---|---|
| `task1_cleaning.ipynb` | Main Python notebook with all cleaning steps |
| `customer_personality_analysis.csv` | Original raw dataset |
| `customer_cleaned_data.csv` | Final cleaned dataset |
| `README.md` | Project documentation |

## 📊 Result
| | Before | After |
|---|---|---|
| Rows | 2240 | 2240 |
| Columns | 29 | 28 |
| Missing Values | 24 | 0 |
| Duplicate Rows | 0 | 0 |
