Download Link: https://assignmentchef.com/product/solved-comp2130-assignment-terminal-based-scrabble-like-game
<br>
In this assignment, you will be tasked to create a terminal based scrabble like game. The name of this game is MyScrabble. This game is played between two human players on a 8 x 8 grid as shown in Figure 1. The aim of the game is to spell words with 4 or more letters. Each letter has a value as shown below, so therefore, a player’s score for a word is calculated by using these values. A <em>words.txt</em> file will be provided to check against for valid words. The game should begin by randomly placing 10 letters on the board. You are given some helper code to help with displaying and basic manipulation of the board.

SCRABBLE_LETTER_VALUES = {

‘A’: 1, ‘B’: 3, ‘C’: 3, ‘D’: 2, ‘E’: 1, ‘F’: 4, ‘G’: 2, ‘H’: 4, ‘I’: 1, ‘J’: 8, ‘K’: 5, ‘L’: 1, ‘M’: 3, ‘N’: 1, ‘O’: 1, ‘P’: 3,

‘Q’: 10, ‘R’: 1, ‘S’: 1, ‘T’: 1, ‘U’: 1, ‘V’: 4, ‘W’: 4, ‘X’: 8, ‘Y’: 4, ‘Z’: 10

}

<strong>Rules:</strong>

<ol>

 <li>To get a score for a word, the last letter played should start a word in any direction. This rule is included to simplify the game. For example, if the following letters are on the board “tao” and “b” is placed after “o” then the word become “boat”.</li>

 <li>The players will take turns in placing a letter on the board. Each player must either place a letter on the board or ask to quit the game.</li>

 <li>The game ends when there are no more empty squares on the board, or one of the player types</li>

</ol>

‘quit’

<ol start="4">

 <li>The score should be displayed and the winner of the game at the end of the game.</li>

</ol>

<strong>Figure 1</strong>

Your implementation <strong>must</strong> at least create the following functions:

<strong>Function 1:</strong>

You need to create a function getPlayerMove(). This function must first ask for the letter to play or for the user to type ‘quit’ if they want to end the game. This function should then get the x and y coordinates on the grid to place the letter in the form xy. Therefore, if the position that the player wants to move is x = 4 and y =7, the player should enter xy.




<strong>Function 2:</strong>

Create a function calculateScore(char * word). This function should take a word and calculate the score for that word based on the dictionary like structure that holds the letter values. Function should return the score for the word.

<strong>Function 3:</strong>

Create a function isOnBoard(int x, int y). This function should take and x and y coordinate and return an integer to represent True if the coordinates are on the board or an integer to represent False if they are not.

<strong>Function 4:</strong>

Create a function startBoard(). This function uses the board to randomly position 10 letters on the board.

<strong>TIPS</strong>

Make sure you use functions appropriately.

Your code should be properly commented.

Break down the problems into small workable units and create associated functions.