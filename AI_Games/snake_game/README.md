<!DOCTYPE html>
<html>
<body>

<h1 align="center">🐍 Snake Game (AI Version)</h1>

<hr>

<h2>🎮 Overview</h2>
<p>
This is an AI-powered Snake Game built using Python and Pygame.<br>
Unlike the classic snake game controlled by a player, this version includes a simple AI agent that automatically navigates the grid to collect food using a <strong>Breadth-First Search (BFS)</strong> pathfinding strategy.
</p>

<hr>

<h2>🧠 Features</h2>

<ul>
  <li><strong>Autonomous Snake Movement</strong> — The AI uses BFS to find paths to the food.</li>
  <li><strong>Dynamic Gameplay</strong> — The snake grows longer with every food it eats.</li>
  <li><strong>Collision Detection</strong> — The game ends when the snake collides with itself.</li>
  <li><strong>Restart Option</strong> — Press <kbd>R</kbd> to restart after Game Over.</li>
  <li><strong>Score Display</strong> — Real-time score is shown on the screen.</li>
</ul>

<hr>

<h2>⚙️ How It Works</h2>

<ol>
  <li>The AI analyzes the grid each frame and computes a safe path to the food.</li>
  <li>It avoids collisions with itself by checking visited nodes using BFS.</li>
  <li>If no path is available, it makes a safe random move.</li>
</ol>

<hr>

<h2>🧩 Classes Used</h2>

<table border="1" width="100%">
  <thead>
    <tr style="background-color: #f0f0f0;">
      <th>Class</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Snake</strong></td>
      <td>Handles position, movement, growth, and rendering.</td>
    </tr>
    <tr>
      <td><strong>Food</strong></td>
      <td>Manages random placement of food.</td>
    </tr>
    <tr>
      <td><strong>SnakeAI</strong></td>
      <td>Uses BFS to find the next move toward the food.</td>
    </tr>
  </tbody>
</table>

<hr>

<h2>🧮 Algorithm Used</h2>

<h3>Breadth-First Search (BFS)</h3>
<ul>
  <li>Used to find the shortest path from the snake's head to the food.</li>
  <li>Ensures the AI can plan safe, optimal moves.</li>
</ul>

<hr>

<h2>🖼️ Game Preview (Optional)</h2>
<p>
You can add a screenshot or gif here:
</p>
<p align="center">
  <code>images/snake_game_demo.gif</code>
</p>

<hr>

<h2>🚀 How to Run</h2>

<h3>1️⃣ Install Requirements</h3>
<p>Make sure you have Python and Pygame installed:</p>
<pre><code>pip install pygame</code></pre>

<h3>2️⃣ Run the Game</h3>
<pre><code>python snake_game.py</code></pre>

<hr>

<h2>🧾 Controls</h2>

<table border="1" width="100%">
  <thead>
    <tr style="background-color: #f0f0f0;">
      <th>Key</th>
      <th>Action</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center"><kbd>R</kbd></td>
      <td>Restart the game after Game Over</td>
    </tr>
    <tr>
      <td align="center"><kbd>ESC</kbd> / Window Close</td>
      <td>Quit the game</td>
    </tr>
  </tbody>
</table>

<hr>

<p align="center">
  <strong>🐍 Enjoy watching the AI play Snake! 🐍</strong>
</p>

</body>
</html>
