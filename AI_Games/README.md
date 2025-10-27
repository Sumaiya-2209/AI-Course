<section>
  <h2>🧠 Overview</h2>
  <p>This project demonstrates core AI search algorithms applied to games. Key concepts used across the games:</p>
  <ul>
    <li>Minimax Algorithm</li>
    <li>Alpha-Beta Pruning</li>
    <li>Heuristic Evaluation</li>
    <li>Depth-Limited Search</li>
  </ul>
  <p>Each game follows the same interface layout and logic flow and includes a GUI (tkinter or pygame).</p>
</section>

<section>
  <h2>🎯 Game 1 — Chess</h2>
  <p><strong>Description:</strong> A simplified Chess AI that predicts the next move by searching possible future positions and evaluating board states.</p>
  <p><strong>Algorithms & Concepts:</strong></p>
  <ul>
    <li>Minimax</li>
    <li>Alpha-Beta Pruning</li>
    <li>Depth-limited search</li>
    <li>Piece-value heuristic evaluation</li>
  </ul>
  <p><strong>How it works:</strong> AI generates legal moves, evaluates board using a scoring function, and picks the best move via Minimax. Alpha-Beta pruning trims the search tree.</p>
</section>

<section>
  <h2>🎯 Game 2 — Connect Four</h2>
  <p><strong>Description:</strong> Classic 7×6 Connect Four. AI analyzes column drops to block or win.</p>
  <p><strong>Algorithms & Concepts:</strong></p>
  <ul>
    <li>Minimax with depth limit</li>
    <li>Alpha-Beta Pruning</li>
    <li>Heuristic evaluation based on connected discs and threats</li>
  </ul>
  <p><strong>How it works:</strong> AI simulates column drops, scores moves with heuristics, and selects the best using Minimax + Alpha-Beta.</p>
</section>

<section>
  <h2>🎯 Game 3 — Tic Tac Toe</h2>
  <p><strong>Description:</strong> 3×3 Tic Tac Toe where the AI plays optimally and never loses.</p>
  <p><strong>Algorithms & Concepts:</strong></p>
  <ul>
    <li>Complete Minimax search</li>
    <li>Alpha-Beta Pruning</li>
  </ul>
  <p><strong>How it works:</strong> Board is a 3×3 matrix. AI recursively simulates moves and chooses the optimal one with Minimax; Alpha-Beta reduces node visits.</p>
</section>

<section>
  <h2>🧰 Installation</h2>
  <p>Quick start:</p>
  <pre><code># Clone the repository

<section>
  <h2>📂 Project Structure (example)</h2>
  <ul>
    <li><span class="pill">/chess</span> — Chess game code & AI</li>
    <li><span class="pill">/connect4</span> — Connect Four implementation</li>
    <li><span class="pill">/tictactoe</span> — Tic Tac Toe implementation</li>
    <li><span class="pill">README.md</span> — This file</li>
  </ul>
</section>

<section>
  <h2>🛠️ Implementation Notes</h2>
  <ul>
    <li>Heuristic functions evaluate piece values, mobility, control of center (Chess), and connection strengths (Connect Four).</li>
    <li>Depth limits are used to bound search time for Chess & Connect Four; Tic Tac Toe uses full search.</li>
    <li>Alpha-Beta pruning is implemented to optimize search performance.</li>
  </ul>
</section>

<section>
  <h2>🤝 Contributing</h2>
  <p>PRs welcome. If you add features (better heuristics, move ordering, GUI polish), please include tests and update documentation.</p>
</section>

<footer>
  <p>Built with ❤️ for learning AI game algorithms. — Keep experimenting and tune heuristics to level up the bots.</p>
</footer>
