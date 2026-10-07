# 🚗 UK Road Accident Analysis | SQL

## 📌 Project Overview

This project analyzes UK road accident data from 2015 using SQL to explore accident severity, vehicle types, and motorcycle-related accidents.

The objective is to examine road safety patterns through relational database analysis, SQL joins, aggregate functions, Common Table Expressions (CTEs), and window functions.

## 🎯 Business Questions

The project addresses four analytical questions:

1. Evaluate the median severity value of accidents involving various motorcycles.
2. Evaluate accident severity and total accidents per vehicle type.
3. Calculate the average accident severity by vehicle type.
4. Calculate the average severity and total accidents involving motorcycles.

## 🗄️ Dataset Description

The project uses three related datasets:

| Table | Description |
|---|---|
| **ACCIDENTS** | Accident records, severity codes, location, road conditions, and other accident characteristics |
| **VEHICLES** | Vehicle-level information associated with recorded accidents |
| **VEHICLE_TYPES** | Reference table containing vehicle type codes and descriptions |

The tables are connected using accident identifiers and vehicle type codes.

**Dataset period:** 2015  
**Database:** MySQL

## 🛠️ SQL Skills Demonstrated

- Relational database creation
- CSV data import
- Multi-table SQL joins
- `GROUP BY` and `ORDER BY`
- `COUNT(DISTINCT)`
- `SUM()` and `AVG()`
- Common Table Expressions (CTEs)
- Window functions
- `ROW_NUMBER()`
- `COUNT() OVER()`
- Median calculations
- Filtering and data aggregation
- Duplicate accident handling

## 📊 SQL Analysis

### 1. Median Accident Severity by Motorcycle Type

Identifies motorcycle categories and calculates the median recorded accident severity code for each category.

**SQL techniques:** Multi-table joins, CTEs, window functions, and median calculations.

### 2. Accident Severity and Total Accidents by Vehicle Type

Groups accident records by vehicle category to calculate the total number of distinct accidents and the sum of recorded severity codes.

**SQL techniques:** Joins, `SUM()`, `COUNT(DISTINCT)`, and grouping.

### 3. Average Accident Severity by Vehicle Type

Calculates the average recorded severity code for each vehicle category to compare the distribution of accident severity across vehicle types.

**SQL techniques:** Joins, `AVG()`, aggregation, and sorting.

### 4. Average Severity and Total Accidents by Motorcycle Type

Focuses on motorcycle-related accidents and calculates average severity codes and distinct accident counts for each motorcycle category.

**SQL techniques:** Filtering, joins, `AVG()`, and `COUNT(DISTINCT)`.

## 💡 Analytical Applications

**Road Safety Analysis:** Examine accident severity patterns across different vehicle categories.

**Motorcycle Analysis:** Compare accident counts and recorded severity codes among motorcycle types.

**Vehicle-Level Analysis:** Connect vehicle records with accident information for category-specific analysis.

**Data Quality:** Reduce duplicate accident counting when multiple vehicles of the same category are involved in one accident.

## ⚠️ Interpretation Notes

Accident severity is stored as a coded category. A lower numerical code does not necessarily represent a less severe accident.

Consequently, averages, medians, and sums of severity codes should be interpreted cautiously. They are descriptive calculations on coded values rather than direct measures of injury severity or total harm.

The queries identify accidents involving particular vehicle types. They do not establish that those vehicles caused the accidents.

## 💻 Tools & Technologies

- MySQL 8.0+
- SQL
- Relational Databases
- CSV Data Import
- Common Table Expressions
- Window Functions
- Data Aggregation

## 📂 Project File

The complete SQL analysis is available here:

[**View UK Road Accident SQL Analysis**](./UK_ACCIDENT.sql)

## 👩‍💻 Author

**Dixita Vandra**

M.S. Business Analytics  
Data Analyst | Business Intelligence Analyst

[LinkedIn](https://www.linkedin.com/in/dixita-vandra/) | [GitHub](https://github.com/dixitavandra)
