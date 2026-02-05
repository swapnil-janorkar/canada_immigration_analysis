Canada Immigration Data Analysis using Pandas
Project Overview

This project performs data analysis and preprocessing on the Canada Immigration dataset using Python and Pandas. The goal is to explore the dataset, clean unnecessary data, engineer useful features, and generate statistical insights.

Technologies Used

Python

Pandas

NumPy

Jupyter Notebook

Dataset Description

Source: IBM Skills Network

File Format: Excel (.xlsx)

Sheet Used: Canada by Citizenship

Description: Immigration data of individuals migrating to Canada from various countries across multiple years.

Tasks Performed
Data Loading

Imported the Excel dataset using pandas.read_excel()

Skipped non-essential header and footer rows

Data Exploration

Examined dataset structure using head(), tail(), shape, and info()

Reviewed statistical summaries using describe()

Data Cleaning

Removed irrelevant columns such as AREA, REG, DEV, Type, and Coverage

Renamed columns for clarity:

OdName → Country

AreaName → Continent

RegName → Region

Feature Engineering

Created a Total column representing the sum of immigration values across all years for each country

Data Validation

Checked for missing values

Verified data consistency and types

Project Structure
Canada-Immigration-Pandas-Analysis
│── data_visP1.ipynb
│── README.md

How to Run

Install dependencies:

pip install pandas numpy


Launch Jupyter Notebook:

jupyter notebook


Open and run data_visP1.ipynb

Learning Outcomes

Understanding real-world datasets using Pandas

Data cleaning and preprocessing techniques

Feature engineering and statistical analysis

Working with Excel data in Python
