# Election_Analysis

### Overview of Election Audit:

The purpose of this election audit analysis was to automate the task of counting all the rows in the election_results.csv file and determine the winner of this election based on the majority of the votes earned. 

secondary purpose of this audit was to also analyze each county and to determine which county brought in what number of votes.


### Election-Audit Results:

The results of the election can be found at the link below:

https://github.com/kbehyar/Election_Analysis/blob/main/analysis/election_results.txt

Based on on the audit, these were the results:

A total of 369,711 votes were cast during this election in 3 different counties. The Denver county had the majority of the votes. and the winner of this election was Diana DeGette who received 272,892 total votes which was 73.8% of the overall votes cast. Below is the breakdown of all the votes based on county and candidates:

County Votes:
- Jefferson: 10.5% (38,855)
- Denver: 82.8% (306,055)
- Arapahoe: 6.7% (24,801)

Candidate votes:
- Charles Casper Stockham: 23.0% (85,213)
- Diana DeGette: 73.8% (272,892)
- Raymon Anthony Doane: 3.1% (11,606)


### Election-Audit Summary:

The script to this automation for this audit can be found at the link below:

https://github.com/kbehyar/Election_Analysis/blob/main/PyPoll_Challenge.py

This script can be used to determine the winners of any elections. Some modifications that need to be made to this script in order for it to determine the results of any election are:

- If a new CSV file is used with more data is used to analysis, the code needs to be adjusted as to which columns hold which information. for exmaple: Gender of candidates can be row[1], Ethnicity = row [3].
- This code can also be adjusted to determine in which counties did each of the candidates received the most votes to determine in which places were each of the candidates more popular 
- 
