# Challenge_03_Python_PyPoll

# PyPoll with Python

## Overview of Project

Based on the data provided by the clients, there is a need to analyze it in order to determine the winners of the elections. Inside the data provided was included the ballot ID, the county and the candidates.

### This project includes:
- The total votes
- Votes per county
- The county that won most votes with percentage and voter counter
- The candidate names, total votes for each one and their respective percentage
- The winner of the election with votes and percentage

### Purpose

Get to visualize data in order to determine the total voters, votes per county, candidate names and the winner of the election with the respective total votes and percentage. This will make an automated script that makes everything as fast as possible and will get the results written in a .txt file so the user can run it from the terminal, command prompt or GitBash depending on the OS. 

## Analysis and Challenges

The first challenge for making the code needed for the analysis, is to remember to use the dictionaries and the lists respective brackets and curly brackets. Also name the variables in a way that could be easy for someone else to read the code. This time the code was rather simple, but if the identation is not used in a proper way, it could lead to the code not working.

### Analysis of Candidate results

Using this code, it can be seen that the candidates received different results in the votes that ended like the following: 

- Charles Casper Stockham: received 85,213 votes and ended with 23.0% of the votes in the election.
- Diana DeGette: received 272,892 votes and ended with 73.8% of the votes in the election.
- Raymon Anthony Doane: received 11,606 votes and ended with 3.1% of the votes in the election.

As can be seen, the candidate with the most votes was Diana DeGette while the one with less votes was Raymon Anthony Doane.

At the end the winner was Diana DeGette with 272,892 votes that corresponds to the 73.8% of the total votes in the election. In second place, the candidate Charles Casper Stockham that received 85,213 votes that is the 23.0% of the total votes. And at last, the candidate Raymon Anthony Doane with 11,892 votes and getting only the 3.1% of the total votes in this election.

![Candidate](https://github.com/LennethNova/Challenge_03_Python_PyPoll/blob/main/Resources/Candidate_winner.PNG)

### Analysis of County results
The total votes for the congressional election were 369,711 and were cast in the following order:
- Jefferson county obtained a 10.5% of the total votes with 38,855 votes.
- Denver county obtained a 82.8% of the total votes with 306,055 votes.
- Arapahoe county obtained a 6.7% with 24,801 votes.

The largest number of votes received was from Denver and the lowest was Arapahoe.

As seen on the numbers per county, the one that obtained the largest amount was Devner with 306,055 votes; followed by Jefferson with 38,855 votes and, in last place was Arapahoe with 24,801 votes in total. 

![County](https://github.com/LennethNova/Challenge_03_Python_PyPoll/blob/main/Resources/Total_votes_per_county.PNG)

### Election-Audit summary

During this election it was easier to count every vote and separate every candidate with their respective votes thanks to the help of this code. This way is easier due to the extended amount of data and the simplicity of it. Given he opportunity to work with python, it can help to analyze (with proper work in it) data faster than Excel and provide results that will help keep the information organized even if there is no order in them.

There are plenty of advantages that this code can provide and, if modified correctly, it can be used in other election data by modifying the root .csv in order to analyze other data or increase the data in the .csv for further analysis. Also, if there is another column of data to analyze, it can be added to the dictionaries and provide another study. This could be useful also for counting votes for different universities when they have elections to select their student representative per faculty, selecting the new dean or any person that is needed for any position that needs to hold a democratic vote using popular vote.

### Challenges and Difficulties Encountered
The final user would have to know how to run the .py file in order to execute the instructions and write the results in the .txt, this will also will be linked to the corresponding .csv that is included here, so if there is a need to analyze the data from other file, it will have to be renamed the same as the .csv that is inluded in the resources folder.

## Results and additional notes
- The final results for this election is that Diana DeGette is the winner.
- This code can be used for different purposes such as academics or other minor elections.
- This code can be modified in order to get wider results depending on the data to analyze.
- The dictionaries and lists form an important part of the functionality of this code.
- Python is more user friendly than VBA.

