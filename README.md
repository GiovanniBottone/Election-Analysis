# Election-Analysis

## Overview of Election Audit:
The purpose of this election audit analysis was to assist a Colorade Board of Elections employee with completing the below tasks for a recent local congressional election. 

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.10, Visual Studio Code 1.63.2

## Election-Audit Results:
See election results below

![Election Results](https://user-images.githubusercontent.com/95371617/149605550-584d878c-7df1-458b-a6a1-f648f87114db.png)

The analysis of the election shows that:
- There were 369,711 votes cast in the election.
  - Jefferson County: 10.5% of votes (38,855 votes)
  - Denver County: 82.8% of votes (306,055 votes)
  - Arapahoe County: 6.7% of votes (24,801 votes)
  
- Denver county had the largest number of votes (306,055), Jefferson County had the second most votes (38,855) and Arapahoe County had the smallest number of votes (24,801)

- The candidates were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
  
- The candidates results were:
  - Charles Casper Stockham received 23.0% of the total vote (85,213 votes)
  - Diana DeGette received 73.8% of the total vote (272,892 votes)
  - Raymon Anthony Doane received 3.1% of the total vote (11,606 votes)

- The winner of the election was:
  - Diana DeGette, who received 73.8% of the vote with 272,892 votes.

## Election-Audit Summary
Two additional ways this script can be used by the election comission are to find the largest number of votes by modifying the requirements from candidate or county, and to determine grographic preference for the requirements. The first use, to find the largest number of votes with different requirements other than candidate or county can be used by swapping candidate or county out for almost anything. For example, swapping candidate and county out for political party and township would allow the election commission to have a better understanding of each townships political party preference. By focusing on the political party preference of each township, the election comission should have a clear understanding of how townships will vote in future elections, which creates a clearer understanding of how counties will vote when the townships have been combined. 

The second way this script can be used, determining georgraphic preferences, can give the election comission a voting result based on percentages rather than total votes. By testing for the percentage of county voters rather than the total amount of county voters, all counties have equal voting power rather than a larger county having greater voting power due to its larger population. Once the counties are considered equal, the election comission could test for the percentage of voters each candidate received in each county, showing which candidate was the most popular within that county. After all the counties have been tested, the election comission will have a clear understanding of which candidate is the most popular in each individual county as well which is the most popular across all counties.  
