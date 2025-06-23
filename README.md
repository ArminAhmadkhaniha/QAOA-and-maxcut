# Solving MAX-Cut Problem with QAOA

This repository contains a report and accompanying code exploring the **MAX-Cut problem** and its approximate solution using the **Quantum Approximate Optimization Algorithm (QAOA)**.

## What is this project about?

The MAX-Cut problem is a classic challenge in **combinatorial optimization** where the goal is to divide the vertices of a graph into two sets to maximize the number of edges connecting them. It's an **NP-hard problem**, meaning it's computationally difficult to solve exactly for large graphs.

This project investigates how to tackle MAX-Cut by:

* Formulating it as a **Quadratic Unconstrained Binary Optimization (QUBO)** problem.
* Applying **QAOA**, a quantum algorithm that uses parameterized quantum circuits to find approximate solutions.
* Discussing the **adiabatic process** as a theoretical foundation for solving such problems on quantum computers.

## Get Started

The main report provides a comprehensive theoretical background, while the notebook demonstrates practical implementation.

### Key Content:

* **`report.pdf`**: The full report detailing the theory, problem formulation, and QAOA explanation.
* **`qaoamax.ipynb`**: A Python notebook with code examples for applying QAOA to MAX-Cut.

