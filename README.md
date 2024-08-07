HTML: Defines the structure with a game board consisting of 9 cells, a restart button, and a message display.
CSS: Styles the game board, cells, and other elements for a clean, user-friendly interface.
JavaScript: Implements the game functionality:
handleCellClick(): Handles user clicks on the cells, updates the game state, and checks for a win or draw.
checkWin(): Checks if the current player has won the game.
restartGame(): Resets the game state for a new game.
Description
The task is to create a Tic-Tac-Toe web application using HTML, CSS, and JavaScript. The application includes features to handle user clicks, track game state, check for winning conditions, and restart the game. Users can play against each other, aiming to get three markers in a row to win.

Usage
Playing the Game:

Click on any empty cell to place your marker (X or O).
Players alternate turns until one player gets three markers in a row or all cells are filled.
Winning the Game:

The game checks for winning conditions after each move.
If a player gets three markers in a row, a message displays the winner.
If all cells are filled without a winner, the game declares a draw.

Restarting the Game:
Click the "Restart" button to reset the game board and start a new game.

Result
When you open the index.html file in a web browser, you will see a Tic-Tac-Toe game board with 9 cells. Players take turns clicking on empty cells to place their markers (X or O). The game tracks the state and checks for a win or draw after each move. A message displays the result, and the game can be restarted by clicking the "Restart" button.

Conclusion
This project demonstrates how to create a functional Tic-Tac-Toe web application using basic web technologies. By combining HTML for structure, CSS for styling, and JavaScript for functionality, we built an interactive and engaging game. The project showcases fundamental web development skills, including DOM manipulation, event handling, and game logic implementation. This Tic-Tac-Toe game can be extended with additional features, such as AI opponents, providing a solid foundation for more complex web applications.
