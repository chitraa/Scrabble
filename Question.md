Question
	 	 	
**Online Scrabble**
A site offers tables for playing Scrabble, each table seating a maximum of four players.
On entry to the virtual room, the user can choose a free seat at any table. There is a public status board for the room indicating the number and identity of participants at each table.
If the room is full, the user can choose to wait until a seat becomes free. Alternatively, if the user does not wish to join a free table, he/she can join a table when a seat becomes free. The system will indicate the availability of a seat to waiting users, who can then choose to occupy the seat or continue waiting.
All users must play a game to completion. However, at any point a user can propose an ending to the game and if all other players agree, the current game can be ended.
The table, i.e. board, free tiles, player racks, are not visible publicly. The board is visible to all players at the table. The free tiles are invisible and the player racks are visible to the player alone.
As per the rules of Scrabble, at the beginning of the game, all players draw a single tile to determine the leader. The one with the highest tile starts the game and play proceeds clockwise.
On his turn, each player can pass, exchange one or more tiles, or make a play by placing tiles on the board. The turn is scored appropriately and the player’s score is updated. The scores are visible to other players at the table.
On completion of the game, a new game is begun.
Design a system for the above scenario.
	 	 	
*Some common principles that must be followed in the execution of the assignment*
* UNIX encourages modularity. Hence all problems must be broken into programs that each has a relatively limited functionality.
* Since modularity is strongly encouraged, the usage of appropriate communication mechanisms is critical. Usage of incompatible IPC mechanisms can overly distort the design.
* Given that familiarity with IPC mechanisms is somewhat lacking, the design 	methodology envisaged is bottom-up design. This means that the 	student has to write small proof-of-concept programs to understand nuances involved in IPC before finalizing the overall design.

