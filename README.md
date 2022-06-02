# Election-Results

The purpose of the election audit is to accomplish the following: obtain voter turnout of each county, determine the percentage of votes from each county out of the total count, the county with the highest turnout. The purpose of the code is to read from an excel file containing voting information from different counties on various candidates then output requested information by polling office. 

*Electuion-audit results:
There was a totla of 369,710 votes cast in the election, determined by the following script:

![image](https://user-images.githubusercontent.com/35518346/171747036-8e82ab2a-5fd1-4b9b-b2fb-437db3f4a093.png)


total votes was intialized at 0 to make sure all votes were counted from excel file

*County Votes: Jefferson- 10.5% (38,854 votes), Denver- 82.8% (306,055 votes) and Arapahoe 6.7% (24,801 votes). 
The number and percentage of votes were broken down by first using a for loop to to cycle through excel to find the county names and vote values from the county votes which was set as the dictionary key. The number of votes were extracted from the dictionary. Percentage was solved by a simple equation shown below. 

![image](https://user-images.githubusercontent.com/35518346/171747850-e81d9e57-27b1-4651-92d2-73f26b243c32.png)

The voting information per county was also saved externally as a text file to make sure that the data could be properly saved at any point of time. 


*Denver had the largest votes this was determined by first determining the highest vote turnout then associating the highest vote turn out with the county. This was done with the following code:

![image](https://user-images.githubusercontent.com/35518346/171748150-29bf066b-8e0e-42ba-907a-fd02174841e4.png)


*Candidate Casper Stockham recieved 85,212 votes which gave him 23% of the total votes
*Candidate Diana DeGette recieved 272,892 votes which gave her 73.8% of the total votes
*Candidate Ramon Anthony Doane recieved 11,606 votes which gave him 3.1% of the total votes

This was determined via the following code:

![image](https://user-images.githubusercontent.com/35518346/171748542-267ca9a0-31e5-428a-b010-7f310e9a1a48.png)


*Diana DeGette won the election with 272,892 votes which gave her 73.8% of the total votes - a landslide victory!


*This script will be good for automating key election results such as total votes, percentage of votes, highest vote turnout and associating that information with candidate name and county. However, some modifications can be utilized to the code for it to be used for primary elections where variables such as party affiliation, gender, age etc. can be added to the code. This way demographic information can be obtained on who is voting for which candidate within a specific party. Another way the code can be modified is to use as a template to potentially predict probability of voter turnout and chances of which candidate has the highest chance of getting more votes within a given county/state or country. This of course will require a substainal amount of existing voting data but thankfully much of that is available online (e.g. registered party affiliation, elections in which you did vote in or not, voter name and address, some popularity survey).

