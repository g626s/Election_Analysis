# Election_Analysis

# Written Analysis of the Election Audit 

# Resources
- Data Source: election_results.csv
- Software: Python 3.6.1, Visual Studio Code, 1.38.1

# Overview of Election-Audit 
In this election audit project, we assisted our client Tom who is a Colorado Board of Elections employee that has given us the the following task to complete the election audit of the tabulated results for U.S. Congressional precinct in Colorado. In our previous collaboration with our client Tom, in the "PyPoll.py" file, we were tasked with reporting the total number of votes cast, the total number of votes for each candidate, the percentage of votes for each candidate, and the winner of the election election based on the popular vote. This task was used with the programming language Python at the request of our client's manager and since the project's code was done successfully, the code can be used to audit not only other congressional disctricts but also senatorial districts and local elections. There were three primary voting methods that we and our client took into account: Mail-in ballots, punch cards, and direct recording electronics or DRE counting machines. Altogether the vote casts by these three methods will determine the final election results. At the request of the election commission after we submitted the previous election audit results, we added some additional data in this election analysis project which are: the voter turnout for each county, the percentage of votes from each county out of the total count, and the county with the highest turnout. Working from the project's election_results.csv file, we used for loops and conditional statements with membership and logical operators to find the requested results. Then, we printed the results to the command line and saved them to the project's election_results.txt file.

# Election-Audit Result
In this Election-Audit project, we answered the following: 

- How many votes were cast in this congressional election?
    - Total Votes: 369,711

Logical operator used to obtain total votes:


![Screen Shot 2022-07-08 at 8 48 03 PM](https://user-images.githubusercontent.com/107281474/178114408-2b8dfb17-611a-47aa-8bd0-8efed56a9fdc.png)

- Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
    - County Votes:
    - Jefferson: 10.5% (38,855)
    - Denver: 82.8% (306,055)
    - Arapahoe: 6.7% (24,801)

For Loop used to obtain a breakdown of the number of votes and the percentage of total votes for each county in the precinct:


![Screen Shot 2022-07-09 at 9 30 00 AM](https://user-images.githubusercontent.com/107281474/178114603-4fbc5074-f0a2-4d80-a258-109531046389.png)

- Which county had the largest number of votes?
    - Largest County Turnout: Denver 

If Statement used to determine the county with the largest number of votes:


![Screen Shot 2022-07-08 at 8 47 04 PM](https://user-images.githubusercontent.com/107281474/178114724-40b147ea-72c9-40bf-aa08-2e80d3815c70.png)


- Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
    - Charles Casper Stockham: 23.0% (85,213)
    - Diana DeGette: 73.8% (272,892)
    - Raymon Anthony Doane: 3.1% (11,606)

- Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
    - Winner: Diana DeGette
    - Winning Vote Count: 272,892
    - Winning Percentage: 73.8%

# Election-Audit Summary 
For the election commission, from the analysis and information in the project, we propose that this script can be used for local to even senatorial elelections with some slight modifications based on the electorial rules and regulations as well as information gathered and methods of obtaining data. The electorial commission can modify this script based on the data source and candidate information.
