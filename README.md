# election_analysis

## Project Overview
A Colorado Board of Elections employee has given me the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of counties where votes were cast.
3. Calculate the total number of votes cast in each county.
4. Calculate the percentage of votes cast in each county.
5. Determine which county had the largest voter turnout.
6. Get a complete list of candidates who received votes.
7. Calculate the total number of votes each candidate received.
8. Calculate the percentage of votes each candidate won.
9. Determine the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.9.1, Visual Studio Code 1.52

## Election-Audit Results
The analysis of the election shows that:
- There were 369,711 votes cast in the election.
- The county results were:
	-  10.5% of the votes, or 38,855 votes, were cast in Jefferson County.
	-  82.8% of the votes, or 306,055 votes, were cast in Denver County.
	-  6.7% of the votes, or 24,801 votes, were cast in Arapahoe County.
- Denver County had the largest number of votes.
- The candidate results were:
  - Charles Casper Stockham received 23.0% of the vote and 85,213 votes.
  - Diana DeGette received 73.8% of the vote and 272,892 votes.
  - Raymon Anthony Doane received 3.1% of the vote and 11,606 votes.
- The winner of the election was:
  - Diana DeGette, who received 73.8% of the vote and 272,892 votes.
  
## Election-Audit Summary
This script can be easily modified to report results for future elections. If you have a different file that contains the election results, you can change the "file_to_load" to point to the updated file by just confirming the path and updating the file name. Depending on the data you are starting with, you can also update the script to look at votes by city, state, gender, etc., instead of county. You would follow the same pattern in the script that we used to calculate the county data, but update it to refer to whatever category you are looking at (i.e., gender).