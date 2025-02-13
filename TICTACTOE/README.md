Tic Tac Toe Game
This is a simple Tic Tac Toe game implemented using HTML, CSS, and JavaScript Polymorphism, Composition Asynchrounous. The game allows two players to play Tic Tac Toe in the browser, keeping track of their scores and displaying the winner or if the game is a draw. The game board can be reset at any time using the reset button.

Features
Two-player Tic Tac Toe game.
Score tracking for both players.
Displays the winner or if the game is a draw.
Reset button to start a new game.

Instructions
How to Play
Open the index.html file in a web browser.
The game board will be displayed with an empty 3x3 grid.
Player One starts by clicking on any of the grid cells to place an "X".
Player Two clicks on any of the remaining cells to place an "O".
Players alternate turns until one player wins or the game is a draw.
The game will automatically determine the winner or if the game is a draw and update the scores.
Click the "Reset" button to start a new game.
If it's draw both socres will be reset

Code Explanation
HTML
The HTML structure consists of a container that holds the game board, score display, winner display, and reset button.
Each cell in the game board is represented by a button element.
CSS
The styles are defined to create a visually appealing and responsive design.
The board buttons and reset button have hover effects for better user experience.
JavaScript
The JavaScript code defines the game logic, including checking for a winner, handling player turns, and resetting the game.
The Board class manages the display and state of the game board.
The Draw, PlayerOne, and PlayerTwo classes inherit from Board and implement the logic for determining the game outcome.
The DetermineWinners function checks if a player has won or if the game is a draw and updates the score and winner display accordingly.
The boardClick function handles user clicks on the game board.
The resetBtn function resets the game to its initial state.
The game is played by clicking on the game board, and the winner is displayed at the end of each game.

Technologies Used
HTML - The structure and content of the webpage.
CSS - The styling and presentation of the webpage.
JavaScript - The logic behind the game and user interactions.