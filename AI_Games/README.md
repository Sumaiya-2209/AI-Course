<h1>🎮 AI Game Collection (Python)</h1>
<p>A collection of three classic AI-powered games built in Python, featuring Chess, Tic Tac Toe, and Snake Game. Each game uses AI algorithms like Minimax, Alpha-Beta Pruning, and Heuristic Evaluation for intelligent decision-making.</p>

<h2>🧠 Overview</h2>
<p>This project demonstrates Artificial Intelligence search algorithms in game development. The key AI techniques implemented include:</p>
<ul>
  <li>✅ <strong>Minimax Algorithm</strong> – Recursive decision-making for optimal moves.</li>
  <li>✅ <strong>Alpha-Beta Pruning</strong> – Optimizes Minimax by skipping unnecessary branches.</li>
  <li>✅ <strong>Heuristic Evaluation</strong> – Scores board positions for better AI decisions.</li>
  <li>✅ <strong>Depth-Limited Search</strong> – Prevents excessive computation in complex games.</li>
</ul>
<p>Each game has a simple GUI (using <code>tkinter</code> or <code>pygame</code>) with a consistent interface.</p>

<h2>🎯 Games Included</h2>

<h3>1️⃣ Chess (AI vs Player)</h3>
<p><strong>Description:</strong><br>
A simplified Chess AI that predicts the best move using Minimax + Alpha-Beta Pruning. The AI evaluates possible future board states to make intelligent decisions.</p>

<p><strong>AI Algorithms Used:</strong></p>
<ul>
  <li>Minimax Algorithm</li>
  <li>Alpha-Beta Pruning</li>
  <li>Depth-Limited Search</li>
  <li>Piece Value Evaluation Function</li>
</ul>

<p><strong>How It Works:</strong></p>
<ul>
  <li>AI generates all legal moves.</li>
  <li>Evaluates the board using a scoring function (based on piece values &amp; positions).</li>
  <li>Uses Minimax to select the optimal move.</li>
  <li>Alpha-Beta Pruning reduces unnecessary computations.</li>
</ul>

<p><strong>Features:</strong><br>
✔ Legal move validation<br>
✔ AI difficulty adjustment (depth limit)<br>
✔ Simple GUI (<code>tkinter</code>/<code>pygame</code>)</p>

<hr>

<h3>2️⃣ Tic Tac Toe (Unbeatable AI)</h3>
<p><strong>Description:</strong><br>
A 3×3 grid game where the player competes against an AI that never loses. The AI uses Minimax with Alpha-Beta Pruning to always make the best move.</p>

<p><strong>AI Algorithms Used:</strong></p>
<ul>
  <li>Minimax Algorithm (evaluates all possible moves)</li>
  <li>Alpha-Beta Pruning (optimizes search)</li>
</ul>

<p><strong>How It Works:</strong></p>
<ul>
  <li>The game board is represented as a 3×3 matrix.</li>
  <li>AI simulates all possible moves recursively.</li>
  <li>Uses Minimax to choose the move that maximizes its winning chance.</li>
  <li>Alpha-Beta Pruning reduces the number of evaluated nodes.</li>
</ul>

<p><strong>Features:</strong><br>
✔ Unbeatable AI (always wins or forces a draw)<br>
✔ Simple GUI (<code>tkinter</code>)<br>
✔ Player vs AI mode</p>

<hr>

<h3>3️⃣ Snake Game (AI Pathfinding)</h3>
<p><strong>Description:</strong><br>
A classic Snake Game where the AI snake automatically navigates to eat food while avoiding collisions. Uses pathfinding algorithms (like BFS or A*).</p>

<p><strong>AI Algorithms Used:</strong></p>
<ul>
  <li>Breadth-First Search (BFS) – Finds the shortest path to food.</li>
  <li>A* Algorithm (optional) – Optimized pathfinding.</li>
  <li>Collision Avoidance – Prevents self-collision.</li>
</ul>

<p><strong>How It Works:</strong></p>
<ul>
  <li>The AI scans the board for food.</li>
  <li>Uses BFS/A* to find the shortest safe path.</li>
  <li>Moves the snake automatically while avoiding walls &amp; itself.</li>
  <li>Grows longer when eating food.</li>
</ul>

<p><strong>Features:</strong><br>
✔ AI-controlled snake (no manual input needed)<br>
✔ Score tracking<br>
✔ Simple GUI (<code>pygame</code>)</p>

<hr>

<h2>🛠 Installation &amp; Setup</h2>

<h3>Prerequisites</h3>
<ul>
  <li>Python 3.x</li>
  <li>Required libraries:</li>
</ul>
<pre><code class="language-shell">pip install pygame numpy
</code></pre>

<h3>How to Run</h3>
<p>Clone the repository:</p>
<pre><code class="language-shell">git clone https://github.com/yourusername/ai-game-collection.git
cd ai-game-collection
</code></pre>
<p>Run any game:</p>
<pre><code class="language-shell">python chess.py       # Chess
python tic_tac_toe.py # Tic Tac Toe
python snake_game.py  # Snake Game
</code></pre>
