
# 🧹 Data Cleaning & Reporting Automation Using Python

## 📌 Project Overview

This project demonstrates a complete **Data Cleaning & Reporting Automation** workflow using **Python**, **Pandas**, and **Google Colab**. The Titanic dataset from Kaggle is used to identify and clean missing values, check for duplicate records, verify data types, and generate automated reports and visual summaries.

The cleaned dataset is then saved for further analysis and visualization.

---

## 🎯 Objectives

- Import and inspect a dataset using Python.
- Identify missing values, duplicate records, and inconsistent data.
- Clean the dataset using Pandas.
- Generate automated reports.
- Create visual summaries.
- Save the cleaned dataset for further analysis.

---

## 📂 Dataset

**Dataset Name:** Titanic - Machine Learning from Disaster

**Source:** Kaggle

**File Used:** `train.csv`

### Dataset Columns

- PassengerId
- Survived
- Pclass
- Name
- Sex
- Age
- SibSp
- Parch
- Ticket
- Fare
- Cabin
- Embarked

---

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- Matplotlib

---

## 📋 Tasks Performed

### ✔ Dataset Inspection

- Loaded the Titanic dataset
- Displayed the first few rows
- Examined dataset information
- Checked dataset dimensions
- Displayed summary statistics

### ✔ Data Cleaning

- Identified missing values
- Filled missing values
  - **Age** → Median
  - **Cabin** → "Unknown"
  - **Embarked** → Mode
- Checked duplicate records
- Removed duplicate records (if any)
- Verified data types
- Removed extra spaces from text columns

### ✔ Automated Reporting

Generated a report containing:

- Column Name
- Data Type
- Missing Values

Saved as:

`Data_Cleaning_Report.csv`

### ✔ Data Visualization

Created the following visualizations:

- Missing Values Chart
- Gender Distribution
- Passenger Class Distribution
- Age Distribution

### ✔ Output

Saved the cleaned dataset as:

`cleaned_train.csv`

---

## 📁 Project Structure

```text
Data-Cleaning-Reporting-Automation/
│
├── Data_Cleaning.ipynb
├── cleaned_train.csv
├── Data_Cleaning_Report.csv
├── requirements.txt
├── README.md
├── train.csv
│
└── images/
    ├── head.png
    ├── info.png
    ├── missing_values.png
    ├── gender_distribution.png
    ├── passenger_class.png
    ├── age_distribution.png
    └── 

---

## 📊 Project Screenshots

### Dataset Preview
![Dataset Preview](Images/head.png)

### Dataset Information
![Dataset Information](Images/info.png)

### Missing Values Chart
![Missing Values Chart](Images/Missing%20values.png)

### Gender Distribution
![Gender Distribution](Images/Gender%20Distribution.png)

### Passenger Class Distribution
![Passenger Class Distribution](Images/Passenger%20Class%20Distribution.png)

### Age Distribution
![Age Distribution](Images/Age%20Distribution.png)

## 📈 Results

- Successfully imported and inspected the Titanic dataset.
- Detected missing values in **Age**, **Cabin**, and **Embarked** columns.
- Filled missing values using appropriate techniques.
- Verified that no duplicate records remained after cleaning.
- Generated an automated data cleaning report.
- Created visual summaries for better understanding of the dataset.
- Saved the cleaned dataset for further analysis.

---

## 📦 Requirements

Install the required libraries using:

```bash
pip install pandas matplotlib
```
