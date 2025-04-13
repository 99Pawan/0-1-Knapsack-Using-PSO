# 0/1 Knapsack Problem Using Particle Swarm Optimization (PSO)

This project explores the application of **Particle Swarm Optimization (PSO)** to solve the **0/1 Knapsack Problem**, comparing its performance with the classical **Dynamic Programming (DP)** approach.

## 🚀 Abstract

The 0/1 Knapsack Problem is a classic NP-hard combinatorial optimization challenge where a subset of items, each with a weight and value, must be chosen to maximize total value under a weight constraint. 

In this project, we implement:
- An **exact** method using **Dynamic Programming (DP)**.
- An **approximate**, metaheuristic method using **Binary PSO**, adapted with greedy initialization, repair mechanisms, and adaptive thresholds.

The PSO approach yields near-optimal solutions significantly faster for large input sizes, with average error mostly under **5%**, validating its practical value for scalability.

---

## 📋 Features

- ✅ Binary PSO tailored for discrete search space
- ✅ Greedy initialization with diversity perturbation
- ✅ Feasibility repair function for overweight solutions
- ✅ Dynamic inertia, cognitive & social coefficients
- ✅ Adaptive sigmoid thresholding
- ✅ Early stopping on stagnation
- ✅ Logarithmic scaling of swarm size and iteration count
- ✅ Error and runtime analysis against DP
- ✅ Visualization of performance using plots

---

## 🧠 Technologies Used

- **Python 3.8**
- **NumPy** — numerical computations
- **Matplotlib** — data visualization

---
