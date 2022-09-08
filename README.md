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
   
    ![Screen Shot 2022-09-08 at 12 56 55 PM](https://user-images.githubusercontent.com/103543959/189194618-e618381c-c4ab-4b06-aed7-70d8921d9fd2.png)

![Screen Shot 2022-09-08 at 1 04 36 PM](https://user-images.githubusercontent.com/103543959/189196002-7f9ff96e-4880-47da-bdcc-9aa8ad53dd3d.png)

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
    
   ![Screen Shot 2022-09-08 at 12 57 35 PM](https://user-images.githubusercontent.com/103543959/189195574-5179444b-b3db-4992-977f-e59890c6618f.png)

![Screen Shot 2022-09-08 at 1 04 59 PM](https://user-images.githubusercontent.com/103543959/189195698-908e3d92-cb95-4124-a8ca-a29ae65848ad.png)

We calculate the percentage vote by using this formula : vote_percentage = float(votes) / float(total_votes) * 100. Then we had to write an if statement to get the county name listed just once. The way we did that was by checking in the county does not match any existing county in the county list, we add the existing county to the list.
- The largest turnout county : 
    - Denver
## Election_Audit Summary
My proposition in this project would be to use this script to be use in the National election. We would want to the the winner in a specific state by initializing the state vote,country total vote, state percentage vote and assigning to a variable. So an example would be state_vote = 0 , state_percentage = 0, state_winner = "". We would calulate to percentage by using this formula: state_percentage = float(state_votes) / float(float(country_votes) * 100.


![Screen Shot 2022-09-08 at 1 03 58 PM](https://user-images.githubusercontent.com/103543959/189194883-18035e2f-a138-4480-94b4-8b0631bae0a0.png)

![Screen Shot 2022-09-08 at 12 58 16 PM](https://user-images.githubusercontent.com/103543959/189195493-fc40bd34-3ace-4df8-8cff-379ed16e9ca8.png)

