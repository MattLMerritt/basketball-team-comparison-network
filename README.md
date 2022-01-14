# basketball-team-comparison-network
A tool to visualize the connections between winning teams in the NBA using network and visualization libraries.
The goal of the project is to create a graph representing the victory of teams over another using a connected directional graph. 
Each node represents a team and an arrow pointing from team A to team B represent team A's victory over team B. 
The definition of victory in this case is that a team has more wins against the other team - there are no arrows for ties.


## Notes
- Does not add ties to adjacency matrix
- In this program, 3 teams that are normally apart of the NBA lineup are removed for a more visible graph. The teams are
    - Utah Jazz, Washington Wizards, and Oklahoma City Thunder
- Data was provided by [Basketball-Reference.com](https://www.basketball-reference.com/) and is from November 2019
    - To replicate the cvs file for other months, download a month from the cite in csv format and remove all headers except at the top.
