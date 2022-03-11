# Election Analysis
---
## Overview of Election Audit
---
### Purpose:

A Colorado Board of Elections employee, Tom, has tasked us to assist in completing an election audit for a congressional precinct by reporting:
  
  * Total number of votes cast. 
  * Total number of votes for each candidate. 
  * Percentage of votes for each candidate. 
  * The winner of the election based on the popular vote.

Rather than analyzing and confirming the congressional precinct voting data in excel, we have been tasked with automating the process of generating audit results by writing and running Python programming script. After successfully running our Python code in order to determine the desired outputs and submitting the election results to the election commission, we have been tasked with submitting additional data to complete the audit. The election commission is interested in voter turnout for the congressional precinct and has requested that we report:
	
  * Voter turnout for each county
	* Percentage of votes from each county out of the total count.
	* The county with the highest turnout.

In order to so, we went through our previous Python programming script and added new code that will find the requested voter turnout results and aggregate it to the previous election results file that we submitted to the election commission. 

---
## Analysis
---
### Election Audit Results:

Our analysis of the Colorado congressional precinct election produced the following outcomes:
	
  * The total votes for the election were 369,711.
  
  * Voter turnout broke down in the following way for each county:
    * Jefferson County represented 10.5% of the voters with 38,855 votes.
    * Denver County represented 82.8% of the voters with 306,055 votes.
    * Arapahoe County represented 6.7% of the voters with 24, 801 votes.
  
  * The county with the largest voter turnout was:
    * Denver County representing 82.8% of the voters with 306,055 votes.

  * The vote breakdown for each candidate was:
    * Charles Casper Stockham received 23.0% of the total vote with 85,213 votes.
    * Diana DeGette received 73.8% of the total vote with 272,892 votes.
    * Raymon Anthony Doane received 3.1% of the total vote with 11,606 votes.

  * The winning candidate was:
    * Diana DeGette receiving 73.8% of the total vote with 272,892 votes.

---
## Summary
---
### Election Audit Suggestions

The election audit code we have written for the Colorado election commission is a solid baseline for determining candidate and voter turnout results. However, if we wanted to apply our election audit code to a larger data set such as a state election or federal election, we would only need to make minor adjustments to our script. An adjustment we could make to the script would be to make an input variable to determine election type such as federal, state, or municipality. Accordingly, when we run the script it will ask us for the election type that will be used for all the headings displayed in the output file. We must ensure that those variables designated as county are changed to a general variable name to include all election types. This entails that the input file format remains the same (Ballot ID, Federal/State/County, Candidate Name) as provided in our elections_results csv file.
The second adjustment we would make is to provide a breakdown of the total candidate votes by county or state. 

![unnamed](https://user-images.githubusercontent.com/99817571/157934067-02718632-7437-461e-be3e-11704ab03657.jpg)

---
## Resources
---
Data Source: election_results.csv
Software: Python 3.7.6, Visual Studio Code 1.65.2


