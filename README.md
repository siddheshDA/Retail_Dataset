# Retail Data Cleaning – Task 1 (Data Analyst Internship)

## 📝 Task Objective

This project is part of a data analyst internship assignment. The goal is to clean and preprocess a raw retail dataset containing missing values, duplicate records, inconsistent text formatting, and mixed date formats.

## 📂 Dataset Used

A simulated **Retail Sales Dataset** with 100+ rows. The dataset includes:
- Customer information
- Gender and Country
- Purchase date
- Product category
- Age, Sales value, and Email

## 🧼 Data Cleaning Steps (Performed using Python - Pandas)

### ✅ Cleaning Actions:
1. **Removed Duplicates:**
   - Used `.drop_duplicates()` to eliminate exact duplicate rows.

2. **Handled Missing Values:**
   - Dropped rows where critical fields like `Full Name`, `Sales ($)`, or `Email` were missing.

3. **Standardized Text Fields:**
   - Standardized `Gender` (e.g., "M", "F", "male", "female") to "Male" and "Female".
   - Cleaned `Country` names to title case (e.g., "INDIA" → "India").
   - Standardized `Product Category` to title case.

4. **Date Formatting:**
   - Converted `Purchase Date` into a consistent format: `dd-mm-yyyy`.

5. **Renamed Columns:**
   - Renamed all columns to lowercase with snake_case (e.g., `Full Name` → `full_name`).

6. **Corrected Data Types:**
   - Converted `age` to integer.
   - Converted `sales_($)` to float.

## 📁 Files Included
- `retail_raw_dataset.csv` – Original uncleaned dataset
- `retail_cleaned_dataset.csv` – Final cleaned version
- `cleaning_script.py` – Python script used for preprocessing
- `README.md` – Task summary

## ⚙️ Tools Used
- Python 3.x
- Pandas
- Jupyter Notebook / Google Colab (Optional)
- Excel (for cross-validation)

## 📌 Learning Outcomes
- Identified and resolved real-world data issues
- Practiced cleaning data using Pandas
- Understood the importance of preprocessing before analysis or modeling

---

**Created for Internship Task 1 – Data Cleaning and Preprocessing**
