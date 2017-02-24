| Purpose		| Steps    | Expected Results | Actual Results | Result (P/F)| Notes |
| :----------| :------- | :----------------| :--------------| :-----------| :------| 
| Test app works	| Open App 	| App opened | App opened | P | |
| Test manager UI	| Choose manager mode	| Manager UI | Manager UI   | P  | |
| Add player	| Enter Name, username, phone number, deck choice | Player added | Player added  | P | |
| Add duplicated player	| Enter Name, username, phone number, deck choice | Player already exists | Player already exists  | P | Player info has already entered |
| Add username already taken	| Enter Name, username, phone number, deck choice | Player username already taken | Player already taken  | P | Player username is taken |
| Remove player	| Enter username | Player deleted | Player deleted  | P | Use the username to delete since it is unique |
| Enter the house cut| Enter the house cut 	| House cut added | House cut added | P | |
| Enter the entry price| Enter the entry price | Entry price added | Entry price added | P | |
| Add player to the tournament| Enter username | Player /username/ added to the tournament | Player /username/ added to the tournament| P | |
| Add duplicate player to the tournament| Enter username | Player /username/ has already added to the tournament | Player /username/ has apready added to the tournament| P | Add player that is adlready added|
| Remove player from the tournament| Enter username | Player /username/ removed from the tournament| Player /username/ removed from the tournament| P | Remove players added by mistake |
| Add player that is not existed in the system | Enter username | Player not existed | Player not exited | P | Add player that is not|
| Start a match | Choose a match from the list and click start | Mark the match as started | Mark the match as started | P | When a tournament is onging |
| End a match | End the onging match | Specify a result for the ended match | Specify a result for the ended match | P | When a tournament is onging |
| End a tournament | End the tournament | Tournament is ended | Tournament is ended | P | If ended eary, show the tournament is ended ahead of time |
| Save tournament results to the system | Click save | Tournament result is saved | Tournament result is saved | P | Save the house profit and the 1/ 2/ 3 prize |
| View totals for every player in the system | Click view totals | A list sorted by totals showed | A list sorted by totals showed | P | When there is no tournament onging |  
| View a list of a player’s individual prizes | Select a player from the list | A list of the player's individual prizes showed | A list of the player's individual prizes showed | P | When there is no tournament onging |  
| View past house profits and the total |  Click view profit history | A list of past house profits in chronological order and the total showed | A list of past house profits in chronological order and the total showed| P | When there is no tournament onging |  
