# Loan Qualifier Application

The purpose of this application is for the user to discover loans that they can qualify for and then be able to save the qualifying loans to a new CSV file.

The app will allow users to share their qualifying loans as a spreadsheet.

---

## Technologies

This project relies on Python and the modules; Sys, Fire, and Questionary. 

The app functions by: 

1. Load the latest Bank data
    bank_data = load_bank_data()

2. Get the applicant's information
    credit_score, debt, income, loan_amount, home_value = get_applicant_info()

3. Find qualifying loans

4. Saving the qualifying loans to a CSV file.

---

## Installation Guide

To install the loan qualifying app you will need to download the application from Github by navigating to the "Code" drop down and Downloading the zip file: https://github.com/SebSand/Sebastian_Module_2_Challenge. 


---

## Usage


1. The user should open their terminal and navigate to the downloaded folder containing the program.

2. Run `app.py` and when prompted, enter the file path to the CSV rate sheet containing the various banks loan qualifications:
    The entered code should look like: 

    
        Enter a file path to a rate-sheet (.csv): ./data/daily_rate_sheet.csv
        

3. The user will be prompted a series of questions regarding their financial information:
    * Their credit_score
    * Their monthly debt
    * Their monthly income
    * The desired loan amount 
    * The value of their home

    The app will calculate and return the users monthly debt to income ratio, the loan to value ratio and provide how many loans they qualify for.

4. The app will prompt the user to save the qualified loans into a file.

---

## Contributors

This app was developed by my coding bootcamp.


---

## License

Considering none of the source code is mine, do what you'd like with it.
