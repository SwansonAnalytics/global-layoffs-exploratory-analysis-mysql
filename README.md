# Global Layoffs Exploratory Analysis with MySQL

## Project Overview

This project uses MySQL to explore patterns in a global layoffs dataset. It examines how reported layoffs vary across companies, countries, years, and company funding stages.

The analysis uses the `layoffs_staging2` table prepared in my [data cleaning project](https://github.com/SwansonAnalytics/layoffs-data-cleaning-mysql). The raw dataset is available in that repository.

## Questions Explored

- What were the largest reported layoff totals and percentages?
- Which companies reported the most layoffs overall?
- How did reported layoffs vary by country, year, and funding stage?
- How did monthly layoff totals change over time?
- What does the rolling monthly total show?
- Which five companies had the highest reported layoffs in each year?

## SQL Techniques

Aggregate functions, `GROUP BY`, date functions, common table expressions (CTEs), window functions, rolling totals, and `DENSE_RANK()`.

## File

- `Exploritory Data Analysis Project.sql` — SQL queries for the exploratory analysis

## Dataset Source

[Global layoffs dataset on Kaggle](https://www.kaggle.com/datasets/swaptr/layoffs-2022)
