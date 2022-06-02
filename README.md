# Election-Results

The purpose of the election audit is to accomplish the following: obtain voter turnout of each county, determine the percentage of votes from each county out of the total count, the county with the highest turnout. The purpose of the code is to read from an excel file containing voting information from different counties on various candidates then output requested information by polling office. 

Electuion-audit results:
How many votes were cast in this congressional election?
There was a totla of 369, 710 votes cast in the election, determined by the following script

![image](https://user-images.githubusercontent.com/35518346/171747036-8e82ab2a-5fd1-4b9b-b2fb-437db3f4a093.png)


total votes was intialized at 0 to make sure all votes were counted from excel file

Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
County Votes: Jefferson- 10.5% (38,854 votes), Denver- 82.8% (306,055 votes) and Arapahoe 6.7% (24,801 votes). 
The number and percentage of votes were broken down by first using a for loop to to cycle through excel to find the county names and vote values from the county votes which was set as the dictionary key. The number of votes were extracted from the dictionary. Percentage was solved by a simple equation shown below. 

![image](https://user-images.githubusercontent.com/35518346/171747850-e81d9e57-27b1-4651-92d2-73f26b243c32.png)

The voting information per county was also saved externally as a text file to make sure that the data could be properly saved at any point of time. 

Which county had the largest number of votes?
Denver had the largest votes this was determined by first determining the highest vote turnout then associating the highest vote turn out with the county. This was done with the following code:

![image](https://user-images.githubusercontent.com/35518346/171748150-29bf066b-8e0e-42ba-907a-fd02174841e4.png)


Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
Candidate Casper Stockham recieved 85,212 votes which gave him 23% of the total votes
Candidate Diana DeGette recieved 272,892 votes which gave her 73.8% of the total votes
Candidate Ramon Anthony Doane recieved 11,606 votes which gave him 3.1% of the total votes

This was determined via the following code:

![image](https://user-images.githubusercontent.com/35518346/171748542-267ca9a0-31e5-428a-b010-7f310e9a1a48.png)


Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
Diana DeGette won the election with 272,892 votes which gave her 73.8% of the total votes - a landslide victory!
