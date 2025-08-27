# 🚗 Reinforcement Learning Workshop – Car Racing Agent

## 📖 Workshop Overview

### Part 1: Introduction to Reinforcement Learning

* What is RL?
* Key Concepts:

  * Agent, Environment, States, Actions, Rewards
  * Policy, Value Function, Q-function
  * Exploration vs. Exploitation
  * Markov Decision Process (MDP)
* Types of RL Algorithms:

  * Value-based (Q-learning, DQN)
  * Policy-based (REINFORCE)
  * Actor-Critic
* Applications of RL:

  * Games (Atari, Go)
  * Robotics
  * Recommender Systems

### Part 2: Live Coding – Car Racing RL Agent

* Hands-on coding of a **Q-learning agent** in a grid world
* Visualizations of the agent’s learning process
* Experiments with:

  * Obstacles ❌
  * Hazards ☠️
  * Subgoals 🎯
  * Reward shaping & exploration strategies

---

## The Car Racing Environment

* **Agent**: 🚗 (Car)
* **Goal**: 🏁 (Finish line)
* **Road**: ⬜ (Free space)
* **Obstacles**: ❌ or ⬛ (Impassable walls)
* **Hazards**: ☠️ (Enterable but high penalty)
* **Subgoal**: 🎯 (Checkpoint before reaching final goal)

The agent learns to navigate from the start position to the finish line using **Q-learning**.

---

## Features in Code

* Grid-world simulation with visual console output
* Q-learning implementation with customizable parameters (`α`, `γ`, `ε`, episodes)
* Step-by-step training with Q-table inspection
* Testing policies (greedy vs. ε-greedy)

Variations of the environment:

* Obstacles and hazards
* Narrow path learning
* Multi-stage goals (subgoal + final goal)

---

## Getting Started

### Requirements

* Python 3.8+
* NumPy

```bash
pip install numpy
```

### Run the Workshop Code

```bash
python reinforcement_learning_workshop.py
```

You will see the grid environment printed in the console as the agent trains and tests different policies.

---

## Example Outputs

* Learned Q-table (values per state)
* Learned policy (best actions per state)
* Agent testing episodes (some succeed, some fail due to exploration)
* Final deterministic run showing the shortest path 🚗 → 🏁

---

Developed and presented by **Zahra Mousavi Ziabari**
as part of an **Intro to Reinforcement Learning** workshop.
