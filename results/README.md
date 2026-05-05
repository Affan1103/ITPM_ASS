# ITPM Assignment 1 – Option 2

## Project Overview

This project performs functional and usability testing on the website:
https://www.pixelssuite.com/

## Automation Testing

Automated using Playwright (Python) to verify preview functionality for PNG image conversion.

## How to Run

### 1. Install dependencies

pip install playwright openpyxl
python -m playwright install

### 2. Run the test

python image_preview_test.py --url "https://www.pixelssuite.com/convert-to-png" --slow-mo-ms 2000

## Output

* execution_results.csv (test results)
* results/preview_pass.png (screenshot proof)

## Manual Testing

36 test cases are included in the Excel file.

## Repository Contents

* Automation scripts
* CSV results
* Screenshot proof
* Manual test cases
