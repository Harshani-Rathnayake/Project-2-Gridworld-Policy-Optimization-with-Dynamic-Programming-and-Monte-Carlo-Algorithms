# Project 2: Gridworld Policy Learning with Dynamic Programming and Monte Carlo Algorithms 

## Overview:

This project explores policy evaluation and optimization methods in a simple **5×5 Gridworld** reinforcement learning environment.  
The assignment is divided into two parts:

* **Part 1:** Estimation of state value functions and finding optimal policies using:
  - Bellman equations (explicit solution and optimality)
  - Iterative Policy Evaluation
  - Policy Iteration
  - Value Iteration

* **Part 2:** Policy learning in a modified episodic gridworld (with terminal states) using:
  - Monte Carlo methods with exploring starts
  - Monte Carlo methods with ε-soft policies
  - Off-policy learning using importance sampling

The goal is to analyze and compare these methods based on the learned value functions and policies.


## Repository Contents:

- `Project 2: Gridworld_Policy_Optimization_DP_and_MC.ipynb`: Main Jupyter notebook containing code implementations, results, and visualizations.
- `Report.pdf`: Formal report including detailed plots, tables, and analysis of the methods.
- `README.md`: Project overview and instructions (this file).

## How to Run the Code:

### Option 1: Run on Google Colab (Recommended)
1. Click the notebook file: `Project 2: Gridworld_Policy_Optimization_DP_and_MC.ipynb`  
2. At the top of the page, click Open in Colab 
3. Go to Runtime > Run all to execute all cells sequentially  

### Option 2: Run Locally with Python 3
1. Ensure Python 3 and Jupyter Notebook are installed on your system  
2. Download `Gridworld Policy Optimization.ipynb`  
3. Launch Jupyter Notebook and open the downloaded notebook  
4. Execute all cells by selecting Kernel > Restart & Run All


## Requirements:

The project relies on the following Python libraries:

- `numpy`
- `matplotlib`
- `seaborn`
- `random`
  
These are typically pre-installed in most Jupyter and Colab environments.

## Results

- Computed state value functions under both uniform random and optimal policies in the Gridworld.
- Visualizations of optimal policies derived via value iteration and policy iteration.
- Analysis of convergence and consistency between dynamic programming approaches.
- Monte Carlo method estimates for state values and policies using on-policy (exploring starts, ε-soft) and off-policy (importance sampling) techniques.
- Insights and comparisons highlighting the Bellman Optimality Equation and challenges of exploration-exploitation trade-offs.
