# Loan Qualifier Program

This project is to develop a Python application that will perform calculations to determine a User's qualificions to specific lender criteria. It incorporates modularized software design. The result of the calculations determines the numbers of lenders available that meet the User's qualifications. Lender data is provided in the '''daily_rate_sheet''' csv file. User provides specific variables as inputs. Then, the application performs the operations to calculate ratios, filter lender rates, save csv file of available lenders and print results .

---

## Technologies

This application is developed on the Python 3.7.11 version. It incorportates the following required dependancies to run. This dependancies include the following Imports:

1. Sys = 
2. CSV  = To import csv file to read and write qualified loans.
3. Pathlib = To load and save files from and to paths.
4. Fire = To engage CLI, help page and entrypoint.
5. Questionary = To interact with User by asking questions to input variables and yes/no.

---

## Installation Guide

The following PIP installation must be performed before running the program. They include:

pip install pathlib
pip install fire
pip install questionary


---

## Usage

To run this application, create a clone on the local desktop. Then, within the folder where program is located, enter the following in the CLI:

'''python app.py'''

This will initialize the application and prompt for location of the '''daily_rate_sheet'''. Enter the relative or absolute path to this file and press enter. 

Then, the User will be asked to input these variables: credit score, monthly income, monthly debt, desired loan amount and value of home.

After these variable inputs are entered, the application will calculate the debt-to-income and loan-to-value ratio. It will also filter the banks criteria and return available loans that qualify.

The image below illustrates the results:




This section should include screenshots, code blocks, or animations explaining how to use your project.

---

## Contributors

Contributor: John Batarse  
Email: jbatarse@hotmail.com
LinkedIn: https://www.linkedin.com/in/john-a-batarse-760a26116/
---

## License

Trilogy Education, LLC / UC Berkeley
