## Problem Statement:
The assignment targets to implement A* search for 8-puzzle problem
Question:
In a general search algorithm, each state (n) maintains a function f(n) = g(n) + h(n)
where g(n) is the least cost from the source state to state n found so far and h(n) is the
estimated cost of the optimal path from state n to the goal state.
Implement a search algorithm for solving the 8-puzzle problem with the following
assumptions.
1. g(n) least cost from source state to current state so far.
2. Heuristics
a. h1(n) = 0.
b. h2(n) = number of tiles displaced from their destined position.
c. h3(n) = sum of the Manhattan distance of each tile from the goal position.
d. h4(n) = Devise a heuristics such that h(n) > h∗(n)
1. 2. Observe and verify that better heuristics expands lesser states.
Observe and verify that all the states expanded by better heuristics should also be
expanded by inferior heuristics.
3. Observe un-reachability and provide proof.
4. Observe and verify whether the monotone restriction is followed for the following
two Heuristics:
a. Monotone restriction: h(n) <= cost(n,m) + h(m)
b. Heuristic:
i. h2(n) = number of tiles displaced from their destined position.
ii. h3(n) = sum of the Manhattan distance of each tile from the goal
position.
5. Observe and verify that if the cost of the empty tile is added (considering the
empty tile as another tile) then monotonicity will be violated.

🧩 8-Puzzle Solver with A* Search Algorithm
🌟 **A Python implementation of the classic 8-puzzle problem solved using A* search with multiple heuristic functions.**

📝 Description
This project provides an efficient solution to the 8-puzzle problem using the A search algorithm* with four different heuristic functions. The program checks puzzle solvability, explores optimal paths, and compares heuristic performance.

🚀 Features
Four Heuristics:

h1: Zero heuristic (Uniform Cost Search)

h2: Misplaced tiles count

h3: Manhattan distance (optimal admissible heuristic)

h4: Custom non-admissible heuristic (1.5× Manhattan distance)

Solvability Check: Ensures only solvable puzzles are processed.

Path Reconstruction: Tracks and displays the full solution path.

Performance Metrics: Measures execution time and move counts.

📊 Results
The program demonstrates:

Fastest convergence with Manhattan distance (h3).

Comparison of heuristic efficiency in terms of time and path length.

Handling of unsolvable cases with immediate feedback.
