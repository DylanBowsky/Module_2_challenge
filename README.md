## Module_2_challenge Testing and data application 

    This project focused on the ability to pull data from a csv file and make it interactive with a user.

## The goal for this application 
    We want it to be user friendly and interactive with the user and to show all of the loans they qualify for in one easy to read file.

## Technologies used

    In this project we used fire, csv, pathlib, run, and questionary.
    Also a testing enviroment was created to make sure the functions are working.

## Installation guide
    We will need to make sure fire and questionary are installed (Commonly used for install "Pip install fire/questionary")
    As well as make sure the correct imports are there pathlib and csv

## Example 

    Ask for the csv file we need (Daily_rate_sheet.csv)
    asks for credit score, debt, income, loan, and home value
    After the the data has been input it will use the filter functions created to generate a list of qualifying loans pulled from the daily rate sheet file
    this will then let the user determine if they will want to save it and save it as a csv file
    if they agree it will create a csv file of all qualified loans
    if they did not qualify at all it will exit the system and tell them to come back another time
