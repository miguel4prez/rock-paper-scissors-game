Here is the link to see the project in full: https://miguel4prez.github.io/rock-paper-scissors-game/

Rock, Paper, Scissors
This is a simple Rock, Paper, Scissors game implemented in HTML, CSS, and JavaScript. The game allows you to choose one of the three options (Rock, Paper, or Scissors) and compete against the computer. The outcome of the game is displayed, and your score is kept track of.

How to Play:
Open the HTML file in a web browser.
Click on one of the three buttons to make your move: Rock, Paper, or Scissors.
The computer will randomly pick its move.
The result of the game will be displayed, indicating whether you won, lost, or tied.
Your score will be updated based on the outcome of the game.
You can reset the score by clicking the "Reset Score" button.

File Structure:
index.html - The main HTML file that contains the game interface and buttons.
styles.css - The CSS file that defines the styles for the game interface.
app.js - The JavaScript file that handles the game logic.

Dependencies:
This project requires the following dependencies:
images/rock-emoji.png: Image file for the rock icon.
images/paper-emoji.png: Image file for the paper icon.
images/scissors-emoji.png: Image file for the scissors icon.

Google Fonts: The project uses the "Play" and "Roboto" fonts from Google Fonts. The fonts are imported using the @import rule.

How the Game Works:
When you click on a move button, the playGame() function is called with the corresponding move as a parameter.
The playGame() function generates a random move for the computer using the pickComputerMove() function.
The outcome of the game is determined based on your move and the computer's move.
The score is updated according to the outcome of the game.
The result of the game and the moves chosen by you and the computer are displayed on the screen.
The score is updated and displayed.
You can reset the score by clicking the "Reset Score" button.

Note: The score is stored in the browser's local storage, so it will persist even if you refresh the page.

Enjoy playing Rock, Paper, Scissors!
