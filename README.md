# Election_Analysis_Challenge

## Overview of Election Audit
The purpose of this challenge is to supply the election comission reults from the election including voter turnout for each county, percentage of votes from each county out of the total votes, and the county with the highest voter turnout. Using the election_results.csv file, we are to apply loops, conditional statements, and logical operators to discover the requested information. After finding the results, we are to print the results, and also save them to the election_results.txt file. 

## Election Audit Results
- 369,711 total votes were cast
- County Breakdown
  - Arapahoe County: 6.7%, (24,801)
  - Denver County: 82.8%, (306,055)
  - Jefferson County: 10.5%, (38,855)
- Denver County has the largest amount of votes
- Candidate Breakdown
  - Charles Casper Stockham: 23%, 85,213 votes
  - Diana DeGette: 73.8%, 272,892 votes
  - Raymon Anthony Doane: 3.1%, 11,606 votes
- Winner: Diana DeGette
  - 73.8%, 272,892 votes

## Summary
The core components of this script can be re-used for future elections. With a little code refactoring, the script can apply to different election scenarios. For example, parts of the code that calculates county votes originally came from the original script for calculating candidate votes. The variable names were changed to apply to county votes. Also, dictionairy keys and values can also be switched out. An important tool in this script are the loops for vote counting and printing portions, which can be applied to any election. 
