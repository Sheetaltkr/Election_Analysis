# Election Analysis- 
## Overview of Election Audit: 
### Purpose
1) Provide **Colorado Board of Elections** below election **audit data** to help them analyze the congressional elections conducted in  **Jefferson**, **Denver** and **Arapahoe** counties with help from Tom and Seth.

-	Total votes for the election
-	Candidate names
-	Total votes for each candidate
-	Percentage of votes each candidate 
-	Winning candidate, vote count, and percentage
-	The voter turnout for each county
-	The percentage of votes from each county out of the total count
-	The county with the highest turnout


2) Provide a **written analysis** of the **election audit** results with your useful findings to the Election Commission.

## Resources
Data source: election_results.cvs

Software: Python 3.7, Visual Studio Code 1.59

## Election-Audit Python program

1) Source File: [election_results.csv](https://github.com/Sheetaltkr/Election_Analysis/blob/main/Resources/election_results.csv) 

2) Program output:[election_analysis.txt](https://github.com/Sheetaltkr/Election_Analysis/blob/main/analysis/election_analysis.txt)

3) Program code:[PyPoll_Challenge.py](https://github.com/Sheetaltkr/Election_Analysis/blob/main/PyPoll_Challenge.py)

#### Program Algorithm:

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

#### Command line Output:

![Command line output](https://github.com/Sheetaltkr/Election_Analysis/blob/main/analysis/Election_results_printed_to_commandLine.png)

#### Election analysis text file output:

![Election_analysis.txt](https://github.com/Sheetaltkr/Election_Analysis/blob/main/analysis/Election_results_saved_textfile.png)

## Election-Audit Results:
-	There were **369,711** votes cast in the election
-	The counties in the precinct were-
	-	Jefferson
	-	Denver
	-	Arapahoe
-	The county results were-
	-	Jefferson received **10.5%** of the votes and **38,855** number of votes
	-	Denver received **82.8%** of the votes and **306,055** number of votes
	-	Arapahoe received **6.7%** of the votes **24,801** number of votes
-	The County  with largest turnout: **Denver**
-	The candidates were-
	-	Charles Casper Stockham
	-	Diana DeGette
	-	Raymon Anthony Doane
-	The candidate results as were-
	-	Charles Casper Stockham received **23.0%** of the votes and **85,213** number of votes
	-	Diana DeGette received **73.8%** of the votes and **272,892** number of votes
	-	Raymon Anthony Doane received **3.1%** of the votes **11,606** number of votes
-	The winner of the election was **Diana DeGette** who received  **73.8%** of the votes and **272,892** number of votes


## Election-Audit Summary: 

#### Business proposal for Election Commission

- Federal, state, local and tribal elections
	- New functionality to count votes at state level by including additional source data columns like state,office, district,party, year of elections as required. This will provide the analysis for elections at  various levels.
	- Example 1: Add new dictionary to hold data for different states and its votes. One can calculate state vote percent and total state votes.
	- Example 2: Add new dictionary to hold data for different years. One can calculate yearly vote percent and total yearly votes.
- Graphs
	- Using `Matplotlib` library in python the script can be used to generate year-wise, state-wise, district-wise graphs. The graphs can be drawn for any dimensions and metrics like vote counts and vote percentage.
- Categorize Election results
	- Using conditional analysis the script can help determine if elections were successful or not using specific success criteria.
- Support multiple Data sources
	- The script can be modified to use various data source types like database, real-time feeds, JSON files etc.
