# Titanic Data Cleaning Project

This project loads the Titanic dataset, cleans missing data, and summarizes it using Python and Pandas.

## Steps performed
1. Loaded the Titanic dataset using Pandas.
2. Checked for missing values with `df.info()` and `df.isnull().sum()`.
3. Filled missing values:
   - **Embarked:** filled missing entries with `'S'`, the most common port.
   - **Cabin:** replaced missing values with `'Unknown'`.
   - **Age:** replaced missing values with the median age (`28.0`).
4. Verified no missing values remained.
5. Summarized the cleaned dataset with `.describe()` and `.value_counts()`.

## How to run
1. Clone this repository:
   ```bash
   git clone https://github.com/abdifatah10101/titanic-data-cleaning.git
