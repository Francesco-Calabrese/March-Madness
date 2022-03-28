# March-Madness
Predicts the winner for the NCAA March Madness Tournament using team stats from ESPN (https://www.espn.com/mens-college-basketball/teams). 


Inputs
---------
teams.txt - text file containing one team per line starting with the west bracket, east bracket, south bracket, and finally the midwest bracket. 

rules.txt - text file to assign points that is used to calculate the winner.

other rules.txt - same as the rules.txt file but applies only to the south and midwest bracket teams.

Operation
-----
Upon launching the program, basic instructions are displayed in a message dialog box. Selecting yes will continue the program, selecting no or cancel will exit the program.


![image](https://user-images.githubusercontent.com/96243400/160413954-36bed2f6-e936-4eeb-bcd9-eff4935f8bf0.png)

If the user continues with the program, a status bar will display with the percent complete. Five brackets will be displayed once all data is retrieved: one for the west bracket, east bracket, south bracket, midwest bracket, and final four bracket. If any of the three inputs needed are not found, a message will display alerting the user and will then exit the program.


![image](https://user-images.githubusercontent.com/96243400/160413752-9e09c445-0efd-418e-89eb-92b8d74068c7.png)



![image](https://user-images.githubusercontent.com/96243400/160413664-ab979b68-1ac2-4c4f-a949-abe57b7fa679.png)


Calculation
-----
This program begins by automatically advancing the first four seeded teams of each bracket to the second round. 

It then uses the rules.txt file to assign points per statistic for the west, east, and final four brackets, and the other rules.txt file for the south and midwest brackets.

The final points found by these rules are then multiplied by a percentage (average game percent, season percent) to offset the major point differences. 

Updates
-----
This program has only imported the 64 teams that participated in the 2022 March Madness Event. To upload more teams, go to the teams section on ESPN (https://www.espn.com/mens-college-basketball/teams) and copy the statistics link under the team name. Add that link to 
