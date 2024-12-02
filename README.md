# Metaheuristic Algorithm Comparison: PSO vs Hill Climbing  

This repository contains a Python Jupyter Notebook comparing two popular metaheuristic algorithms: **Particle Swarm Optimization (PSO)** and **Hill Climbing**. The comparison focuses on optimizing two benchmark mathematical functions: **Rastrigin** and **Sum of Squares**.

## Overview  
Metaheuristic algorithms are widely used in optimization problems where finding an exact solution is computationally expensive or infeasible. This project compares the performance of PSO and Hill Climbing in solving two non-convex mathematical optimization problems.  

### Functions Explored  
1. **Rastrigin Function**  
   - A non-convex function characterized by its large search space and multiple local minima.
   - \( f(x) = A \cdot n + \sum_{i=1}^n \left[ x_i^2 - A \cdot \cos(2\pi x_i) \right] \), where \( A = 10 \).

2. **Sum of Squares Function**  
   - A simpler function often used as a baseline for optimization algorithms.
   - \( f(x) = \sum_{i=1}^n i \cdot x_i^2 \).

## Notebook Contents  
The Python Notebook includes:
- Implementation of **Particle Swarm Optimization (PSO)** and **Hill Climbing**.
- Definitions of the Rastrigin and Sum of Squares functions.
- Comparison of optimization performance based on:
  - Convergence rate.
  - Best-found solution.
  - Computation time.

