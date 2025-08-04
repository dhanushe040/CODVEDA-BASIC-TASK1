# BASIC-TASK1
# 📊 CODVEDA BASIC TASK 1 – Data Cleaning and Preprocessing

## 📝 Task Overview
This task focuses on preparing raw data for analysis by cleaning and standardizing it using **Python and Pandas**. The goal is to ensure the dataset is accurate, consistent, and ready for further exploration or modeling.

---

## 🔧 Steps Performed

### 1. Load Dataset
- Imported the dataset using `D:\codveda\Data Set For Task\Churn Prdiction Data\churn-bigml-80.csv.read_csv()`.
- Verified structure using `.head()`, `.info()`, and `.describe()`.

### 2. Handle Missing Values
- Identified missing values using `.isnull().sum()`.
- Applied appropriate strategies:
  - **Imputation**: Filled missing values using mean/median/mode.
  - **Removal**: Dropped rows/columns with excessive missing data.

### 3. Remove Duplicates
- Checked for duplicate rows using `.duplicated()`.
- Removed duplicates with `.drop_duplicates()`.

### 4. Standardize Data Formats
- **Date Formats**: Converted inconsistent date strings to `datetime` objects.
- **Categorical Variables**: Standardized labels (e.g., "Male", "male" → "Male").
- **Numerical Columns**: Ensured consistent data types and ranges.

---

## 📁 Files Included
- `t1 data clean,preprocess.ipynb`: Jupyter Notebook with full code and explanations.
- `README.md`: Project summary and documentation.

---

## 🚀 Technologies Used
- Python 🐍
- Pandas 🐼
- Jupyter Notebook 📓

---

## 📌 Outcome
The cleaned dataset is now:
- Free of missing and duplicate
