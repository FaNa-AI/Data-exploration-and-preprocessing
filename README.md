



# 🏠 House Price Data Cleaning Script

Clean and preprocess the house price dataset from an Excel file, preparing it for further analysis or modeling by removing invalid, missing, or non-numeric data.

---

## 📂 Dataset

* **Input:** `HousePricePrediction.xlsx` (Excel file, Sheet1)
* **Output:** `Cleaned_HousePricePrediction.xlsx` (cleaned and saved Excel file)

---

## 🧹 Data Cleaning Steps

1. **Initial Exploration**
   Display dataset info and summary statistics.

2. **Filter Invalid Records**
   Remove rows with zero or negative values in critical columns:

   * `LotArea`
   * `YearBuilt`
   * `YearRemodAdd`
   * `TotalBsmtSF`
   * `SalePrice`

3. **Handle Missing Data**
   Drop rows containing any NaN values.

4. **Keep Numeric Columns Only**
   Remove all non-numeric columns to ensure clean data for modeling.

5. **Save Cleaned Dataset**
   Export the processed data to `Cleaned_HousePricePrediction.xlsx`.

---

## 🚀 How to Use

1. Place your input Excel file at the correct path (`file_path`).
2. Install dependencies:

   ```bash
   pip install pandas openpyxl
   ```
3. Run the cleaning script:

   ```bash
   python house_price_cleaning.py
   ```

---

## 📊 Output

* A clean, preprocessed Excel file: `Cleaned_HousePricePrediction.xlsx`.
* Console report showing the count of records remaining after cleaning.

---

## 🎯 Why Use This Script?

* Automates tedious data cleaning steps.
* Ensures dataset integrity by removing invalid or missing data.
* Prepares data perfectly for machine learning models or further analysis.

