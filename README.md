# Election Audit

## Overview of Election Audit

The purpose of this election audit is to assist the election commission with determining the results of the congressional election. The election commission has requested the following information:
- The voter turnout for each county
- The percentage of votes from each county out of the total count
- The county with the highest vote turnout
- The number of votes each candidate received
- The percentage of votes each candidate received out of the total number
- The winning candidate, meaning the candidate who received the highest number of votes
  - How many votes the winning candidate received
  - The percentage of votes the winning candidate received out of the total votes cast

## Election Audit Results
- There were 369,711 votes cast in this congressional election.
- The number of votes and the percentage of total votes for each county was as follows:
  - Arapahoe County had 24,801 votes, which was 6.7% of the total votes cast.
  - Denver County had 306,055 votes, which was 82.8% of the total votes cast.
  - Jefferson County had 38,855 votes, which was 10.5% of the toal votes cast.
- Denver County had the largest number of votes cast.
- The number of votes and the percentage of total votes for each candidate was as follows:
  - Charles Casper Stockham received 85,213 votes, which was 23.0% of the total votes cast.
  - Diana DeGette received 272,892 votes, which was 73.8% of the total votes cast.
  - Raymon Anthony Doane received 11,606 votes, which was 3.1% of the total votes cast.
- The candidate Diana DeGette won the election. She received 272,892 votes, which was 73.8% of the total votes cast.

<img width="303" alt="Election Results Text File" src="https://user-images.githubusercontent.com/88804543/132064522-0de559de-87f3-4c44-9af8-319f2e9a8995.png">

## Election Audit Summary

In a summary statement, provide a business proposal to the election commission on how this script can be used, with some modifications, for any election. Give at least 2 examples of how this script can be modified to be used for other elections.

This script can be used to analyze the voting data from other elections. We can modify the input file, the file which will be read by our script. This script will then analyze the csv file which we designate.

<img width="495" alt="File to Load" src="https://user-images.githubusercontent.com/88804543/132064886-e8f3596f-88cc-4d32-adc7-42e92410f0f7.png">

For the file_to_load variable, we can select a new file and it's location, which would replace the '("Resources", "election_results.csv")' in the code example above. We can also save the new results to a different path by modifying the file_to_save variable. We could create a new text file to write the results to; so we would replace where it says '("analysis", "election_analysis.txt")' in the example code above.
