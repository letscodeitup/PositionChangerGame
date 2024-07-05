# PositionChangerGame
A simple interactive game where players can choose and replace elements at specific positions in a list.

Description:
PositionChangerGame is a simple interactive game where players can choose and replace elements at specific positions in a list. This game allows users to continuously update the list until they decide to stop.

1.How It Works:
The game starts with a list containing three elements: [0, 1, 2].

2.Display the Game List:
The display_game function prints the current state of the game list.

3.Choose a Position:
The position_choice function prompts the user to select a position in the list (0, 1, or 2).
The prompt will repeat until the user enters a valid position.

4.Replace the Value at the Chosen Position:
The replacement_choice function asks the user to enter a new value to place at the selected position in the list.
The list is then updated with this new value at the chosen position.

5.Ask to Continue Playing:
The gameon_choice function asks the user if they want to keep playing (YES or NO).
The prompt will repeat until the user enters a valid response.
If the user chooses YES, the game continues; if NO, the game ends.

6.Game Loop:
The main loop of the game continues to display the list, ask for a position and new value, and check if the user wants to keep playing.
