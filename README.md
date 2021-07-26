# election_analysis
Election analysis homework using Python

## Overview of Election Audit
Over the past week we've been helping Seth and Tom by creating a python program that could analyze election results to determine a winning candidate. However, the election comission is now requesting additional information about the participating counties to complete the audit.

### Purpose
The purpose of this analysis was to determine the total number of votes, votes for each county, percentage of votes for each county, percentage of votes for each candidate, and record the winner of the election.

## Election Audit-Results
From the analysis we created a text file with the following information regarding the results of the analysys:

- Total Votes: 369,711

### County Votes:
- Jefferson: 10.5% (38,855)
- Denver: 82.8% (306,055)
- Arapahoe: 6.7% (24,801)

- Largest County Turnout: Denver

### Candidate Votes:
- Charles Casper Stockham: 23.0% (85,213)
- Diana DeGette: 73.8% (272,892)
- Raymon Anthony Doane: 3.1% (11,606)

### Winning Votes:
- Winner: Diana DeGette
- Winning Vote Count: 272,892
- Winning Percentage: 73.8%

## Election Audit Summary
This script could easily be repurposed and used for another election. Almost all of the script could be applied to any similar election data. There are a couple of of items that would need to be checked though. First of all, the working directory and file locations would need to math the paths of 'file_to_load' and 'file_to_save' variables. If the CSV file is not in the proper location you would get an error message addressing this. You would also need to make sure that the 'county_name' and 'candidate_name' match the correct columns or you will recieve false results. 

However, the script should be scalable for any number of candidates or governing body. Counties could even be modified to states so long as the variables and column call outs match correctly.