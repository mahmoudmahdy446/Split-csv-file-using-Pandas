# Splitting excel file and reformat to csv witb Pandas

# Task: Splitting and Formatting Data for Google Contacts

## Problem Statement

You have an Excel file with Arabic quad names with its mobile number and need to perform the following tasks:

1. **Reading the Excel File with Arabic Text Encoding**: Load the Excel file while preserving the Arabic character encoding. The specific encoding to use may vary depending on the file. Common encodings include 'utf-8', 'utf-16', or 'utf-16-le'.

2. **Splitting the Data into Smaller CSV Files**: Split the data into smaller CSV files, each containing 500 records, and ensure that the Arabic characters are correctly preserved.

3. **Formatting CSV Files for Google Contacts**: Format each smaller CSV file to match the CSV format of Google Contacts.

4. **Labeling Contacts in "Group Membership" Column**: Label each set of 250 names and numbers in the "Group Membership" column with labels like "1 ::: * myContacts," "2 ::: * myContacts," and so on.

## Solution

### Step 1: Reading the Excel File

- Load the Excel file using the specified encoding to preserve Arabic characters.
- Rename the column to match Google Contacts CSV format.

### Step 2: Splitting the Data

- Split the data into smaller DataFrames, each containing 500 records.
- Adjust the labeling in the "Group Membership" column to label each set of 250 names and numbers.

### Step 3: Formatting CSV Files

- Save each smaller DataFrame to a CSV file with the specified encoding.
- The resulting CSV files will contain only the "name" and "number" columns.

## How to Use

1. Run the provided code in a Python environment (e.g., Jupyter Notebook).

2. The code will perform the necessary steps to split and format the data for Google Contacts.

3. The encoding to use when reading and saving files will depend on your specific data and requirements.

## Notes

- Ensure that the Excel file is correctly formatted with the quad names and phone numbers.

- The code may require modifications based on specific file paths and names.

- Choose the appropriate encoding for your data to preserve Arabic characters.

