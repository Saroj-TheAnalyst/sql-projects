# SQL Projects - Tableau Analysis

Welcome to the SQL Projects repository, where I have shared various projects related to data analysis and visualization using SQL and Tableau. This repository includes datasets, SQL queries, and Tableau visualizations that explore different domains, including movie datasets, Covid-19 statistics, and more.

## Table of Contents

- [Overview](#overview)
- [Project List](#project-list)
- [Installation Instructions](#installation-instructions)
- [SQL Queries](#sql-queries)
- [License](#license)
- [Contact](#contact)

## Overview

This repository contains SQL projects that provide insights into various datasets, utilizing SQL queries and Tableau visualizations. The primary goal is to demonstrate SQL's power in data analysis and visualization by answering complex business questions and generating reports that are insightful and actionable.

The SQL queries used in these projects are intended for use with Tableau and other BI tools for deeper data exploration.

## Project List

### 1. **Movies Dataset**
This project uses a dataset of movies, including information such as movie names, genres, release years, ratings, and budgets. The objective is to use SQL queries to analyze trends in the movie industry, such as:

- The highest-rated movies.
- The relationship between budget and revenue.
- The most popular genres.

**Files**: 
- `movies.csv`: Dataset containing movie-related data.
- SQL Queries: A collection of queries to analyze the dataset.
  
### 2. **Covid-19 Analysis**
This project focuses on COVID-19 data analysis. Using SQL queries, we explore COVID-19 case numbers, death rates, and vaccination rates, offering insights into pandemic trends across different regions and countries.

**Files**:
- `CovidDeaths.csv`: Dataset with COVID-19 case and death data.
- SQL Queries: Various queries that analyze the dataset, from basic statistics to more advanced trends.

## Installation Instructions

### Prerequisites

Make sure you have the following installed:

- **Python**: For running scripts and data manipulation.
- **SQL Database**: You will need a SQL database (MySQL, PostgreSQL, SQLite, etc.) to execute the queries.
- **Tableau** (Optional): For visualizing the queries and dashboards.

## Set Up SQL Database

To begin with, you need to set up an SQL database where you will store the data from the CSV files. Follow the steps below to set up your database:

1. **Create a New Database**  
   Depending on the SQL platform you are using (MySQL, PostgreSQL, etc.), create a new database. Here is an example of how to do it on MySQL:
   
   ```sql
   CREATE DATABASE movie_analysis;

### Explanation:
- **Create Tables**: Details the process of creating tables in your SQL database.
- **Import the CSV Files**: Provides SQL commands to load the CSV files into your database, depending on the SQL platform you're using (MySQL or PostgreSQL).

