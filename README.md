# Data-Cleaning-
Data Cleaning with Pandas

Project Overview

This repository contains two key components:

Customer Call List Dataset: A dataset provided in an Excel file (Customer Call List.xlsx) containing customer call information.

Data Cleaning Notebook: A Jupyter Notebook (Data cleaning in Pandas.ipynb) demonstrating how to clean, preprocess, and manipulate the dataset using Python's Pandas library.

The purpose of this project is to showcase data cleaning techniques using a real-world dataset, preparing it for analysis or further processing.

Repository Contents

Files

Customer Call List.xlsx

Raw dataset with information on customer calls.

The file includes fields such as customer name, contact details, call duration, call status, and other relevant attributes.

Data cleaning in Pandas.ipynb

A Python notebook demonstrating:

Importing and exploring the dataset.

Handling missing values.

Removing duplicates.

Standardizing column names.

Formatting data types.

Additional transformations or feature engineering steps.

How to Use

Prerequisites

Ensure you have the following installed:

Python 3.8 or above

Jupyter Notebook or JupyterLab

Pandas library (v1.3.0 or above)

OpenPyXL library (for handling Excel files)

Open the Jupyter Notebook:

jupyter notebook "Data cleaning in Pandas.ipynb"

Run the cells step-by-step to understand the data cleaning process.

Data Cleaning Process

Loading the Dataset

Read the Excel file into a Pandas DataFrame using read_excel().

Exploratory Data Analysis (EDA)

Check the first few rows of the dataset using head().

Inspect the data types and null values with info() and isnull().sum().

Cleaning Steps

Handle Missing Values: Fill or drop rows with missing data.

Remove Duplicates: Identify and eliminate duplicate rows.

Normalize Data: Standardize formats (e.g., phone numbers, dates).

Fix Data Types: Convert columns to appropriate data types (e.g., integers, floats, datetime).

Output the Cleaned Data

Save the cleaned dataset to a new Excel or CSV file for future use.

Key Features

Real-world dataset with potential inconsistencies.

Step-by-step explanation of data cleaning processes.

Code and comments optimized for clarity and reusability.

Contributing

Feel free to submit issues or pull requests to enhance the project. Contributions can include:

Additional cleaning techniques.

More advanced transformations or analyses.

Improvements to the documentation.
