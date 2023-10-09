# Budget-Tracker
Developed a budget tracker via Python and Jupyter Notebook that imports a dictionary as an editable CSV file.

### Problem Statement
Your family member wants to enter the 21st century and track their budget using a Python application that stores data in a .csv file. 

### Deliverables
A Python application that accepts user input to interact with users.

## Technical Acceptance Criteria:
User Stories
- When I start up the application, I am given the following options:
    - Add a new entry to the budget tracker
    - Display the total account balance
    - View all previous entries
- If I choose to add a new entry, I am asked to provide:
    - A title describing the budget item
    - Whether the budget item is Income or Expense
    - The total amount of the budget item
    - The date of the transaction in "MM-DD-YYYY" string format
- If I choose to display the total account balance:
    - The program adds all income and subtracts all expense items to display the net balance
- If I choose to view all previous entries:
    - The program prints all details of all previous entries in a human-readable format

### Technical Requirements:
- Stores all entries in a .csv file
- Load the previously created entries when the user initializes the application

## Getting Started

These instructions will give you a copy of the project up and running on
your local machine for development and testing purposes. 

### Prerequisites

Requirements for the software and other tools to build, test and push 
- [Python](https://www.python.org/)
- An open-source code editor such as [Jupyter Notebook](https://jupyter.org/)

### Installing

A step-by-step series of examples that tell you how to get a development
environment running

1. Download and open your open-source code editor. 

2. Download John Bacolores_budget_app.ipynb file.

3. Upload John Bacolores_budget_app.ipynb file.

## Running the tests

Run all cells. Awaiting user commands in the final cell of the notebook. 

### Sample Tests

How to add a transaction: Press [a] to add a transaction

    [a] then "Enter"

Input the title of the transaction:

    Check from brother

What is the category:

    income or expense

Enter the amount:

    500

Input the date in mm/dd/yyyy format:

    08/29/2023

Returns to user input: 

    Press [a] to add a transaction, [b] to view the account balance, [v] to view all transactions, or [q] to quit.

## Deployment

N/A - can launch via Jupyter Notebook

### Post-MVP Goals:
- The program allows you to track multiple accounts
- The program can analyze profit and loss for a specific month or year
- The program can provide high-level stats, such as average transaction size
- The program can track and analyze transactions by specific customers or vendors

## Built With

  - [Contributor Covenant](https://www.contributor-covenant.org/) - Used
    for the Code of Conduct
  - [Creative Commons](https://creativecommons.org/) - Used to choose
    the license

## Authors

- **Billie Thompson** - *Provided README Template* -
    [PurpleBooth](https://github.com/PurpleBooth)

## Acknowledgments

- Hat tip to anyone whose code is used
- **Paula Bannerman** - *Provided guidance and oversight* - [dcartist](https://github.com/dcartist)
- **Andrew Riddle** - *Provided guidance and oversight* - [ajriddle](https://github.com/ajriddle)
