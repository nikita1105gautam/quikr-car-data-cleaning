# Quikr Car Data Cleaning Project

## 📌 Project Overview
This project focuses on cleaning and preparing the Quikr Car dataset using Python and Pandas. The goal is to improve data quality by handling missing values, removing duplicate records, and converting columns into appropriate data types.

## 🎯 Objectives
- Load and explore the car dataset.
- Identify missing values and duplicate records.
- Clean car prices by removing commas and handling invalid price entries.
- Convert year, price, and kilometres driven into numeric data types.
- Remove rows containing missing values.
- Save the cleaned dataset as a CSV file.

## 🛠️ Tools & Technologies
- Python
- Pandas
- NumPy
- Google Colab
- GitHub

## 📂 Dataset Information
The dataset contains information about used cars, including:

- `name` – Car name
- `company` – Car manufacturer
- `year` – Manufacturing year
- `Price` – Car price
- `kms_driven` – Kilometres driven
- `fuel_type` – Fuel category

## 🧹 Data Cleaning Steps
1. Loaded the CSV dataset using Pandas.
2. Checked missing values and duplicate records.
3. Removed duplicate rows.
4. Removed commas from price and kilometres values.
5. Handled invalid price entries such as `Ask For Price`.
6. Converted numeric columns to appropriate data types.
7. Removed rows containing missing values.
8. Checked the cleaned dataset and saved it as a CSV file.

## 📊 Final Results

| Metric | Result |
|---|---:|
| Original Records | 745 |
| Final Records | 724 |
| Total Columns | 6 |
| Missing Values | 0 |
| Duplicate Records | 0 |

## 📁 Project Files
- `quikr_car.csv` – Original dataset
- `quikr_car_cleaned.csv` – Cleaned dataset
- `Quikr_Car_Data_Cleaning.ipynb` – Google Colab notebook containing the cleaning process
- `README.md` – Project documentation

*Note: Add the notebook and original dataset to the repository if you have permission to share them. Update the filenames if yours are different.*

## ▶️ How to Run the Project
1. Download or clone this repository.
2. Open the Jupyter Notebook in Google Colab.
3. Upload the original CSV dataset.
4. Run the notebook cells in order.
5. Review the cleaned data and export the final CSV file.

## 📚 What I Learned
- Data cleaning using Pandas
- Handling missing and duplicate values
- Working with CSV files
- Converting data types
- Basic data quality checks
- Using Google Colab for data analysis

## 👩‍💻 Author
Created as a Data Cleaning and Data Analysis practice project using Python.

