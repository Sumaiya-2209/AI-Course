# 1. Breadth-First Search (BFS)
## How it Works

BFS explores nodes level-by-level starting from a source. It uses a queue and marks visited nodes to avoid repeats.

## Applications
-Shortest path in unweighted graphs
-Web crawling
-Social network analysis
-Garbage collection (mark phase)

## Complexity
-Time: O(V + E)
-Space: O(V)

## Input / Output

![Breadth-First Search (BFS)](https://github.com/user-attachments/assets/88243b8a-83a9-46b0-a3d7-fad43806764b)


2. Depth-First Search (DFS)
How it Works

DFS explores as deep as possible along a branch before backtracking. Implemented with recursion or a stack.

Applications

Topological sorting

Detecting cycles

Maze solving

Pathfinding in implicit graphs

Complexity

Time: O(V + E)

Space: O(V) (recursion stack)

Input / Output

images/dfs_example.png

3. Bidirectional Search
How it Works

Runs two simultaneous searches — one from the start and one from the goal — and meets in the middle to reduce work.

Applications

Shortest path (when start & goal known)

Route planning in large graphs

Complexity

Time: roughly O(b^(d/2) + b^(d/2)) vs O(b^d) for single-direction (b = branching factor, d = solution depth)

Space: O(b^(d/2))

Input / Output

images/bidirectional_example.png

4. Depth-Limited Search (DLS)
How it Works

A DFS variant with a fixed depth limit. If depth limit reached, the search stops along that branch.

Applications

Avoid infinite paths in cyclic or infinite-depth graphs

Controlled resource usage

Complexity

Time: O(b^l) where l = depth limit

Space: O(l)

Input / Output

images/depth_limited_example.png

5. Iterative Deepening Depth-First Search (IDDFS)
How it Works

Performs repeated DLS with increasing depth limits (0,1,2...) until solution found. Combines DFS space efficiency with BFS completeness.

Applications

When solution depth is unknown but memory is limited

Optimal finding in unweighted trees

Complexity

Time: O(b^d) (slightly higher constant than DFS)

Space: O(d)

Input / Output

images/iddfs_example.png

6. Best-First Search
How it Works

Explores nodes by a heuristic value (priority queue). Chooses node that appears most promising according to heuristic h(n).

Applications

Greedy pathfinding

Route planning with heuristic guidance

Complexity

Time: depends on heuristic and branching factor (worst-case exponential)

Space: can be large (stores frontier)

Input / Output

images/best_first_example.png

7. Hill-Climbing Search
How it Works

Local search that iteratively moves to the neighbor with a better heuristic value until no improvement is possible (a peak).

Applications

Optimization problems

When solution landscape is smooth and local improvements help

Complexity

Time: depends on landscape and stopping criteria

Space: O(1)–O(n) depending on implementation

Notes

Can get stuck in local maxima; random restarts or simulated annealing help.

Input / Output

images/hill_climbing_example.png

8. Beam Search
How it Works

A breadth-limited heuristic search that keeps only the best k candidates at each level (beam width k).

Applications

NLP (sequence decoding)

Large search spaces where full frontier is too large

Complexity

Time: O(b * k * d) roughly

Space: O(k)

Input / Output

images/beam_search_example.png

9. A* Search
How it Works

Uses f(n) = g(n) + h(n) where g is cost from start and h is heuristic to goal. If h is admissible, A* is optimal and complete.

Applications

Optimal pathfinding with costs (games, robotics)

Route planning

Complexity

Time: exponential in worst case, depends on heuristic quality

Space: high (stores frontier)

Input / Output

images/a_star_example.png

10. Minimax Algorithm
How it Works

Adversarial search that assumes both players play optimally; maximizer chooses moves to maximize score, minimizer to minimize it. Explores game tree to terminal states or depth limit.

Applications

Two-player zero-sum games (chess, tic-tac-toe)

Game AI baseline

Complexity

Time: O(b^d) where d = depth

Space: O(d)

Input / Output

images/minimax_example.png

11. Alpha-Beta Pruning
How it Works

Optimization of minimax that prunes branches that cannot affect final decision, using α (alpha) and β (beta) bounds.

Applications

Same as minimax but much faster in practice

Competitive game-playing agents

Complexity

Time: O(b^(d/2)) in best case, still O(b^d) worst-case

Space: O(d)

Input / Output

images/alpha_beta_example.png

How to use these notes

Each images/*.png is a placeholder — replace with your own example diagrams.

Shorten or expand any section for your assignment needs.

References & Further Reading

Standard textbooks: Artificial Intelligence: A Modern Approach (Russell & Norvig)

Online resources: algorithm visualizers, lecture notes
