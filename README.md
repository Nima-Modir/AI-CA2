# Genetic Algorithms and Game Search

## Part 1: Genetic Algorithms
This section involves implementing a genetic algorithm to solve a given equation-based problem.

### Key Tasks:
#### Problem Setup:

You are given an equation with operands and operators (e.g., +, -, *, /).
The goal is to use a genetic algorithm to find the optimal set of values that satisfy the equation.
#### Chromosome Representation:

Each chromosome is represented as a sequence of genes, where genes are operands or operators.
#### Crossover and Mutation:

Implement both crossover and mutation operators to evolve the population.
Perform crossover by combining genes from two parent chromosomes.
Apply mutation by changing genes randomly to explore the search space.
#### Selection and Fitness:

Use fitness functions to evaluate how close a chromosome is to solving the equation.
Select the best-performing chromosomes to pass their genes to the next generation.
#### Expected Output:

The algorithm should output the optimal chromosome (set of values) that solves the equation.
The implementation must be efficient in terms of time and resources.

## Part 2: Game Search using Minimax Algorithm
This part of the project involves implementing the Minimax algorithm to solve a game search problem, specifically using the Minimax with Alpha-Beta Pruning technique.

### Key Tasks:
#### Game Implementation:

Simulate a game environment where two players take turns.
Implement the Minimax algorithm to determine the best move for a player based on the current game state.
#### Alpha-Beta Pruning:

Optimize the Minimax algorithm using Alpha-Beta pruning to cut off branches in the search tree that don’t need to be explored.
#### Heuristic Function:

Design an appropriate heuristic function to evaluate game states during the search process.
#### GUI Integration:

Implement a simple graphical interface (optional) to visualize the game progress and decisions made by the Minimax algorithm.
#### Expected Output:

The algorithm should output the best moves for each player, showing how the game progresses based on the Minimax decisions.
The depth of the search and the number of nodes explored should also be reported.
