# Week2-Lab

# Week 2 Lab – Data Cleaning, Preparation and Analysis

## Overview

This lab focused on cleaning and preparing messy data using Python and Pandas. Real-world datasets often contain formatting issues, invalid values, duplicates, and inconsistent text, so data cleaning is an important step before any analysis can be performed.

---

## Tasks Completed

### 1. Loading the Dataset

The dataset was imported from Google Drive into a Pandas DataFrame for inspection and cleaning.

### 2. Data Type Validation

The `payment_amt` column was incorrectly stored as text due to the presence of dollar signs. The dollar signs were removed and the column was converted into a numeric data type so mathematical operations could be performed.

### 3. Cleaning Inconsistent Text Values

Several text fields contained inconsistent formatting such as:
- Different capitalisation styles
- Extra spaces
- Unnecessary punctuation

String values were standardised using title case, whitespace trimming, and text replacement functions.

### 4. Removing Invalid Data

Negative payment amounts were identified as impossible values and removed from the dataset to improve data quality.

### 5. Date Conversion

Unix timestamps were converted into readable datetime values. The dates were also converted to the Sydney timezone for better interpretation.

### 6. Duplicate Detection

The dataset was checked for duplicate rows and duplicate transaction IDs. Duplicate transaction records were removed while keeping the most appropriate record.

---

## Reflection

In this lab, I performed several data cleaning techniques using pandas. First, I checked the data types and converted the `payment_amt` column from text to numeric values by removing dollar signs. I then identified and fixed inconsistent text values by standardising capitalization, removing extra spaces, and cleaning unnecessary punctuation. Negative payment amounts were filtered out because they represented invalid data. I also 
