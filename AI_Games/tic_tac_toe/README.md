<!DOCTYPE html>
<html>
<body>

<h1 align="center">🎮 Tic Tac Toe</h1>

<hr>

<h2>🧠 Overview</h2>
<p>
This project is an AI-based Tic Tac Toe game built with Python and Pygame.<br>
It allows a human player to compete against an intelligent AI that uses the <strong>Minimax algorithm</strong> with <strong>Alpha-Beta Pruning</strong> for optimal gameplay.
</p>

<hr>

<h2>🚀 Features</h2>

<ul>
  <li><strong>🎯 Human vs AI Gameplay</strong> — Play directly against a smart AI opponent.</li>
  <li><strong>🧩 Minimax Algorithm</strong> — Ensures the AI makes optimal moves.</li>
  <li><strong>⚡ Alpha-Beta Pruning</strong> — Improves efficiency by reducing unnecessary state exploration.</li>
  <li><strong>💥 Visual Game Board</strong> — Beautifully designed interface using Pygame.</li>
  <li><strong>🔁 Restart Option</strong> — Press <kbd>R</kbd> to restart anytime.</li>
  <li><strong>🏆 Win Detection</strong> — Displays win lines and end messages instantly.</li>
</ul>

<hr>
<br><img width="998" height="1024" alt="Screenshot 2025-10-26 222442" src="https://github.com/user-attachments/assets/77b5c9e1-73c6-4392-a542-2a46d2b82a9b" />

<br><img width="1001" height="1015" alt="Screenshot 2025-10-26 222500" src="https://github.com/user-attachments/assets/31a518ab-44cb-4290-97c9-62361ff1629c" />

<br><img width="993" height="1017" alt="Screenshot 2025-10-26 222523" src="https://github.com/user-attachments/assets/666277b0-2c72-4309-83c1-08bd6ce9d057" />


<h2>⚙️ How It Works</h2>

<p>
The AI checks all possible moves recursively using the <strong>Minimax algorithm</strong> to find the best outcome:
</p>

<ul>
  <li><strong>Maximizing player (AI)</strong> tries to get a win (+1).</li>
  <li><strong>Minimizing player (Human)</strong> tries to make the AI lose (–1).</li>
  <li><strong>Alpha-Beta pruning</strong> reduces unnecessary branches to speed up the decision-making process.</li>
</ul>

<hr>

<h2>🧩 Key Functions</h2>

<table border="1" width="100%">
  <thead>
    <tr style="background-color: #f0f0f0;">
      <th>Function</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code>minimax()</code></td>
      <td>Recursive search that evaluates all possible moves.</td>
    </tr>
    <tr>
      <td><code>ai_move()</code></td>
      <td>Selects the best move based on minimax score.</td>
    </tr>
    <tr>
      <td><code>check_win()</code></td>
      <td>Checks for winning combinations.</td>
    </tr>
    <tr>
      <td><code>draw_figures()</code></td>
      <td>Renders X's and O's on the board.</td>
    </tr>
    <tr>
      <td><code>restart()</code></td>
      <td>Resets the board for a new round.</td>
    </tr>
  </tbody>
</table>

<hr>


<h2>🎮 Controls</h2>

<table border="1" width="100%">
  <thead>
    <tr style="background-color: #f0f0f0;">
      <th>Key</th>
      <th>Action</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center"><strong>Mouse Click</strong></td>
      <td>Place your move (O)</td>
    </tr>
    <tr>
      <td align="center"><kbd>R</kbd></td>
      <td>Restart the game</td>
    </tr>
    <tr>
      <td align="center"><kbd>ESC</kbd> / Window Close</td>
      <td>Quit the game</td>
    </tr>
  </tbody>
</table>

<hr>

<h2>🏁 How to Run</h2>

<h3>1️⃣ Install Dependencies</h3>
<pre><code>pip install pygame numpy</code></pre>

<h3>2️⃣ Run the Game</h3>
<pre><code>python tic_tac_toe.py</code></pre>

<hr>

<h2>🧾 Game Rules</h2>

<ul>
  <li>Player uses <strong>O</strong> (circle).</li>
  <li>AI uses <strong>X</strong> (cross).</li>
  <li>First to align 3 in a row (horizontal, vertical, or diagonal) wins.</li>
  <li>Game ends with a <strong>Win</strong>, <strong>Loss</strong>, or <strong>Tie</strong> message.</li>
</ul>

<hr>

<p align="center">
  <strong>🎯 Challenge yourself against the unbeatable AI! 🎯</strong>
</p>

</body>
</html>
