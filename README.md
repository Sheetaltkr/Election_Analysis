#Election Analysis- 
#
##Overview of Election Audit: 

###Purpose
1) To provide **Colorado Board of Elections** below election **audit data** to help them analyze the congressional elections conducted in  **Jefferson**, **Denver** and **Arapahoe** counties with help from Tom and Seth.

-	Total votes for the election
-	Candidate names
-	Total votes for each candidate
-	Percentage of votes each candidate 
-	Winning candidate, vote count, and percentage
-	The voter turnout for each county
-	The percentage of votes from each county out of the total count
-	The county with the highest turnout


2) Provide a **written analysis** of the **election audit** results with your useful findings to the Election Commission.

##Resources
Data source: election_results.cvs

Software: Python 3.7, Visual Studio Code 1.59

##Election-Audit Python program

1) Source File: [election_results.csv](https://github.com/Sheetaltkr/Election_Analysis/blob/main/Resources/election_results.csv) 

2) Program output:[election_analysis.txt](https://github.com/Sheetaltkr/Election_Analysis/blob/main/analysis/election_analysis.txt)

3) Program code:[PyPoll_Challenge.py](https://github.com/Sheetaltkr/Election_Analysis/blob/main/PyPoll_Challenge.py)

####Program Algorithm:

1. Set the source file path for election_results.csv

2. Set the output file path for election_analysis.txt 

3. Initialize `int`, `string`, `list` and `dictionary` variables to store

	-	candidate names
	-	candidate votes
	-	candidate vote
	-	percentage
	-	winning candidate
	-	winning vote count
	-	winning vote percentage
	-	count names
	-	county votes
	-	county vote percentage
	-	count with largest turnover
	
4. Open source file for reading data

5. Using `For` loop and `If` conditional and `Not in` membership operators for every row in the source file 
 
	-	Count total votes 
	-	Read candidate name from third column
	-	Count votes for each candidate
	-	Read county name from second column
	-	Count votes for each county

6. Open output file for writing audit data from step 5
7. Print total vote count to terminal
8. Write total vote count to output file
9. Using `For` loop retrieve county name, county votes and calculate county vote percentage
10. Print the county results to the terminal
11. Write county results to output file
12. Determine county with the largest turnout and its vote count
13. Print the county with the largest turnout to the terminal
14. Write the county with the largest turnout to a text file
15. Using `For` loop retrieve candidate name, candidate votes and calculate candidate vote percentage
16. Print the candidate results to the terminal
11. Write candidate results to output file
12. Determine the winning candidate, its vote count and vote percentage
13. Print the winning candidate results to the terminal
11. Write winning candidate results to output file

####Command line Output:

![Command line output](https://github.com/Sheetaltkr/Election_Analysis/blob/main/analysis/Election_results_printed_to_commandLine.png)

####Election analysis text file output:

![Election_analysis.txt](https://github.com/Sheetaltkr/Election_Analysis/blob/main/analysis/Election_results_saved_textfile.png)

##Election-Audit Results:
Using a bulleted list, address the following election outcomes. Use images or examples of your code as support where necessary.

####How many votes were cast in this congressional election?
Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.

####Which county had the largest number of votes?
Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.

####Which candidate won the election, what was their vote count, and what was their percentage of the total votes?


##Election-Audit Summary: 

In a summary statement, provide a business proposal to the election commission on how this script can be used—with some modifications—for any election. 

two examples of how this script can be modified to be used for other elections.
