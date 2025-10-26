<!DOCTYPE html>
<html>
<body>

<h1 align="center">♟️ Chess Game</h1>

<p align="center">
A simple chess game implemented in Python using the Pygame library. It features a basic AI that calculates the optimal move by peeking <strong>DEPTH</strong> moves ahead. The AI assesses positions and scores only.
</p>

<p align="center">
  <em>Untitled video - Made with Clipchamp</em>
</p>

<hr>

<h2>📖 Introduction</h2>
<p>
This is a basic implementation of a chess game with a graphical user interface. The game allows two players to make moves on a standard chessboard. Additionally, there is an AI opponent that uses <strong>negamax algorithm</strong>, <strong>alpha beta pruning</strong> for move selection.
</p>

<hr>

<h2>✨ Features</h2>

<h3>🖥️ Graphical User Interface:</h3>
<ul>
  <li>The game features a user-friendly graphical interface developed using the Pygame library.</li>
</ul>

<h3>👥 Two-player Mode:</h3>
<ul>
  <li>Play against a friend in human vs. human gameplay. Enjoy the classic chess experience with two human players.</li>
</ul>

<h3>🤖 AI Opponent:</h3>
<ul>
  <li>Challenge yourself against an AI opponent equipped with the negamax algorithm and alpha-beta pruning. The AI has options to make valid moves, providing a single-player chess experience.</li>
</ul>

<h3>♔ Checkmate, Stalemate, and Legal Moves:</h3>
<ul>
  <li>The game checks for conditions such as checkmate, stalemate, and legal moves, ensuring a fair and rule-compliant gameplay experience.</li>
</ul>

<h3>🎯 Advanced Chess Mechanics:</h3>
<ul>
  <li>Supports advanced chess mechanics, including pawn promotion, en passant, and castling for a more strategic and engaging experience.</li>
</ul>

<h3>↩️ Undo and Reset Board:</h3>
<ul>
  <li>Press <kbd>Z</kbd> for undo, <kbd>R</kbd> for reset</li>
</ul>

<h3>🎨 Variety of Chess Boards:</h3>
<ul>
  <li>Enjoy playing on different chess board colors, adding a personalized touch to your gaming experience.</li>
</ul>

<h3>🔊 Immersive Sounds and Images:</h3>
<ul>
  <li>Enhance your gaming experience with multiple piece move or capture sounds.</li>
</ul>

<hr>

<h2>♟️ Special Moves</h2>

<h3>En Passant</h3>
<p>
In chess, the en passant rule allows a pawn to capture an opponent's pawn that has moved two squares forward from its starting position. The capturing pawn moves to the square immediately beyond the captured pawn. Here's how it works:
</p>

<table>
  <tr>
    <td><strong>Initial Position:</strong></td>
    <td>Chessboard</td>
  </tr>
  <tr>
    <td><strong>Opponent's Move:</strong></td>
    <td>Chessboard</td>
  </tr>
  <tr>
    <td><strong>En Passant Capture:</strong></td>
    <td>Chessboard</td>
  </tr>
</table>

<h3>Pawn Promotion</h3>
<p>
In chess, pawn promotion occurs when a pawn reaches the eighth rank. The pawn can be promoted to any other chess piece (except a king). Here's how it works:
</p>

<table>
  <tr>
    <td><strong>Reach the Eighth Rank:</strong></td>
    <td>Chessboard</td>
  </tr>
  <tr>
    <td><strong>Select the Promotion Piece:</strong></td>
    <td>Chessboard</td>
  </tr>
</table>

<hr>

<h2>🎮 How to Play</h2>

<ol>
  <li>Clone the repository to your local machine.</li>
  <li>Install the required dependencies.
    <pre><code>pip install pygame</code></pre>
  </li>
  <li>Run the <code>main.py</code> script to start the game.
    <pre><code>python main.py</code></pre>
  </li>
</ol>

<h3>Using Visual Studio Code:</h3>
<ol>
  <li>Open Visual Studio Code.</li>
  <li>Click on "File" → "Open Folder" and select the cloned directory.</li>
  <li>Open the integrated terminal in Visual Studio Code.</li>
  <li>Run the following command to start the game:
    <pre><code>python main.py</code></pre>
  </li>
</ol>

<hr>

<h2>🎮 Controls</h2>
<p>The controls for the chess game are designed to be intuitive and user-friendly.</p>

<h3>Selecting a Piece:</h3>
<ul>
  <li>Click on the chess piece you want to move. The selected piece will be highlighted to indicate that it's ready for a move.</li>
  <li>If AI is thinking you can click on AI piece to see all possible moves.</li>
</ul>

<h3>Moving a Piece:</h3>
<ul>
  <li>After selecting a piece, the legal moves for that piece will be highlighted on the chessboard.</li>
  <li>Click on one of the highlighted squares to move the selected piece to that position.</li>
  <li>The game will automatically handle the rules of chess, including legal moves, capturing opponent pieces, pawn promotion, en passant, and castling.</li>
</ul>

<hr>

<h2>💾 Installation</h2>

<h4>1. Clone the repository:</h4>
<pre><code>git clone https://github.com/anuragjain-git/chess-bot.git</code></pre>

<h4>2. Navigate to the project directory:</h4>
<pre><code>cd chess</code></pre>

<h4>3. Install dependencies:</h4>
<pre><code>pip install -r requirements.txt</code></pre>

<h4>4. Run the game:</h4>
<pre><code>python main.py</code></pre>

<hr>

<p align="center">
  <strong>♟️ Enjoy playing Chess! ♟️</strong>
</p>

</body>
</html>
