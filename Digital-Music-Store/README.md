# 🎵 Digital Music Store Analysis

## 📌 Project Overview

This project analyzes a digital music store database using SQL to uncover insights related to customer spending, sales performance, music preferences, artists, and geographic markets.

The analysis progresses from basic SQL queries to more advanced techniques involving multiple-table joins, subqueries, Common Table Expressions (CTEs), aggregate functions, and window functions.

## 🎯 Business Questions

The analysis addresses questions such as:

- Who is the most senior employee?
- Which countries generate the most invoices?
- What are the highest invoice totals?
- Which city generates the most revenue?
- Who is the highest-spending customer?
- Which customers listen to Rock music?
- Which artists have the most Rock tracks?
- Which tracks are longer than the average song length?
- How much does each customer spend on different artists?
- What is the most popular music genre in each country?
- Who is the highest-spending customer in each country?

## 🗄️ Database

The analysis uses a relational music-store database containing information about:

- Customers
- Employees
- Artists
- Albums
- Tracks
- Genres
- Invoices
- Invoice Lines
- Playlists
- Media Types

The relationships between these tables allow customer transactions to be connected with individual tracks, albums, artists, and genres.

## 🛠️ SQL Skills Demonstrated

- SELECT statements
- WHERE filtering
- GROUP BY and ORDER BY
- Aggregate functions: `SUM()`, `COUNT()`, `AVG()`, `MAX()`
- INNER JOIN / multi-table joins
- Subqueries
- Common Table Expressions (CTEs)
- Window functions
- `DENSE_RANK()`
- Data aggregation
- Revenue and customer-spending analysis
- Handling tied rankings
- Relational database analysis

## 📊 Analysis

### Easy Queries

The first section focuses on foundational SQL analysis, including employee seniority, invoice distribution by country, top invoice values, city-level revenue, and identifying the highest-spending customer.

### Moderate Queries

The intermediate section uses multiple-table joins and subqueries to identify Rock music listeners, determine the artists with the most Rock tracks, and find tracks with durations above the overall average.

### Advanced Queries

The advanced section analyzes customer spending by artist and uses CTEs and window functions to identify the most popular genre in each country while preserving ties.

It also determines the highest-spending customer in each country and returns multiple customers when the highest spending amount is shared.

## 💡 Key Analytical Concepts

This project demonstrates how relational data can be transformed into business insights by connecting transactional information with customer and product-level data.

**Customer Analysis:** Identifying high-value customers and analyzing their spending behavior.

**Geographic Analysis:** Comparing invoice activity and revenue across countries and cities.

**Product Analysis:** Evaluating track, genre, album, and artist popularity.

**Revenue Analysis:** Aggregating invoice and purchase data to identify important customers and markets.

## 💻 Tools & Technologies

- MySQL
- SQL
- Relational Databases
- CSV Data Import
- Data Aggregation
- Business Analysis

## 📂 Project File

The complete SQL analysis is available here:

[**View Digital Music Store SQL Analysis**](./DIGITAL_MUSIC_STORE.sql)

## 👩‍💻 Author

**Dixita Vandra**

M.S. Business Analytics  
Data Analyst | Business Intelligence Analyst

[LinkedIn](https://www.linkedin.com/in/dixita-vandra/) | [GitHub](https://github.com/dixitavandra)
