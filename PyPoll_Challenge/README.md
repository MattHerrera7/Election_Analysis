# Election_Analysis
#Python_Election_Analysis
Analysis of election results using python to read in a csv file and provide the folowing deliverables:
1. The Election Results Printed to the Command Line
2. The Election Results Saved to a Text File 
3. A Written Analysis of the Election Audit


## Overview of Elecyion Audit:
 The Colrado Board of Elections has requested an audit of a recent local election with the following specified "asks":
 * Total number of votes cast
 * A complete list of candidateds who recieved votes
 * Total number of votes each candidated recieved
 * Percentage of votes each candidate won
 * The winner of the elction based on popular vote
 
 The  Election commission has requested some additional data to complete the audit:

    The voter turnout for each county
    The percentage of votes from each county out of the total count
    The county with the highest turnout

The results are expected to be provided ( to the terminal and in a text file) using the following template:

![Expected Output] (./ C:\Users\matth\Documents\Data analytics\UCF\Module 3\Election Results\Election_Analysis\PyPoll_Challenge\Images\Final_Results.png)
# Resources
* Data Source: elecion_results.csv
* Software: Python 3.7.6, Visual Studio Code 1.61.2

## Election-Audit Results:
Guidance: Using a bulleted list, address the following election outcomes. Use images or examples of Python code as support where necessry.

## Specified "Asks":
 * How many votes were cast in this election?
    -Total_Votes: 369,711
* A complete list of candidates who recieved votes 
* Total number of votes each candidated recieved
    -Charles Casper Stockham: 23.0% (85,213)
    -Diana DeGette: 73.8% (272,892)
    -Raymon Anthony Doane: 3.1% (11,606)
* Percentage of votes each candidate won
## Results as recorded in my election_analysis.txt file
![my analysis](./Images/Final_Results.png)

## Election-Audit Python Code Summary
The python code provided is "robust" and can be used for any state wide clection given the following:
1. need a seperate csv file for each election
2. need a seperate election analysis txt file to record results 
3. the code does not "hard wire " candidates or counties and can therefore be used or any state wide election