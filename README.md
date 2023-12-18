## Ruby

Steps to build a Tik Tac game in Ruby

1. Initialize the Game Board:
   Create a data structure to represent the Tic-Tac-Toe board. This can be a 3x3 array or any other data structure that fits your preference.

2. Display the Game Board:
   Implement a function to display the current state of the game board. This will be useful for players to see the board after each move.

3. Player Input:
   Allow players to input their moves. This typically involves prompting the current player to enter the row and column where they want to place their symbol ('X' or 'O').

4. Make a Move:
   Update the game board based on the player's input. Ensure that the chosen cell is empty before placing the player's symbol.

5. Switch Players:
   Create a mechanism to switch between players after each move. If the current player is 'X', switch to 'O', and vice versa.

6. Check for a Winner:
   Implement a function to check for a winner after each move. Check rows, columns, and diagonals for a winning combination.

7. Check for a Tie:
   Check if the board is full after each move. If the board is full and there is no winner, declare the game a tie.

8. Main Game Loop:
   Set up a loop that continues until there is a winner or a tie. Inside the loop, take player input, make moves, and check for a winner or tie.

9. End the Game:
   Display the final state of the board and announce the winner or declare a tie. Optionally, ask the players if they want to play again.

10. Testing:
    Test the game thoroughly to ensure that it handles various scenarios, including valid and invalid inputs.
