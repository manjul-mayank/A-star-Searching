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
