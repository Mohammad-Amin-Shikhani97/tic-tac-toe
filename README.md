<h1>TicTacToe – Console-Based Java Game</h1>

<p>
A simple Tic-Tac-Toe game in Java, featuring a human player (X) against a randomized computer (O). 
The game uses console input to gather player moves and displays the board state after each move.
Enjoy a quick match with immediate feedback and a final outcome at the end.
</p>

<h2>Table of Contents</h2>
<ol>
  <li><a href="#features">Features</a></li>
  <li><a href="#installation">Installation &amp; Compilation</a></li>
  <li><a href="#usage">Usage</a></li>
  <li><a href="#game-flow">Game Flow</a></li>
  <li><a href="#references">References</a></li>
  <li><a href="#license">License</a></li>
</ol>

<h2 id="features">Features</h2>
<ul>
  <li><strong>Console-based:</strong> Interact entirely through the console.</li>
  <li><strong>Random Opponent:</strong> The computer’s moves are driven by <code>java.util.Random</code>.</li>
  <li><strong>Classic Gameplay:</strong> Standard Tic-Tac-Toe on a 3×3 board.</li>
  <li><strong>Replay Option:</strong> Start a new game after the current session finishes.</li>
  <li><strong>Win &amp; Draw Detection:</strong> Checks for victory or tie after every move.</li>
</ul>

<h2 id="installation">Installation &amp; Compilation</h2>
<ol>
  <li><strong>Download or Clone the Source Code:</strong>
    <pre><code>git clone https://github.com/Mohammad-Amin-Shikhani97/tic-tac-toe.git</code></pre>
  </li>
  <li><strong>Check Project Structure:</strong>  
    Ensure the files are within the <code>TicTacToe</code> package directory and the package statement matches.
  </li>
  <li><strong>Compile:</strong>
    <pre><code>cd &lt;PROJECT-FOLDER&gt;
javac TicTacToe/*.java
</code></pre>
    This compiles all classes in the <code>TicTacToe</code> package.
  </li>
  <li><strong>Run:</strong>
    <pre><code>java TicTacToe.TicTacToe
</code></pre>
  </li>
</ol>

<h2 id="usage">Usage</h2>
<ol>
  <li>When the program starts, it initializes a 3×3 board.</li>
  <li>The human player (X) makes the first move by entering a position (based on user input logic).</li>
  <li>After each move, the game checks if there’s a winner or if the board is full (draw).</li>
  <li>The computer (O) makes a move using random choices.</li>
  <li>At the end of the game, it displays the outcome: either X wins, O wins, or a draw.</li>
  <li>Enter <code>'j'</code> to play again or <code>'n'</code> to quit.</li>
</ol>

<h2 id="game-flow">Game Flow</h2>
<ul>
  <li><strong>main Method:</strong> Initializes the scanner, board, and participant objects (<code>Board</code>, <code>Spieler</code>, <code>Cpu</code>), and handles the replay loop.</li>
  <li><strong>spielen Method:</strong> Runs the actual gameplay loop, alternating between player and computer moves, checking the board after each turn, and ending upon victory or draw.</li>
  <li><strong>checkWinner Method:</strong> Checks rows, columns, and diagonals for three matching symbols (X or O) to determine if someone has won.</li>
</ul>

<h2 id="license">License</h2>
<p>
This project is provided without any specific license unless otherwise stated. 
Please note that any included dependencies or libraries may have their own licensing terms.
</p>

<p><strong>Have fun playing Tic-Tac-Toe!</strong> Feel free to open an issue or submit a pull request if you have questions or suggestions.</p>
