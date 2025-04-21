# 🧹 Mall Customer Segmentation - Data Cleaning

## 📂 Dataset

**File:** `Mall_Customers.csv`  
**Source:** [Kaggle - Customer Segmentation Data](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)

### Columns:
- `CustomerID`
- `Gender`
- `Age`
- `Annual Income (k$)`
- `Spending Score (1-100)`

---

## 🧼 Summary of Data Cleaning

- Loaded dataset using Pandas
- Verified dataset shape and structure using `shape`, `size`, and `info()`
- Checked for missing values with `isnull().sum()`  
  → No missing values found
- Renamed columns for consistency:
  - `Annual Income (k$)` → `annual_income_k$`
  - `Spending Score (1-100)` → `spending_score_1_100`
- Verified and ensured correct data types
- Checked for and confirmed no duplicate rows
- Cleaned dataset exported as:  
  📁 `mall_customers_cleaned.csv`

---

## 📁 Files Included

- `Mall Dataset Cleaning.ipynb` — Code for cleaning process
- `mall_customers_cleaned.csv` — Final cleaned dataset


---
