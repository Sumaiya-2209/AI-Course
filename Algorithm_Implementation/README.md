# Algorithm Implementation
## 1. Breadth-First Search (BFS)
### How it Works

BFS explores nodes level-by-level starting from a source. It uses a queue and marks visited nodes to avoid repeats.

### Applications
-Shortest path in unweighted graphs <br>
-Web crawling <br>
-Social network analysis <br>
-Garbage collection (mark phase) <br>

### Complexity
-Time: O(V + E) <br>
-Space: O(V) <br>

### Input / Output

<img width="332" height="237" alt="BFS" src="https://github.com/user-attachments/assets/4c340f0d-d28a-45ff-9ec2-2d9ef9ed8a80" />



## 2. Depth-First Search (DFS)
### How it Works

DFS explores as deep as possible along a branch before backtracking. Implemented with recursion or a stack.

### Applications
-Topological sorting <br>
-Detecting cycles <br>
-Maze solving <br>
-Pathfinding in implicit graphs <br>

### Complexity
-Time: O(V + E) <br>
-Space: O(V) (recursion stack) <br>

### Input / Output
<img width="343" height="240" alt="DFS" src="https://github.com/user-attachments/assets/7295ef87-dab5-4c12-9b5e-8db565703b22" />


## 3. Bidirectional Search
### How it Works

Runs two simultaneous searches — one from the start and one from the goal — and meets in the middle to reduce work.

### Applications
-Shortest path (when start & goal known) <br>
-Route planning in large graphs <br>
### Complexity

-Time: roughly O(b^(d/2) + b^(d/2)) vs O(b^d) for single-direction (b = branching factor, d = solution depth) <br>
-Space: O(b^(d/2)) <br>

### Input / Output

<img width="619" height="390" alt="Bidirectional" src="https://github.com/user-attachments/assets/e8b43419-8fb3-4f4c-bdd3-4c09d3d137f2" />


## 4. Depth-Limited Search (DLS)
### How it Works

A DFS variant with a fixed depth limit. If depth limit reached, the search stops along that branch.

### Applications

-Avoid infinite paths in cyclic or infinite-depth graphs <br>
-Controlled resource usage <br>

### Complexity

-Time: O(b^l) where l = depth limit <br>
-Space: O(l) <br>

### Input / Output

<img width="392" height="345" alt="DLS1" src="https://github.com/user-attachments/assets/dd2683d7-6004-4c25-b0f1-e6cfcc6de888" />


## 5. Iterative Deepening Depth-First Search (IDDFS)
### How it Works

Performs repeated DLS with increasing depth limits (0,1,2...) until solution found. Combines DFS space efficiency with BFS completeness.

### Applications
-When solution depth is unknown but memory is limited <br>
-Optimal finding in unweighted trees <br>

### Complexity

-Time: O(b^d) (slightly higher constant than DFS) <br>
-Space: O(d) <br>

### Input / Output
<img width="425" height="295" alt="IDS" src="https://github.com/user-attachments/assets/7374a397-3d86-4b39-9938-1a59a3b852df" />



## 6. Best-First Search
### How it Works

Explores nodes by a heuristic value (priority queue). Chooses node that appears most promising according to heuristic h(n).

### Applications
-Greedy pathfinding <br>
-Route planning with heuristic guidance <br>

### Complexity

-Time: depends on heuristic and branching factor (worst-case exponential) <br>
-Space: can be large (stores frontier) <br>

### Input / Output

<img width="412" height="626" alt="Bestfirst" src="https://github.com/user-attachments/assets/407dab91-f737-4492-8cac-448685d6f742" />


## 7. Beam Search
### How it Works

A breadth-limited heuristic search that keeps only the best k candidates at each level (beam width k).

### Applications

-NLP (sequence decoding) <br>
-Large search spaces where full frontier is too large <br>

### Complexity

-Time: O(b * k * d) roughly <br>
-Space: O(k)

### Input / Output

<img width="356" height="420" alt="Beamsearch" src="https://github.com/user-attachments/assets/6053c2c2-d667-4d5b-95a0-81c52a7ce5b7" />


## 8. A* Search
### How it Works

Uses f(n) = g(n) + h(n) where g is cost from start and h is heuristic to goal. If h is admissible, A* is optimal and complete.

### Applications

-Optimal pathfinding with costs (games, robotics) <br>
-Route planning <br>

### Complexity

-Time: exponential in worst case, depends on heuristic quality <br>
-Space: high (stores frontier) <br>

### Input / Output

<img width="348" height="507" alt="A_star" src="https://github.com/user-attachments/assets/a9fdf672-0abc-4944-acff-5fedb8456bd8" />

## 9. Minimax Algorithm
### How it Works

Adversarial search that assumes both players play optimally; maximizer chooses moves to maximize score, minimizer to minimize it. Explores game tree to terminal states or depth limit.

### Applications

-Two-player zero-sum games (chess, tic-tac-toe) <br>
-Game AI baseline <br>

### Complexity

-Time: O(b^d) where d = depth <br>
-Space: O(d) <br>

### Input / Output

<img width="544" height="247" alt="minmax" src="https://github.com/user-attachments/assets/cd89501e-09da-47d9-b9a5-301b5211b4f7" />


## 10. Alpha-Beta Pruning
### How it Works

Optimization of minimax that prunes branches that cannot affect final decision, using α (alpha) and β (beta) bounds.

### Applications

-Same as minimax but much faster in practice <br>
-Competitive game-playing agents

### Complexity

-Time: O(b^(d/2)) in best case, still O(b^d) worst-case <br>
-Space: O(d) <br>

### Input / Output

<img width="645" height="368" alt="AlphaBeta" src="https://github.com/user-attachments/assets/d1e11339-6461-4b79-be9f-c5570aadba6b" />


## How to use these notes

-Each images/*.png is a placeholder — replace with your own example diagrams. <br>
-Shorten or expand any section for your assignment needs. <br>

## References & Further Reading

-Standard textbooks: Artificial Intelligence: A Modern Approach (Russell & Norvig) <br>
-Online resources: algorithm visualizers, lecture notes
