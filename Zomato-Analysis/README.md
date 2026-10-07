# 🍽️ Zomato Restaurant Data Analysis | SQL

## 📌 Project Overview

This project analyzes Zomato restaurant data using SQL to uncover insights about restaurant distribution, customer ratings, pricing, online delivery, table booking, cuisines, and restaurant popularity across different cities and countries.

The project demonstrates how SQL can be used to transform raw restaurant data into meaningful business insights through data cleaning, joins, aggregation, date analysis, ranking, and segmentation.

## 🎯 Business Questions

The analysis addresses the following questions:

1. Build calendar attributes from restaurant opening dates, including year, month, quarter, weekday, financial month, and financial quarter.
2. Find the number of restaurants by city and country.
3. Analyze restaurant openings by year, quarter, and month.
4. Determine the number of restaurants across different rating ranges.
5. Create price buckets based on the average cost for two and determine how many restaurants fall into each bucket.
6. Calculate the percentage of restaurants offering table booking.
7. Calculate the percentage of restaurants offering online delivery.
8. Identify the highest-rated restaurants in each country.
9. Identify the top five restaurants based on customer votes.
10. Identify top restaurants based on ratings and votes across countries.
11. Explore restaurant cuisines and extract individual cuisine categories.

## 🗄️ Dataset Description

The project uses two primary tables:

| Table | Description |
|---|---|
| **RESTAURANT** | Contains restaurant details including location, cuisines, ratings, votes, pricing, delivery options, table booking, and opening dates |
| **COUNTRY** | Contains country codes and corresponding country names |

The tables are connected using the restaurant's country code.

**Database:** MySQL  
**Domain:** Restaurant & Food Service Analytics

## 🛠️ SQL Skills Demonstrated

- Database and table creation
- CSV data import
- Data cleaning and transformation
- SQL joins
- Common Table Expressions (CTEs)
- Window functions
- `ROW_NUMBER()`
- `DENSE_RANK()`
- `COUNT()` and `COUNT(DISTINCT)`
- `AVG()` and aggregation
- `CASE` statements
- Percentage calculations
- Date functions
- Financial calendar calculations
- Rating and price segmentation
- String manipulation
- Cuisine extraction
- Sorting and ranking

## 📊 SQL Analysis

### 1. Calendar & Financial Date Analysis

Transforms restaurant opening dates into useful calendar dimensions including year, month, quarter, weekday, financial month, and financial quarter.

**SQL techniques:** Date functions, `DATE_FORMAT()`, `MONTH()`, `YEAR()`, `QUARTER()`, and calculated fields.

### 2. Restaurant Distribution by Country & City

Determines how restaurants are geographically distributed across countries and cities.

**SQL techniques:** Joins, `GROUP BY`, `COUNT(DISTINCT)`, and sorting.

### 3. Restaurant Opening Trends

Analyzes restaurant openings by year, quarter, and month to identify changes in restaurant growth over time.

**SQL techniques:** Date extraction, aggregation, grouping, and chronological sorting.

### 4. Restaurant Rating Analysis

Segments restaurants into rating ranges to understand the distribution of customer ratings.

**SQL techniques:** `CASE`, numeric conversion, grouping, and aggregation.

### 5. Restaurant Price Segmentation

Groups restaurants into price buckets using the average cost for two and calculates the number of restaurants within each range.

**SQL techniques:** `CASE`, numeric conversion, aggregation, and custom sorting.

### 6. Table Booking Analysis

Calculates the percentage of restaurants that offer table booking.

**SQL techniques:** `COUNT()`, percentage calculations, subqueries, and grouping.

### 7. Online Delivery Analysis

Calculates the percentage of restaurants that provide online delivery services.

**SQL techniques:** Aggregation, percentage calculations, and grouping.

### 8. Highest-Rated Restaurants by Country

Ranks restaurants within each country to identify the highest-rated establishments.

**SQL techniques:** CTEs, `DENSE_RANK()`, window functions, joins, and filtering.

### 9. Most Popular Restaurants by Votes

Identifies the top five restaurants receiving the highest number of customer votes.

**SQL techniques:** Numeric conversion, joins, `ORDER BY`, and `LIMIT`.

### 10. Top Restaurants by Rating & Votes

Ranks restaurants using both customer ratings and vote counts to identify leading restaurants across countries.

**SQL techniques:** CTEs, `ROW_NUMBER()`, partitioning, multi-column ranking, and joins.

### 11. Cuisine Analysis

Extracts individual cuisine categories from restaurant cuisine strings to support cuisine-level analysis.

**SQL techniques:** `SUBSTRING_INDEX()`, `TRIM()`, `CASE`, and string manipulation.

## 💡 Business Applications

**Market Analysis:** Understand restaurant concentration across cities and countries.

**Customer Preference Analysis:** Evaluate ratings and votes to identify highly rated and popular restaurants.

**Service Analysis:** Measure adoption of online delivery and table booking services.

**Pricing Analysis:** Segment restaurants according to average dining cost.

**Cuisine Analysis:** Explore cuisine categories and restaurant offerings.

**Expansion Analysis:** Examine historical restaurant opening patterns across different periods.

## ⚠️ Data Considerations

- Restaurant prices may be represented in different local currencies, so direct price comparisons between countries should be interpreted carefully.
- Customer ratings and votes represent different measures. Ratings indicate customer evaluation, while votes provide information about the volume of customer feedback.
- Restaurant opening dates should be converted only after confirming the date format in the source dataset.
- The analysis is based on the available dataset and does not represent live Zomato restaurant information.

## 💻 Tools & Technologies

- MySQL 8.0+
- SQL
- Relational Databases
- CSV Data Import
- Common Table Expressions
- Window Functions
- Data Aggregation
- Data Transformation

## 📂 Project File

The complete SQL analysis is available here:

[**View Zomato Restaurant Data Analysis SQL**](./Zomato%20API%20Analysis.sql)

## 👩‍💻 Author

**Dixita Vandra**

M.S. Business Analytics  
Data Analyst | Business Intelligence Analyst

[LinkedIn](https://www.linkedin.com/in/dixita-vandra/) | [GitHub](https://github.com/dixitavandra)
