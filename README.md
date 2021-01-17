# Analysis of the Election Audit

## Overview of Election Audit

The purpose of this Election Audit Analysis was to provide the additional information requested by The Election Commission of the Colorado Board of Elections, such as the voter turnout for each county, the percentage of votes from each county out of the total county and the county with the highest turnout.
Also, we want to explain the methodology used during the analysis to help the audience understand our process and give them an insight into what they can do with the data presented. 
The following resources were used to complete this analysis:
- Data source: Election _results.csv
- Software: Python Version 3.9.1
- Software: Visual Code Version 1.52.1 

## Election-Audit Results 
- How many votes were cast in this congressional election?
In this congressional election, a total of 369,711 votes were cast. (See picture 1)

    Picture 1 - General Election results saved on Election_results (txt file)
    
    ![](https://github.com/Marietas/Mod3-Election-Analysis/blob/main/Resources/Election_results.PNG)
    
- Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
 
The total County Votes and their percentage are the following:

--Jefferson: 10.5% (38,855)
--Denver: 82.8% (306,055)
--Arapahoe: 6.7% (24,801)

- Which county had the largest number of votes?

The largest county was Denver with 306,055 votes

- Provide a breakdown of the number of votes and the percentage of the total votes each candidate received

The candidate results are the following:
•	Charles Casper Stockham received 23% of the total of 85,213 votes.
•	Diana DeGette received 82.8% of the total of 272,892 votes.
•	Raymon Anthony Doane received 3.1% of the total of 11,606 votes.
 
TOTAL NUMBER OF VOTES = 369,711

- Which candidate won the election, what was their vote count, and what was their percentage of the total votes?

Candidate Diana DeGette. She received 82.8% of the total votes; this percentage represents a total of 272,892 votes

### Picture 2

To get to the results in figure one, the code below was developed.
The county list and county votes dictionary are listed in lines 21 and 22, respectively.

   Picture 2 - VS code print screen
    
    
   ![](https://github.com/Marietas/Mod3-Election-Analysis/blob/main/Resources/VS_code_page1.PNG)
    


Add Pic2 

### Picture 3

Add Pic3
The total vote code developed to print the results to the terminal can be seen in picture 3, from line 85 to line 91.


The county with the largest number of voters is printed to the terminal throughout the following code sequence (line 113 to 118):


The code developed to present the winner of the election, winning vote count, and winning percentage of votes and save these data in txt file  are shown in the picture below Lines (145 to 154) 

## Election-Audit Summary:

We can modify this script by applying different variables in alignment with additional questions or other data set.
•	Smallest county turnout

Also, this script can be used in any kind/size of election, as the script is open without any restrictions on the number of records that can identify.
•	Add or replace county by the state to use it on the Presidential Elections
•	Add or replace county by Country to use it on Brexit election.


