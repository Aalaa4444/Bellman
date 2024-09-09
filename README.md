# Bellman
This repository provides a Python implementation of the Bellman Equation for solving a 3x4 Grid World problem. The Bellman Equation is a fundamental concept in Reinforcement Learning, used to determine the optimal policy and value function for a given state.

## Problem Overview
In the Grid World environment, an agent starts in a grid and must reach a goal while avoiding obstacles. The environment is deterministic, meaning each action leads to a predictable outcome. The agent's task is to maximize the expected cumulative reward by selecting the best possible actions based on the Bellman equation.

## Grid World Layout
* Grid Size: 3x4
* Start State: (2, 0)
* Goal State: (0, 3)
* Obstacle: The agent cannot move through certain grid cells (e.g., (1, 1)).
* Rewards:
  * +1 for reaching the goal.
  * -1 for falling into a trap.
  * 0 for all other cells.
