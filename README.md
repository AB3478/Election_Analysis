# Election_Analysis

## Project Overview
A Colorado Board of Elections employee has provided the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on the popular vote.

## Resources
- Data source: election_results.csv
- Software: Python 3.7.6., Visual Studio Code

## Analysis of the election determined that:
- There were 369,711 votes cast in the election.
- The candidates were:
   - Charles Casper Stockham
   - Diana DeGette
   - Raymon Anthony Doane
- The candidate results were: 
   - Charles Casper Stocham received 23% of the vote with 85,213 votes
   - Diana DeGette received 73% of the vote with 272,892 votes
   - Raymon Anthony Doane received 3% of the vote with 11,606 votes.
 - The winner of the election was:
   - Diana DeGette, who received 73% of the vote and 272,892 votes.
 
 ## Challenge Overview
 
 The election commission requested additional data to complete the audit:
 - The voter turnout for each county
 - The percentage of votes from each county out of the total count
 - The county with the highest turnout
 
 ## Challenge Summary
 
Out of the 369,711 total votes, Denver county had the largest vote total with 306,055 (82%) followed by Jefferson county with 38,855 votes (10.5%), and Arapahoe with 24,801 votes (6.7%). Diana DeGette won the election with 272,892 votes (73%).

![](https://github.com/AB3478/Election_Analysis/blob/main/Resources/Results.png)

In the future, we could expand the code to analyze the data from other election results. In addition to analyzing a congressional election, we could also examine local, state, and federal results. Several components  of the code would remain the same, such as county votes, candidate votes, and declaring a winner.
