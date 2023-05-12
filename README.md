# Snake_and_Ladder_Java_Oops
All core concepts of obejct oriented programe is  Covered in this Game.
This is a simple console-based implementation of the popular game Snake and Ladder built using Core Java. The game supports multiple players and random dice rolls. The objective of the game is to be the first player to reach the end of the board by climbing ladders and avoiding snakes.

# Installation and Usage
<ol>
  <li>Clone the repository: git clone https://github.com/your-username/Snake-Ladder-Game.git</li>
<li>Navigate to the project directory: cd Snake-Ladder-Game</li>
<li>Compile the Java files: javac *.java</li>
<li>Run the game: java Main</li>
  </ol>

# Gameplay
<ol>
  <li>The game starts by prompting the user to enter the number of players.</li>
<li>Each player takes turns rolling a six-sided dice. The number on the dice determines the number of steps the player can move on the board.</li>
<li>If a player lands on a ladder, they move up to the square at the top of the ladder.</li>
<li>If a player lands on a snake, they move down to the square at the tail of the snake.</li>
<li>The first player to reach the end of the board wins the game.</li>
  </ol>
#  Implementation Details
<p>
The game is built using Core Java and follows the object-oriented programming paradigm. The main classes and their responsibilities are as follows:</p>

# Snake
<p>The Snake class represents the Snake and its properties. It contains the head and the tail value of the Snake.</p>

# Ladder
<p>The Ladder class represents the Snake and its properties. It contains the start and the end value of the Ladder.</p>

# Board
<p>The Board class represents the game board and its properties. It contains the number of squares on the board, the positions of the ladders and snakes, and the current positions of the players.</p>

# Player
<p>The Player class represents a player in the game. It contains the player's name and current position on the board.
</p>
# Dice
<p>The Dice class represents the dice used in the game. It generates a random number between 1 and 6 when rolled.</p>

# Main
<p>The Main class contains the main method and is responsible for starting the game. It prompts the user for the number of players and initializes the game board and players. It then runs the game loop until a player reaches the end of the board.</p>

# Conclusion
<p>This Snake and Ladder game implementation using Core Java is a fun and interactive way to practice object-oriented programming concepts and Java syntax. The game is easy to install and run, and can be easily modified and customized to suit individual preferences.</p>
