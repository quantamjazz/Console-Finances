# Financial Analysis Project
This project is a financial analysis tool that processes a dataset of monthly profit/losses over a period of time. The dataset used is an array of arrays.
<img width="951" alt="Screenshot 2023-12-12 at 21 10 48" src="https://github.com/quantamjazz/Console-Finances/assets/148623614/8b8a639b-cf1f-4692-ae00-588441985369">

# Features
The tool calculates and outputs the following:

Total Months: The total number of months included in the dataset.
Total Profit/Losses: The net total amount of profit/losses over the entire period.
Average Change: The average change in profit/losses between months over the entire period.
Greatest Increase in Profits: The greatest increase in profits (date and amount) over the entire period.
Greatest Decrease in Losses: The greatest decrease in losses (date and amount) over the entire period.

# How It Works
The tool uses a for loop to iterate through each month's data in the finances array. For each month, it adds the profit/loss to a total, calculates the change from the previous month, and keeps track of the greatest increase and decrease it has seen so far.

After going through all the months, it calculates the average change in profit/losses, and then prints out all the results.

# Usage
Open the console to view the results from the tool.

# Requirements
This project requires a JavaScript environment to run.

# Contributing
Contributions are welcome.

# License
MIT License.
