# adobe-indesign-price-automation
Adobe InDesign JavaScript automation tool for updating product prices from CSV files.

# Adobe InDesign Price Automation Tool

A portfolio automation project for Adobe InDesign.

This tool updates product prices in Adobe InDesign documents using data from a CSV file.  
The script matches product codes from the document with product codes in the CSV file and replaces outdated prices automatically.

## Features

- Reads product data from a CSV file
- Finds product codes in an Adobe InDesign document
- Updates prices based on matching product codes
- Allows the user to configure which products should be updated
- Reduces manual work and helps avoid copy-paste errors
- Runs directly inside Adobe InDesign as a JavaScript script

## Tech Stack

- JavaScript
- Adobe InDesign scripting
- CSV data processing
- Workflow automation

## Use Case

This project was created to automate a repetitive catalog update workflow.  
Instead of manually searching for product codes and changing prices one by one, the script reads updated prices from a CSV file and applies them to the InDesign document.

## Example CSV

```csv
product_code,old_price,new_price
ABC-001,99.99,89.99
ABC-002,149.99,129.99
ABC-003,59.99,49.99
