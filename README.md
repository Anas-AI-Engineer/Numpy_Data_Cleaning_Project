# 🧹 NumPy Data Cleaning Project

A Python-based data cleaning project built with **NumPy** that demonstrates essential data preprocessing techniques, including missing value imputation and duplicate removal.

This project focuses on preparing raw datasets for further data analysis and machine learning tasks.

---

## 📌 Project Overview

Real-world datasets often contain missing values and duplicate records, which can affect data analysis and machine learning results.

In this project, I created a simulated dataset and implemented data cleaning techniques using NumPy to make the dataset more organized and reliable.

## ✨ Key Features

- **Dataset Generation:** Generate a random numerical dataset using NumPy.
- **Missing Value Injection:** Introduce random `NaN` values to simulate real-world data problems.
- **Mean Imputation:** Replace missing values with the mean of their respective columns.
- **Median Imputation:** Replace missing values with the median of their respective columns.
- **Duplicate Removal:** Identify and remove duplicate rows.
- **Data Verification:** Check remaining missing values and inspect the final dataset shape.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| NumPy | Numerical computing and data cleaning |

## 📂 Project Structure

```text
numpy-data-cleaning-project/
│
├── main.py
└── README.md
```

## ⚙️ Installation & Usage

**1. Clone the repository**

```bash
git clone YOUR_REPOSITORY_URL
```

**2. Navigate to the project directory**

```bash
cd numpy-data-cleaning-project
```

**3. Install NumPy**

```bash
pip install numpy
```

**4. Run the project**

```bash
python main.py
```

## 📊 Data Cleaning Workflow

```text
Raw Dataset
     |
     v
Generate Dataset
     |
     v
Insert Missing Values
     |
     v
Missing Value Imputation
  (Mean / Median)
     |
     v
Remove Duplicate Rows
     |
     v
Final Cleaned Dataset
```

## 🧠 What I Learned

Through this project, I practiced:

- Creating and manipulating NumPy arrays.
- Working with array dimensions and shapes.
- Using NumPy indexing and slicing.
- Handling missing values with statistical methods.
- Implementing reusable Python functions.
- Removing duplicate records.
- Verifying data quality after preprocessing.

## 🚀 Future Improvements

- Add outlier detection.
- Implement standardization and normalization.
- Compare different imputation techniques.
- Generate data cleaning reports.
- Work with real-world datasets.

## 🎯 Project Goal

The goal of this project is to strengthen my Python and NumPy skills while building a foundation in data preprocessing for Machine Learning and AI Engineering.

---

**Author:** Anas

**Field:** AI Engineering | Python | Data Analysis

**Status:** Completed ✅
