# Data-Analysis-using-NumPy-and-Pandas
This repository contains a Jupyter Notebook demonstrating foundational data manipulation, numerical computation, and exploratory data analysis techniques using Python's **NumPy** and **Pandas** libraries.
---
## 📋 Overview

The assignment is divided into three core sections, each focusing on specific data structures and operations:

1. **NumPy Array Operations:** Analyzing daily temperature records over two weeks using 1D and 2D arrays.
2. **Pandas Series:** Creating, indexing, filtering, and manipulating student rank and marks data.
3. **Pandas DataFrame:** Exploring, grouping, filtering, and updating retail transaction records.

---

## 🚀 Key Tasks & Operations Covered

### 1. NumPy Array Operations
* **1D & 2D Array Creation:** Constructed arrays representing weekly temperature data (`temperatures_w1` and `temperatures`).
* **Array Inspection:** Checked array properties including `.shape`, `.ndim`, `.dtype`, and `.size`.
* **Mathematical Computations:** 
  * Converted temperatures from Celsius to Fahrenheit using vectorized operations: $F = (C \times \frac{9}{5}) + 32$.
  * Calculated summary statistics (`np.max()`, `np.min()`, and `np.mean()`).
* **Slicing & Indexing:** Extracted specific subsets of data (first three days, middle three days, and weekend temperatures across multiple weeks).

### 2. Pandas Series
* **Series Initialization:** Created a custom-indexed Series mapping student ranks (`Rank1` to `Rank5`) to their respective marks.
* **Data Access & Filtering:** 
  * Retrieved elements using label-based indexing (`.loc`) and integer-position indexing (`.iloc`).
  * Applied boolean masking to filter scores greater than 90.
* **Series Manipulation:** Updated specific values, dropped entries using `.drop()`, and performed element-wise division to compute CGPA.

### 3. Pandas DataFrame
* **DataFrame Construction:** Built a `transactions` dataset containing `TransactionID`, `ProductCategory`, `Region`, and `Amount`.
* **Exploratory Data Analysis (EDA):** 
  * Inspected data structure with `.head()`, `.tail()`, `.shape`, `.columns`, and `.dtypes`.
  * Analyzed categorical distributions using `.value_counts()` and `.unique()`.
  * Aggregated regional sales averages using `.groupby()`.
* **Conditional Filtering & Updates:** 
  * Filtered records using multiple boolean conditions (`Region == 'North'` & `Amount > 200`).
  * Updated cell values conditionally via `.loc`, engineered a new `Discount` feature, and removed specific rows and columns.

---

## 🛠️ Technologies Used

* **Python 3**
* **NumPy** – Numerical computing and array operations
* **Pandas** – Data structures and data analysis tools
* **Jupyter Notebook** – Interactive coding environment

---
This project is open-source and available for educational purposes.
