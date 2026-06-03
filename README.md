# UiPath Cash Flow Validation Automation

## Overview

This UiPath automation reads cash flow records from an Excel file, validates financial data, calculates cash flow differences, handles invalid entries through exception handling, and updates the source workbook with processing results.

## Features

* Read cash flow data from Excel
* Validate Cash In values
* Validate Cash Out values
* Implement exception handling using Try-Catch
* Log validation errors
* Calculate cash flow differences
* Update processing status
* Write results back to Excel

## Technologies Used

* UiPath Studio 2024.10
* Excel Activities
* DataTables
* Exception Handling
* Logging Activities

## Process Flow

1. Read data from the Excel workbook.

2. Iterate through each record in the CashFlow sheet.

3. Validate the **Cash In** value.

4. Validate the **Cash Out** value.

5. Capture and log validation exceptions.

6. Calculate the difference:

   `Difference = Cash In - Cash Out`

7. Update the Status column based on validation results.

8. Write the updated data back to Excel.

## Sample Output

| Cash In | Cash Out | Difference | Status         |
| ------- | -------- | ---------- | -------------- |
| 5000    | 2000     | 3000       | Done           |
| 3k      | 1000     | -          | Cash In wrong  |
| 3000    | XYZ      | -          | Cash Out wrong |

## Skills Demonstrated

* Excel Automation
* Data Validation
* Exception Handling
* Logging and Monitoring
* DataTable Operations
* Financial Data Processing
* Business Rule Implementation


## Course Information

This project was developed as part of the UiPath Automation Developer Professional Training (v2024.10) program. The workflow demonstrates practical implementation of Excel automation, exception handling, and business-rule validation using UiPath.

## Author

Anousha
UiPath Developer | RPA Enthusiast
