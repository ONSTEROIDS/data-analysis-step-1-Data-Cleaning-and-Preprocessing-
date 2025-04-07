# data-analysis-step-1-Data-Cleaning-and-Preprocessing-
data analysis step 1  (Data Cleaning and Preprocessing)
# 🧹 Data Cleaning and Preprocessing – Marketing Campaign Dataset

## 📋 Task Summary

This project involves cleaning and preprocessing a marketing campaign dataset using Python and Pandas.

### ✅ Objective:
- Identify and fix common data issues such as missing values, duplicates, inconsistent formatting, and incorrect data types.

---

## 🛠 Tools Used

- Python 3
- Pandas

---

## 🔧 Cleaning Steps Performed

1. Removed missing values using `dropna()`.
2. Removed duplicate rows using `drop_duplicates()`.
3. Standardized column names to lowercase with underscores.
4. Converted the `Dt_Customer` column to datetime format.
5. Standardized text columns like `Education` and `Marital_Status`.
6. Fixed data types for columns like `Income`, `Kidhome`, and `Teenhome`.

---

## 📁 Files Included

- `marketing_campaign.csv` – Original dataset
- `cleaned_marketing_campaign.csv` – Cleaned dataset
- `data_cleaning.py` – Python script with data cleaning steps
- `README.md` – Project documentation

---

## 📌 How to Run

```bash
# Clone the repository
git clone https://github.com/yourusername/marketing-data-cleaning.git

# Navigate to the project folder
cd marketing-data-cleaning

# Run the Python script
python data_cleaning.py
