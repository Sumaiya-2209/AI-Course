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

![Breadth-First Search (BFS)](https://github.com/user-attachments/assets/88243b8a-83a9-46b0-a3d7-fad43806764b)


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

![Depth-First-Search](https://github.com/user-attachments/assets/92eeb2e1-f307-4ba0-92eb-72136f942ebc)

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

![Bidirectional Search](https://github.com/user-attachments/assets/59db6b83-19fd-40c3-9365-e65e12149393)


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

![depth_limited_search](https://github.com/user-attachments/assets/b86a3f3a-61eb-4f36-aad2-2fc2322d97d1)


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

![Iterative Deepening Depth-First Search (IDDFS)](https://github.com/user-attachments/assets/027a0a81-a590-44b0-96da-09777940dd9d)


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

![Best-First Search](https://github.com/user-attachments/assets/2083d7eb-b9fc-4724-a662-07c5875679ed)


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

![Beam Search](https://github.com/user-attachments/assets/bfbd38fc-f29c-469d-9bb7-f35755d7f53d)


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

<img width="559" height="669" alt="a-star" src="https://github.com/user-attachments/assets/9e6b01fb-a000-44bc-a685-c0894851929a" />

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

<img width="500" height="447" alt="Minimax Algorithm" src="https://github.com/user-attachments/assets/3880021c-4b9e-4377-a908-29672edc1ffd" />


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

![Alpha-Beta Pruning](https://github.com/user-attachments/assets/e3f07165-638f-485f-8296-63f296ec5fae)


## How to use these notes

-Each images/*.png is a placeholder — replace with your own example diagrams. <br>
-Shorten or expand any section for your assignment needs. <br>

## References & Further Reading

-Standard textbooks: Artificial Intelligence: A Modern Approach (Russell & Norvig) <br>
-Online resources: algorithm visualizers, lecture notes
