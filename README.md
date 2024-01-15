# Python API Automation Framework

Hybride Custom Framework to Test the REST APIs


### Tech Stack
1. Python 3.11
2. Requests - HTTP Framework
3. Pytest - Testing Framework
4. Reporting - Allure Report, Pytest HTML
5. Test Data - CSV, Excel, JSON
6. Parallel Execution - x distribute



### How to Install Packages
'' pip install requests pytest pytest-html faker allure-pytest jsonschema ''


### To Freeze your Package version
'' pip freeze > requirements.txt ''

## To install te Freeze version 
'' pip install -r requirements.txt ''

## How to run your Testcase Parallel ##
'' pip install pytest-xdist ''
'' pytest -n auto test/integration_test/test_create_booking.py -s -v ''

## To work with the Excel ##
'' pip install openpyxl ''

## To work with JSON Schema ##
'' pip install jsonschema ''