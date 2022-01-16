### Loan Qualifier Calculations

This program is to develop a **Python** application that will perform calculations to determine a User's qualificions to specific lenders criteria. It incorporates modularized software design. The result of the calculations determines the numbers of lenders available that meet the User's qualifications. Lenders data is provided in the ```daily_rate_sheet.csv``` file. User provide specific variables as inputs. Then, the application performs the operations to calculate ratios, filter lender rates, save csv file of available lenders and prints results .

---

## Technologies

This application is developed on the **Python** *3.7.11 version*. It incorportates the following required 5 dependancies to run. These dependancies include the following Imports:

1. **Sys** = To provide access to functions that interacti with this application.
2. **CSV**  = To import csv file to read and write qualified loans.
3. **Pathlib** = To load and save files from and to paths.
4. **Fire** = To engage CLI, help page and entrypoint.
5. **Questionary** = To interact with User by asking questions to input variables and yes/no.

---

## Installation Guide

The following PIP installation must be performed before running the program. They include:

```pip install pathlib```

```pip install fire```

```pip install questionary```


---

## Usage

To run this application, create a clone on the local desktop. Then, within the folder where program is located, enter the following in the CLI:

```python app.py```

This will initialize the application and prompt for location of the ```daily_rate_sheet.csv```. Enter the relative path (```./data/daily_rate_sheet.csv```) or absolute path to this file and press enter. 

Then, the User will be asked to input these 5 variables: credit score, monthly debt, monthly income, desired loan amount and value of home.

After these variable inputs are entered, the application will calculate the debt-to-income and loan-to-value ratio. It will also filter the banks criteria and return the available loans that qualify.

The image below illustrates the results:

![<ScreenShot>](<Python app.py Screen Shot .png>))

In the example above, the User's inputs are: credit score = 725, monthly debt = 10000, monthly income = 50000, loan amount = 250000 and home value = 1000000. The application calculated the DTI ratio = 0.20, LTV rato = 0.25 and found 5 qualifying loans. User enters 'Y' to save file and names the file. Qualifying loans is saved as "Loans Qualified".

---

## Contributors

Contributor: John Batarse  

Email: jbatarse@hotmail.com

LinkedIn: (["Find me on LinkedIn"](<https://www.linkedin.com/in/john-a-batarse-760a26116/>))


## License

Trilogy Education, LLC / UC Berkeley
