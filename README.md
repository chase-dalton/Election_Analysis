# Election_Analysis
Analysis of Colorado election data with Python

## Project Overview
A Colorado Board of Elections employee has given me the following tasks to complete the election audit of a recent local congressional election:

  1. Calculate the total number of votes
  2. Get a complete list of counties that participated in the vote
  3. Calculate the total number of votes for each county
  4. Calculate the percentage of votes each county contributed 
  5. Get a complete list of candiates who received votes
  6. Calculate the total number of votes each candidate received
  7. Calculate the percentage of votes each candidate won
  8. Determine the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.8.8

## Results
The analysis showed that:
- There were 369,711 votes cast.
- The counties in the precinct that participated were:
    - Jefferson County, with 38,855 votes (10.5%),
    - Denver County, with 306,055 votes (82.8%), and
    - Arapahoe County, with 24,801 votes (6.7%)

- Denver County had the largest number of votes in this election.

- The candidates were:
  - Charles Casper Stockham, who received 23.0% of the vote with 85,213 votes,
  - Diana Degette, who received 73.8% of the vote with 272,892 votes, and
  - Raymon Anthony Doane, who received 3.1% of the vote with 11,606 votes 

- The winner of this election was Diana Degette with 272,892 (73.8%) of the vote.

The Python script not only prints the results in the terminal, as shown below, but the results are also published to a [text file](https://github.com/typicalchazz/Election_Analysis/blob/main/analysis/election_results.txt) as well.  

![terminal image](https://github.com/typicalchazz/Election_Analysis/blob/main/Resources/Election_Analysis_Terminal_Output.png)

## Summary
Using Python, we were able to assist the election commision answer their question of which counties participated in voting, and which candidate won the election. The Python script is incredibly flexible and modifications can be made to improve it and make it accessible for any election. A great feature that would not only be easy to add, but would be very likely asked for, would be to get the breakdown of the counties vote by candidate. That way the commision would not only see what counties participated, but what candidate did they vote for. Another great feature would be to change the scope of the script and see how various cities voted for their candidates as opposed to counties. The script could even be used in state elections.