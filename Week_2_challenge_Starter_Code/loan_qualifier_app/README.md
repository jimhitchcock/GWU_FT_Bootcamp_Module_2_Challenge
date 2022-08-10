# Loan Qualifier Application

**Welcome to my repository for the Loan Qualifier App.  Please explore the codebase!**
>"...making finding loans easy!"

The loan qualifier app will allow the user to easily filter and return only the loans that the user qualifies.  No more searching through endless spreadsheets of lenders and manually matching their quidelines to your qualifications.  Just load the path for your daily rate sheet and when prompted, you can choose to save your list of loans your qualify in the qualifying_loans.csv file for future reference.

---

## Technologies

This app was written with [Python 3.7.13](https://www.python.org/downloads/release/python-3713/)

Command Line Interface ussing the: 

[Fire library](https://pypi.org/project/fire/)

[Questionary Library](https://pypi.org/project/questionary/)

---

## Installation Guide

Before running the application first install the following dependencies. 

```python
    pip install fire
    pip install questionary
```

---

## Usage

To use the Loan Qualifier App simply use the daily_rate_sheet.csv to load the list of lenders.
Then answer some basic qualification questions about your credit score, debt, income, loan amout requested and home value.
You then will have an option to save your list of loans that meet your qualifications to a qualified_loans.csv file.

---

## Contributors

Parts of this application were written by Jim Hitchcock, starter code provided by GWU FinTech Bootcamp.
Further review and debugging provided by AskBCS help desk.

---

## License

MIT License
