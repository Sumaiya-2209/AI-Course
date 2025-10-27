<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AI Game Collection (Python)</title>
</head>
<body>
    <h1>🎮 AI Game Collection (Python)</h1>
    <p>A collection of three classic <strong>AI-powered games</strong> built in Python, featuring <strong>Chess</strong>, <strong>Tic Tac Toe</strong>, and <strong>Snake Game</strong>. Each game uses <strong>AI algorithms</strong> like <strong>Minimax, Alpha-Beta Pruning, and Heuristic Evaluation</strong> for intelligent decision-making.</p>

    <h2>🧠 Overview</h2>
    <p>This project demonstrates <strong>Artificial Intelligence search algorithms</strong> in game development. The key AI techniques implemented include:</p>
    <ul class="algorithms">
        <li><strong>Minimax Algorithm</strong> – Recursive decision-making for optimal moves.</li>
        <li><strong>Alpha-Beta Pruning</strong> – Optimizes Minimax by skipping unnecessary branches.</li>
        <li><strong>Heuristic Evaluation</strong> – Scores board positions for better AI decisions.</li>
        <li><strong>Depth-Limited Search</strong> – Prevents excessive computation in complex games.</li>
    </ul>
    <p>Each game has a <strong>simple GUI</strong> (using <code>tkinter</code> or <code>pygame</code>) with a consistent interface.</p>

    <h2>🎯 Games Included</h2>

    <h3>1️⃣ Chess (AI vs Player)</h3>
    <p><strong>Description:</strong><br>
    A <strong>simplified Chess AI</strong> that predicts the best move using <strong>Minimax + Alpha-Beta Pruning</strong>. The AI evaluates possible future board states to make intelligent decisions.</p>

    <p><strong>AI Algorithms Used:</strong></p>
    <ul class="features">
        <li>Minimax Algorithm</li>
        <li>Alpha-Beta Pruning</li>
        <li>Depth-Limited Search</li>
        <li>Piece Value Evaluation Function</li>
    </ul>

    <p><strong>How It Works:</strong></p>
    <ol>
        <li>AI generates all <strong>legal moves</strong>.</li>
        <li>Evaluates the board using a <strong>scoring function</strong> (based on piece values & positions).</li>
        <li>Uses <strong>Minimax</strong> to select the <strong>optimal move</strong>.</li>
        <li><strong>Alpha-Beta Pruning</strong> reduces unnecessary computations.</li>
    </ol>

    <p><strong>Features:</strong></p>
    <ul class="features">
        <li>Legal move validation</li>
        <li>AI difficulty adjustment (depth limit)</li>
        <li>Simple GUI (tkinter/pygame)</li>
    </ul>

    <h3>2️⃣ Tic Tac Toe (Unbeatable AI)</h3>
    <p><strong>Description:</strong><br>
    A <strong>3×3 grid game</strong> where the player competes against an <strong>AI that never loses</strong>. The AI uses <strong>Minimax with Alpha-Beta Pruning</strong> to always make the best move.</p>

    <p><strong>AI Algorithms Used:</strong></p>
    <ul class="features">
        <li>Minimax Algorithm (evaluates all possible moves)</li>
        <li>Alpha-Beta Pruning (optimizes search)</li>
    </ul>

    <p><strong>How It Works:</strong></p>
    <ol>
        <li>The game board is represented as a <strong>3×3 matrix</strong>.</li>
        <li>AI <strong>simulates all possible moves recursively</strong>.</li>
        <li>Uses <strong>Minimax</strong> to choose the move that <strong>maximizes its winning chance</strong>.</li>
        <li><strong>Alpha-Beta Pruning</strong> reduces the number of evaluated nodes.</li>
    </ol>

    <p><strong>Features:</strong></p>
    <ul class="features">
        <li>Unbeatable AI (always wins or forces a draw)</li>
        <li>Simple GUI (tkinter)</li>
        <li>Player vs AI mode</li>
    </ul>

    <h3>3️⃣ Snake Game (AI Pathfinding)</h3>
    <p><strong>Description:</strong><br>
    A <strong>classic Snake Game</strong> where the AI snake <strong>automatically navigates</strong> to eat food while avoiding collisions. Uses <strong>pathfinding algorithms</strong> (like <strong>BFS or A*</strong>).</p>

    <p><strong>AI Algorithms Used:</strong></p>
    <ul class="features">
        <li>Breadth-First Search (BFS) – Finds the shortest path to food.</li>
        <li>A* Algorithm (optional) – Optimized pathfinding.</li>
        <li>Collision Avoidance – Prevents self-collision.</li>
    </ul>

    <p><strong>How It Works:</strong></p>
    <ol>
        <li>The AI <strong>scans the board for food</strong>.</li>
        <li>Uses <strong>BFS/A*</strong> to find the <strong>shortest safe path</strong>.</li>
        <li>Moves the snake <strong>automatically</strong> while avoiding walls & itself.</li>
        <li><strong>Grows longer</strong> when eating food.</li>
    </ol>

    <p><strong>Features:</strong></p>
    <ul class="features">
        <li>AI-controlled snake (no manual input needed)</li>
        <li>Score tracking</li>
        <li>Simple GUI (pygame)</li>
    </ul>

    <h2>🛠 Installation & Setup</h2>
    <h3>Prerequisites</h3>
    <ul>
        <li>Python 3.x</li>
        <li>Required libraries:</li>
    </ul>
    <pre><code>pip install pygame numpy</code></pre>

    <h3>How to Run</h3>
    <ol>
        <li>Clone the repository:</li>
    </ol>
    <pre><code>git clone https://github.com/yourusername/ai-game-collection.git
cd ai-game-collection</code></pre>
    <ol start="2">
        <li>Run any game:</li>
    </ol>
    <pre><code>python chess.py       # Chess
python tic_tac_toe.py # Tic Tac Toe
python snake_game.py  # Snake Game</code></pre>
</body>
</html>
