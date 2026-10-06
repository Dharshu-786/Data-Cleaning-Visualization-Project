# Data Cleaning & Visualization Project

## Project Overview

This project focuses on cleaning, preprocessing, analyzing, and visualizing a raw employee dataset using Python.

The project involves handling missing values, duplicate records, date formatting, and salary outliers. After cleaning the data, different visualizations were created to identify useful patterns and insights from the dataset.
## Dataset

The dataset contains employee information such as:

- Name
- Age
- Salary
- Join Date
- Department

## Tools & Technologies

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook
## Data Cleaning Process

The following steps were performed to clean and prepare the dataset:

### 1. Handling Missing Values

Missing values were identified using Pandas. Missing values in the `Age` and `Salary` columns were filled using the median of the respective columns.

### 2. Removing Duplicate Records

Duplicate rows were identified and removed to avoid repeated records in the analysis.

### 3. Date Conversion

The `Join_Date` column was converted from text format to datetime format using Pandas.

### 4. Outlier Detection and Handling

Salary outliers were detected using the Interquartile Range (IQR) method. The extreme values were capped at the upper IQR boundary to reduce their influence while preserving the records.
## Visualizations

The cleaned dataset was analyzed using the following visualizations:

- Salary Distribution
- Employees by Department
- Average Salary by Department
- Age vs Salary
- Age Distribution

## Key Insights

- HR has the highest number of employees, with 22 employees.
- Finance and IT have 10 employees each.
- IT has the highest average salary among the departments.
- Finance has the lowest average salary among the departments.
- Most employee salaries are concentrated around the ₹65,000–₹80,000 range.
- The visualizations help identify salary patterns and employee distribution across departments.
## Conclusion

This project provided practical experience in data cleaning, preprocessing, and visualization using Python.

The raw dataset was successfully cleaned by handling missing values, removing duplicate records, converting date formats, and handling salary outliers using the IQR method.

The cleaned data was then visualized to understand employee distribution, salary patterns, and department-wise differences.

This project demonstrates the use of Pandas, Matplotlib, and Seaborn for basic data analysis and visualization.