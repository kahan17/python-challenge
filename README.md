# Python Financial and Election Data Analysis

This repository contains two Python-based data analysis projects: **PyBank** and **PyPoll**. Each project focuses on analyzing large datasets efficiently to provide meaningful insights.

---

## PyBank: Financial Analysis
### Overview
The **PyBank** project involves analyzing financial data from a company's dataset to generate insights on monthly profits and losses. The analysis calculates total months, net profit/loss, average change, and identifies the periods of greatest increase and decrease in profits.

### Dataset
- File: `budget_data.csv`
- Columns: `Date`, `Profit/Losses`

### Analysis Goals
1. Calculate the total number of months included in the dataset.
2. Compute the net total amount of "Profit/Losses" over the entire period.
3. Determine changes in "Profit/Losses" over the period and calculate the average of those changes.
4. Identify the greatest increase and decrease in profits (date and amount).

### Results
- **Total Months:** 86
- **Total Profit/Losses:** $22,564,198
- **Average Change:** $-8311.11
- **Greatest Increase:** Aug-16 ($1,862,002)
- **Greatest Decrease:** Feb-14 ($-1,825,558)

---

## PyPoll: Election Results Analysis
### Overview
The **PyPoll** project is designed to analyze election data and determine the outcome of a vote. The program calculates total votes, vote distribution, and identifies the winner based on popular vote.

### Dataset
- File: `election_data.csv`
- Columns: `Voter ID`, `County`, `Candidate`

### Analysis Goals
1. Calculate the total number of votes cast.
2. Generate a list of candidates who received votes.
3. Determine the percentage and total votes each candidate received.
4. Identify the winner of the election based on the highest vote count.

### Results
- **Total Votes:** 369,711
- **Candidates and Results:**
  - Charles Casper Stockham: 23.049% (85,213 votes)
  - Diana DeGette: 73.812% (272,892 votes)
  - Raymon Anthony Doane: 3.139% (11,606 votes)
- **Winner:** Diana DeGette

---

## Methodology
Both projects are implemented in Python using efficient data processing techniques. Key Python libraries and tools include:
- **CSV:** For reading input data files.
- **OS:** For file path management.
- **Python Logic:** To compute required metrics and handle file output.

### Project Outputs
Each script generates a detailed analysis:
1. **Terminal Output:** Results are displayed in the terminal.
2. **Text File Output:** Results are written to `budget_analysis.txt` (PyBank) and `election_analysis.txt` (PyPoll).

---

## Repository Structure
