# Tic-Tac-Toe
Problem Statement: Dynamic Memory Allocation, Arrays, and Structures: Tic-Tac-Toe Game 

In this programm, we have implemented a Tic-Tac-Toe game in C that utilizes dynamic memory 

allocation, arrays, and structures. The game will be played between two players, 'X' and 'O', on a 3x3 grid. The 

program will dynamically allocate memory for the grid and use structures to represent the players and their moves. 

1. Create a structure named Player with the following attributes: 

a. char symbol: To store the player's symbol ('X' or 'O'). 

b. int score: To store the player's score (1 for win, 0 for loss). 

2. Implement a function named initializeGrid that dynamically allocates memory for a 3x3 grid. Initialize the grid 

with empty spaces (' '). 

3. Implement a function named printGrid that takes the dynamically allocated grid as input and prints the current 

state of the Tic-Tac-Toe grid. 

4. Implement a function named checkWin that checks if a player has won the game. It should take the grid and the 

current player's symbol as input and return 1 if the player has won, 0 otherwise. 

5. Implement the main function: 

a. Initialize two instances of the Player structure, one for 'X' and one for 'O'. 

b. Use a loop to alternate between players and allow them to make moves. 

c. For each move, prompt the current player to enter their row and column choices. 

d. Validate the inputs to ensure they are within the valid range and the chosen cell is not already occupied. 

e. After each move, update the grid and print its current state. 

f. Check if the current player has won using the checkWin function. 

g. If a player wins, update their score and display the winner. 

h. If the grid is full and no one has won, display a tie message. 

6. Properly deallocate the dynamically allocated memory for the grid at the end of the program. 

7. Use proper error handling and input validation to handle incorrect user inputs gracefully. 
