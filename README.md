# Task 2: Data Cleaning and Exploratory Data Analysis (EDA)

## 📌 Objective
The goal of this task is to perform **data cleaning** and **exploratory data analysis (EDA)** on the Titanic dataset from Kaggle. This includes identifying and handling missing data, removing irrelevant features, and visualizing trends and relationships within the dataset.

---

## 🗂️ Files Included
- `train.csv` – Training dataset containing passenger details and survival info.
- `test.csv` – Test dataset (not used directly in EDA but part of the competition).
- `task2_eda.py` – Python script that performs data cleaning and generates EDA graphs.
- `task2_EDA_report.pdf` – A PDF report that includes all EDA graphs and findings.
- `cleaned_train.csv` – Cleaned version of the training data after preprocessing.
- `README.md` – This file.

---

## 🧪 Steps Performed

### ✅ Data Cleaning
- Filled missing `Age` values with the **median**.
- Filled missing `Embarked` values with the **mode**.
- Dropped the `Cabin` column due to too many missing values.
- Dropped the `Ticket` column due to limited relevance.

### 📊 Exploratory Data Analysis (EDA)
- Visualized survival distribution.
- Analyzed survival rates by:
  - Sex
  - Passenger Class
  - Age group
- Created a **correlation heatmap** to study relationships between numerical features.

---

## 📥 How to Run the Script

### 🔧 Requirements
- Python (Recommended: 3.8+)
- Libraries: `pandas`, `seaborn`, `matplotlib`

Install libraries if needed:
```bash
pip install pandas seaborn matplotlib
