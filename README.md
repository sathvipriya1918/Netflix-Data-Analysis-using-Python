# Netflix Data Analysis using Python

Internship project for Auspify Technologies: Data Analysis Using Python Internship (Nov-Dec 2026).

## Overview
This project analyzes the Netflix Movies and TV Shows dataset using Python. It covers data cleaning, content type analysis, country-wise analysis and release-year trends.

## Tools Used
Python, Pandas, Matplotlib, Seaborn, Jupyter Notebook, Git

## Project Structure
- data/ : raw dataset (`Dataset.csv`) and cleaned dataset (`netflix_cleaned.csv`)
- task1_cleaning.ipynb: Data cleaning and preparation
- task2_content_type.ipynb: Movies vs TV Shows analysis
- task3_country.ipynb: Country-wise content analysis
- task4_trends.ipynb: Trend analysis by release year
- screenshots/: Screenshots of completed tasks

## Tasks Completed

### Task 1: Data Cleaning and Preparation
- Found hidden missing values ("Not Given") in 2,588 director and 287 country entries and replaced them with "Unknown".
- Removed 3 duplicate titles (8,790 rows reduced to 8,787).
- Standardized columns, converted dates, and added year, month and duration columns.

### Task 2: Content Type Analysis
- Movies make up 69.7% of the catalog (6,124) and TV shows 30.3% (2,663).
- The TV show share of additions has risen every year since 2018.

### Task 3: Country-Wise Analysis
- The United States has the most titles (3,240, 38.1%), followed by India (1,056).
- The top 10 countries make up 78.0% of titles with a known country.

### Task 4: Trend Analysis by Release Year
- Releases peaked in 2018 with 1,144 titles. 2021 is incomplete because the data ends in September 2021.
- TV shows passed movies in 2021 releases (315 vs 277).

## How to Run
1. Install the libraries: `pip install pandas matplotlib seaborn jupyter`
2. Run `jupyter notebook`
3. Open the notebooks in order, from Task 1 to Task 4.
