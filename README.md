# Election_Analysis
Week 3 module, introduction to Python

## Election Audit Overview 
In this challenge the student assisted a Colorado Board of Elections employee to perform the election audit for Congress by creating a code to automate the vote count report and compute:
 * Total number of votes casted
 * Total number of votes by county
 * Percentage of votes by county
 * Identify largest county turnout
 * Total number of votes for each candidate
 * Percentage of votes for each candidate
 * Identify winner of the election based on the popular vote


## Election-Audit Results
* How many votes were cast in this congressional election?

  ![ScreenShot](https://github.com/liviamiyabara/Election_Analysis/blob/main/analysis/Total%20votes.png)

* Provide a breakdown of the number of votes (stated in the parentesis) and the percentage of total votes for each county in the precinct.

  ![ScreenShot](https://github.com/liviamiyabara/Election_Analysis/blob/main/analysis/County%20votes.png)

* Which county had the largest number of votes?

  ![ScreenShot](https://github.com/liviamiyabara/Election_Analysis/blob/main/analysis/County%20largest%20number%20%20of%20votes.png)

* Provide a breakdown of the number of votes (stated in the parentesis) and the percentage of the total votes each candidate received.

  ![ScreenShot](https://github.com/liviamiyabara/Election_Analysis/blob/main/analysis/Candidates%20vote%20breakdown.png)

* Which candidate won the election, what was their vote count, and what was their percentage of the total votes?

  ![ScreenShot](https://github.com/liviamiyabara/Election_Analysis/blob/main/analysis/Winner.png)

## Election-Audit Summary

With some modifications the script can be used for any election. In the case of the national election, besides the analysis by county, edits to the code could also provide the breakdown by state. After defining the list, dictionary and the count and percentage to zero, a for loop would be created to get the list of states:
![ScreenShot](https://github.com/liviamiyabara/Election_Analysis/blob/main/analysis/State%20vote%20count%20For%20loop.png)
Then another for loop would be used to calculate the sum of votes per state and the percentages:
![ScreenShot](https://github.com/liviamiyabara/Election_Analysis/blob/main/analysis/State%20vote%20count.png)

