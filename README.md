# Election_Analysis
## Project Overview
In this project, We are assisting Tom, a Colorado Board of Election employee in an audit election  of a recent local congressional election. We will : 
1- Be analyzing and reporting vote cast.
2- Get the complete list of candidates who received votes.
3- Calulate votes for each candidate. 
4- Caluclate the total percentage of votes each candidate won.
5- Determine the winners of the election.
6- Calculate the vote turnout for each county
7- Calculte the percentage of votes from each county.
8- Dtermine the county with the highest turnout. 

## Ressources 
- Data Source: Election_results.csv.
- We will be using Python 3.7 and Visual Studio Code 1.38 to accomplish this project. 

## Election_Audit Results
The report of the election show that:
- There was 369,711 total votes in this election.
- The candidate were:
    - Charles Casper Stockham
    - Diana DeGette
    - Raymon Anthony Doane
- The election results were:
    -  Charles Casper Stockham with 23.0% of the vote and 85,213 number of votes
    - Diana DeGette with 73.8% of the vote and 272,892 number of votes
    - Raymon Anthony Doane with 3.1% of the vote and 11,606 number of votes.
We added the vote to the candidate name by using this formula : candidate_votes[candidate_name] += 1.
- The winner of the election were: 
    - Diana DeGette who received 73.8% of the vote and 272,892 number of votes.
- The vote and percentage turnout for each county: 
    - Arapahoe county : 24,801 votes with 6.7%
    - Denver county : 306,055 votes with 82.8%
    - Jefferson county : 38,855 votes with 10.5 %
We calculate the percentage vote by using this formula : vote_percentage = float(votes) / float(total_votes) * 100. Then we had to write an if statement to get the county name listed just once. The way we did that was by checking in the county does not match any existing county in the county list, we add the existing county to the list.
- The largest turnout county : 
    - Denver
## Election_Audit Summary
My proposition in this project would be to use this script to be use in the National election. We would want to the the winner in a specific state by initializing the state vote,country total vote, state percentage vote and assigning to a variable. So an example would be state_vote = 0 , state_percentage = 0, state_winner = "". We would calulate to percentage by using this formula: state_percentage = float(state_votes) / float(float(country_votes) * 100.
