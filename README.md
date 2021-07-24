# Election Audit

## Overview of Election Audit
Tom, a Colorado Board of Elections employee, needs assitance to complete the election audit of a recent local congressional election.

### Purpose
We want to automate the process of generating a vote count report using Python, the vote count report should include below:

The total number of votes cast.

A list of counties that had a turnout.

The voter turnout for each county.

The percentage of votes each county cast.

The county with the highest turnout.

A list of candidates who recieved votes.

The total number of votes each candidate recieved.

The percentage of votes each candidate won.

The winner of the election based on popular vote.


## Election Audit Results

-There were 369,711 total votes cast in this congressional election.

-The county results for the precinct:
Jefferson cast 10.5% of the vote and 38,855 votes.
Denver cast 82.8% of the vote and 306,055 votes.
Arapahoe cast 6.7% of the vote and 24,801.

-Denver county had the largest number of votes.

-The candidate results were:
Charles Casper Stockham recieved 23.0% of the vote and 85,213 votes.
Diana DeGette recieved 73.8% of the vote and 272,892 votes.
Raymon Anthony Doane recieved 3.1% of the vote and 11,606 votes.

-The winner of the election was Diana DeGette, who recieved 73.8% of the vote and 272,892 votes.
See the output of the code below:
![Untitled](https://user-images.githubusercontent.com/38533045/126882462-8dce4aa0-9228-45d6-8436-a5d132b8b54e.png)

## Election Audit Summary
I propose that the election commission can use the PyPoll_Challenge.py script, with some modifications, for other elections. 
Currently, the program is written to analyze the election_results.csv file by iterating through each row and reading the data in the second and third columns, 'County' and 'Candidate', in order to calculate and print the results. There are many different ways in which this code can be altered and used with any election results.

For example, the program can be modified to determine which column to read data from by iterating through the header row. Then files with columns that are arranged in a different order will be analyzed accordingly. The programmer will also no longer have to inspect the data in order to ensure that script is reading the correct columns.
