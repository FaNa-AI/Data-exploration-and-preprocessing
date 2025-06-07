

# House Price Data Cleaning Script

This Python script performs initial data cleaning and preprocessing on the House Price dataset stored in an Excel file. The cleaned data is saved for further analysis or modeling.

---

## Dataset

* **Input file:** `HousePricePrediction.xlsx` (Excel file, Sheet1)
* **Output file:** `Cleaned_HousePricePrediction.xlsx` (cleaned data saved in Excel format)

---

## Data Cleaning Steps

1. **Initial Data Inspection**

   * Prints dataset info and descriptive statistics.

2. **Filter Invalid Records**

   * Removes rows with zero or negative values in key columns:

     * `LotArea`
     * `YearBuilt`
     * `YearRemodAdd`
     * `TotalBsmtSF`
     * `SalePrice`

3. **Handle Missing Data**

   * Drops rows with any missing (NaN) values.

4. **Remove Non-numeric Columns**

   * Keeps only numeric columns for further processing.

5. **Save Cleaned Data**

   * Saves the cleaned dataset into `Cleaned_HousePricePrediction.xlsx`.

---

## How to Use

1. Make sure the input Excel file is available at the specified path (`file_path`).

2. Install necessary packages:

```bash
pip install pandas openpyxl
```

3. Run the script:

```bash
python house_price_cleaning.py
```

---

## Output

* A cleaned Excel file named `Cleaned_HousePricePrediction.xlsx`
* Prints the number of records remaining after cleaning.

---

