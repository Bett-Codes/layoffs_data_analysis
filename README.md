# Global Layoffs Data Analysis using MySQL

## Project Overview

This project analyzes a real-world layoffs dataset using MySQL. The goal was to clean messy raw data and perform exploratory data analysis to uncover trends in company layoffs across industries, countries, and time. The project demonstrates practical SQL skills including data cleaning, aggregation, grouping, and analytical querying.

## Objectives

* Clean and standardize a real-world dataset
* Remove duplicates and handle missing values
* Analyze layoffs by company, industry, country, and year
* Identify patterns and trends in layoffs globally
* Generate insights from structured query analysis

## Dataset

The dataset contains company layoff records including:

* Company name
* Location
* Industry
* Total layoffs
* Percentage laid off
* Date
* Country
* Funding stage

The raw dataset required cleaning before analysis due to inconsistent company names, null values, and formatting issues.

## Data Cleaning Process

Data cleaning was performed entirely in MySQL using SQL queries. The following steps were carried out:

* Removed duplicate records using ROW_NUMBER()
* Trimmed company names to remove white spaces
* Standardized date format to SQL DATE type
* Handled NULL and blank values
* Standardized industry names
* Corrected inconsistencies in country naming
* Removed unusable records

All cleaning queries are documented in:
`sql/01_data_cleaning.sql`

## Exploratory Data Analysis

After cleaning, exploratory analysis was performed using SQL aggregation and grouping functions. The analysis included:

* Total layoffs by year
* Layoffs by country
* Layoffs by industry
* Companies with the highest layoffs
* Monthly layoffs trends
* Funding stage analysis

All analysis queries are available in:
`sql/02_analysis.sql`

## Key Insights

* The technology sector experienced the highest number of layoffs.
* The United States recorded the majority of layoffs compared to other countries.
* Layoffs peaked during 2022–2023 indicating economic slowdown effects.
* Startups showed higher layoff volatility compared to established companies.
* Certain companies conducted repeated layoffs across multiple periods.

## Tools Used

* MySQL
* MySQL Workbench
* Git & GitHub

## What This Project Demonstrates

This project demonstrates the ability to:

* Work with messy real-world datasets
* Perform SQL data cleaning
* Conduct exploratory data analysis using SQL
* Extract meaningful business insights from raw data
* Document and present technical work professionally

## Author

**Bett Codes**
Actuarial Science 
Dedan Kimathi University of Technology
