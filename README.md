# Reinforcement Learning Assignment – Cairo University

This repository contains the implementation of two reinforcement learning algorithms — **Value Iteration** and **Q-Learning** — applied to the FrozenLake-v1 environment from OpenAI Gym. The work was submitted as part of the AI424 course at Cairo University.

## 📄 Contents

- `FrozenLake v1 RL.ipynb`: Jupyter notebook with full implementation and explanations.
- `report.pdf`: A brief report explaining the algorithms, implementation approach, and results.
- `results/`: Folder containing output charts and images comparing the performance of both algorithms.

## 🧠 Algorithms Overview

### 🔷 Value Iteration
- Uses dynamic programming and the Bellman Optimality Equation.
- Iteratively updates the state-value function until convergence.
- Extracts the optimal policy from the final value function.

### 🔷 Q-Learning
- A model-free, off-policy algorithm.
- Learns the action-value function using an epsilon-greedy policy.
- Trains the agent through multiple episodes to build a Q-table.

## 📊 Evaluation Criteria

- **Success Rate**: How often the agent reaches the goal.
- **Convergence Speed**: Number of iterations (Value Iteration) vs episodes (Q-Learning) needed to learn a good policy.
- **Visual Comparison**: Output charts and tables show performance differences between both methods.

## 🧰 Technologies & Tools Used

- **Python 3**
- **Jupyter Notebook**
- **OpenAI Gym** – for the `FrozenLake-v1` environment
- **NumPy** – for numerical operations and matrix handling
- **Matplotlib** – for plotting results and comparisons


---

## 📊 Algorithms Summary

### 🔷 Value Iteration
- Iteratively computes the optimal value function using the Bellman Optimality Equation.
- Derives the optimal policy by selecting actions with the highest expected return.

### 🔷 Q-Learning
- Uses tabular Q-learning with an epsilon-greedy exploration strategy.
- Learns the action-value function directly through interaction with the environment.
- No knowledge of environment dynamics is required.

---

## 📈 Evaluation Criteria

- **Success Rate**: Number of successful episodes after learning.
- **Convergence Speed**: Number of iterations (Value Iteration) vs episodes (Q-Learning) required to reach a stable policy.
- **Visual Comparison**: Plots included in the `results/` folder.

---

## 📚 References

OpenAI Gym Documentation
Official documentation for Gym environments, including FrozenLake.
🔗 https://www.gymlibrary.dev/environments/toy_text/frozen_lake/

---

## ▶️ How to Run

1. Install the required libraries:
   ```bash
   pip install gym matplotlib numpy
