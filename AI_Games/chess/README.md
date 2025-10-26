<!DOCTYPE html>
<html>
<body>

<h1 align="center">♟️ Chess Game</h1>

<p align="center">
A simple chess game implemented in Python using the Pygame library. It features a basic AI that calculates the optimal move by peeking <strong>DEPTH</strong> moves ahead. The AI assesses positions and scores only.
</p>

<p align="center">
  <img width="801" height="892" alt="Screenshot 2025-10-25 205226" src="https://github.com/user-attachments/assets/234ad99f-0114-48cc-bfb3-52d3abc021f5" />
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


<h3>🤖 AI Chess:</h3>
<ul>
  <li>Challenge yourself against an AI opponent equipped with the negamax algorithm and alpha-beta pruning. The AI has options to make valid moves, providing a single-player chess experience.</li>
</ul>

<h3>♔ Checkmate, Stalemate, and Legal Moves:</h3>
<ul>
  <li>The game checks for conditions such as checkmate, stalemate, and legal moves, ensuring a fair and rule-compliant gameplay experience.</li>
</ul>

<h3>↩️ Undo and Reset Board:</h3>
<ul>
  <li>Press <kbd>Z</kbd> for undo, <kbd>R</kbd> for reset</li>
</ul>

<h3>🎨 Variety of Chess Boards:</h3>
<ul>
  <li>Enjoy playing on different chess board colors, adding a personalized touch to your gaming experience.</li>
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
    <img width="799" height="893" alt="Screenshot 2025-10-25 205517" src="https://github.com/user-attachments/assets/b1f73225-84f0-49c3-ba15-1920b2369265" />

  </tr>
  <tr>
    <td><strong>Opponent's Move:</strong></td><br>
    <img width="805" height="884" alt="Screenshot 2025-10-25 205434" src="https://github.com/user-attachments/assets/3de8621a-8f61-435a-9797-e696e062f8a0" />

  </tr>

<h3>Pawn Promotion</h3>
<p>
In chess, pawn promotion occurs when a pawn reaches the eighth rank. The pawn can be promoted to any other chess piece (except a king). Here's how it works:
</p>

  <tr>
    <td><strong>Reach the Eighth Rank:</strong></td>
    <img width="804" height="883" alt="Screenshot 2025-10-25 210942" src="https://github.com/user-attachments/assets/4a7db9d7-cc52-4224-b441-d44a260b1181" />

  </tr>

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
