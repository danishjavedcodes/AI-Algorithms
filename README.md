# AI Algorithms — Basic Algorithms for Learning

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

A **beginner-friendly collection of basic AI and machine learning algorithms** for learning. This repository contains hands-on **Jupyter notebooks** in Python that implement classic search techniques, game-playing AI, probabilistic models, evolutionary algorithms, and introductory ML — ideal for students, self-learners, and anyone building a foundation in **artificial intelligence**.

> **Purpose:** Basic algorithms for learning — not production libraries. Run each notebook cell-by-cell to understand how each algorithm works under the hood.

---

## Table of Contents

- [What You Will Learn](#what-you-will-learn)
- [Topics Covered](#topics-covered)
- [Repository Structure](#repository-structure)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Notebooks Guide](#notebooks-guide)
- [Contributing](#contributing)
- [Author](#author)

---

## What You Will Learn

This repo helps you learn foundational **AI algorithms** through practical Python code:

- **Graph search** — BFS, DFS, UCS, GBFS, and A* pathfinding
- **Local search** — Hill climbing and simulated annealing
- **Constraint satisfaction** — N-Queens (backtracking and genetic algorithms)
- **Adversarial search** — Minimax for Tic-Tac-Toe
- **Probabilistic AI** — Hidden Markov Models (HMM)
- **Machine learning** — Supervised and unsupervised learning with scikit-learn
- **Neural networks** — From-scratch forward pass and sigmoid activation

---

## Topics Covered

| Category | Algorithms & Concepts |
|----------|----------------------|
| **Uninformed Search** | Breadth-First Search (BFS), Depth-First Search (DFS), Uniform Cost Search (UCS) |
| **Informed Search** | Greedy Best-First Search (GBFS), A* Algorithm |
| **Local Search** | Hill Climbing, Simulated Annealing |
| **CSP / Optimization** | N-Queens Problem, Genetic Algorithms |
| **Game AI** | Minimax Algorithm, Tic-Tac-Toe AI |
| **Probabilistic Models** | Hidden Markov Model (HMM), Viterbi-style inference |
| **Machine Learning** | Decision Trees, Random Forest, Naive Bayes, K-Means, PCA |
| **Neural Networks** | Perceptron-style layers, weights, biases, sigmoid activation |

---

## Repository Structure

```
AI-Algorithms/
├── bfs_and_dfs.ipynb              # BFS & DFS graph traversal
├── UCS.ipynb                      # Uniform Cost Search
├── GBFS.ipynb                     # Greedy Best-First Search
├── A_star_algorithm.ipynb         # A* pathfinding
├── Local Searching Algorithms  .ipynb   # Hill climbing & simulated annealing
├── n-queen_problem.ipynb        # N-Queens (backtracking)
├── genetic_algorithm .ipynb       # Genetic algorithm basics
├── Genetic Algorithm implementation on N-Queen.ipynb
├── minimax_tic_tac_toe.ipynb      # Minimax game AI
├── HMM.ipynb                      # Hidden Markov Models
├── supervised ML with sklearn.ipynb
├── Unsupervised_Learning.ipynb
├── Neural Networks.ipynb
├── titanic.csv                    # Sample dataset (Titanic)
└── README.md
```

---

## Prerequisites

- **Python 3.8+**
- **Jupyter Notebook** or **JupyterLab**
- Familiarity with basic Python and NumPy is helpful

### Install Dependencies

```bash
pip install jupyter numpy pandas matplotlib scikit-learn
```

---

## Getting Started

1. **Clone the repository**

   ```bash
   git clone https://github.com/danishjavedcodes/AI-Algorithms.git
   cd AI-Algorithms
   ```

2. **Launch Jupyter**

   ```bash
   jupyter notebook
   ```

3. **Open a notebook** from the list above and run cells in order.

4. **Experiment** — change graph weights, heuristics, board sizes, or hyperparameters to see how each algorithm behaves.

---

## Notebooks Guide

| Notebook | Description |
|----------|-------------|
| `bfs_and_dfs.ipynb` | Implement and compare BFS and DFS on a sample graph |
| `UCS.ipynb` | Find lowest-cost paths with Uniform Cost Search |
| `GBFS.ipynb` | Greedy Best-First Search on Romania-style map graphs |
| `A_star_algorithm.ipynb` | A* search with admissible heuristics |
| `Local Searching Algorithms  .ipynb` | Hill climbing and simulated annealing for optimization |
| `n-queen_problem.ipynb` | Solve N-Queens using backtracking |
| `genetic_algorithm .ipynb` | Core GA: selection, crossover, mutation |
| `Genetic Algorithm implementation on N-Queen.ipynb` | Apply GA to the N-Queens problem |
| `minimax_tic_tac_toe.ipynb` | Play Tic-Tac-Toe against a minimax AI |
| `HMM.ipynb` | Hidden Markov Model — states, transitions, observations |
| `supervised ML with sklearn.ipynb` | Classification on Titanic data (Decision Tree, RF, Naive Bayes) |
| `Unsupervised_Learning.ipynb` | K-Means clustering and PCA on Titanic data |
| `Neural Networks.ipynb` | Build a simple neural network forward pass from scratch |

---

## Keywords

`artificial intelligence`, `AI algorithms`, `machine learning`, `search algorithms`, `A star`, `BFS`, `DFS`, `genetic algorithm`, `minimax`, `hidden markov model`, `neural networks`, `scikit-learn`, `python`, `jupyter notebook`, `learn AI`, `basic algorithms`, `beginner AI`

---

## Contributing

Contributions are welcome. If you find a bug, want to add a notebook, or improve explanations:

1. Fork the repository
2. Create a feature branch (`git checkout -b improve/readme-or-notebook`)
3. Commit your changes
4. Open a Pull Request

---

## Author

**[danishjavedcodes](https://github.com/danishjavedcodes)**

- GitHub: [https://github.com/danishjavedcodes/AI-Algorithms](https://github.com/danishjavedcodes/AI-Algorithms)

---

## License

This project is open source and intended for **educational use**. Feel free to use, study, and share these notebooks for learning basic AI algorithms.
