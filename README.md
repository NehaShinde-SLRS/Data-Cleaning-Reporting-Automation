
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

<img width="1611" height="368" alt="head" src="https://github.com/user-attachments/assets/72805f08-d3c1-43c7-8040-27c7d49456ea" />


---

### Dataset Information

<img width="647" height="498" alt="info" src="https://github.com/user-attachments/assets/0342b398-baa5-4777-a85f-402769043aa9" />


---

### Missing Values Chart

<img width="787" height="667" alt="Missing_values" src="https://github.com/user-attachments/assets/7082c30e-3624-4f38-89a5-be13dbe8d2dd" />


---

### Gender Distribution

<img width="571" height="489" alt="Gender Distribution" src="https://github.com/user-attachments/assets/56642c67-2f89-45b5-b36b-f501dfc6d78e" />


---

### Passenger Class Distribution

<img width="571" height="450" alt="Passenger Class Distribution" src="https://github.com/user-attachments/assets/8584a8a4-ea65-4f58-a49a-ac71270aeac5" />


---

### Age Distribution

<img width="571" height="455" alt="Age Distribution" src="https://github.com/user-attachments/assets/872108df-f67a-4b3e-90fa-f5c6d9c87fd3" />


---

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
