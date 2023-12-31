# PyBank and PyPoll

* PyBank: Analysis of monthly Profit/Loss data
* PyPoll: Analysis of election result

## Background

In this work, I have created Python scripts for analyzing the financial records of PyBank and the election result of PyPoll.


## PyBank

![Revenue](Images/revenue-per-lead.png)

* In this work, I have created a Python script for analyzing the financial records of PyBank. With a set of financial data called [budget_data.csv](PyBank/Resources/budget_data.csv), the dataset comprises two columns: `Date` and `Profit/Losses.` 

* Create a Python script that analyzes the records to calculate each of the following:

  * The total number of months included in the dataset

  * The net total amount of "Profit/Losses" over the entire period

  * The average of the changes in "Profit/Losses" over the entire period

  * The greatest increase in profits (date and amount) over the entire period

  * The greatest decrease in losses (date and amount) over the entire period

  [Financial_Analysis](https://github.com/RGK73/python-challenge/tree/main/PyBank/analysis/budget_data.txt)

  ```text
  Financial Analysis
  ----------------------------
  Total Months: 86
  Total: $22564198
  Average  Change: $-8311.11
  Greatest Increase in Profits: Aug-16 ($1862002)
  Greatest Decrease in Profits: Feb-14 ($-1825558)
  ```


## PyPoll

![Vote_Counting](Images/Vote_counting.png)

* In this work, I have created a Python script for analyzing the votes of election results of PyPoll.

* With a set of poll data called [election_data.csv](PyPoll/Resources/election_data.csv), the dataset comprises three columns: `Voter ID,` `County,` and `Candidate.` 

* Create a Python script that analyzes the votes and calculates each of the following:

  * The total number of votes cast

  * A complete list of candidates who received votes

  * The percentage of votes each candidate won

  * The total number of votes each candidate won

  * The winner of the election based on popular vote.

 [Election_Results](https://github.com/RGK73/python-challenge/blob/main/PyPoll/analysis/election_analysis.txt)

  ```text
  Election Results
-------------------------
Total Votes: 369711
-------------------------
Charles Casper Stockham: 23.049% (85213)
Diana DeGette: 73.812% (272892)
Raymon Anthony Doane: 3.139% (11606)
-------------------------
Winner: Diana DeGette
-------------------------
```
