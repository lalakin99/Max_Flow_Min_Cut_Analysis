# Max-Flow Min-Cut Analysis - Network Dynamics and Learning Lecture Project 1

## 📜 Project Overview
This repository contains my work for the first individual project in the "Network Dynamics and Learning" course at Politecnico di Torino (2023/2024). The project focuses on **network flow optimization problems**, including:
- Max-Flow Min-Cut problems.
- Bipartite Graphs and Perfect Matching.
- Network Flow Optimization in real-world contexts like highway networks.

---

## 🔍 Problem Description
The project explores several key problems in network dynamics:
1. **Max-Flow Min-Cut**: Analyze and determine:
   - Minimum aggregate capacity removal for no feasible flow.
   - Maximum aggregate capacity removal without affecting throughput.
   - Distribution of extra capacities to maximize throughput.
   
2. **Bipartite Graphs**:
   - Find perfect matchings.
   - Optimize assignments under capacity constraints.
   - Determine optimal book redistribution to maximize matches.

3. **Highway Network Optimization**:
   - Shortest path calculations.
   - Maximum flow between intersections.
   - Social optimum and Wardrop equilibrium flow analysis with toll implementation.

---

## 📂 Repository Contents
- **`HW1_Report.pdf`**: Full report detailing problem analysis, methods, and solutions.
- **`HW1_LalAkin.ipynb`**: Jupyter Notebook containing Python code for solving all problems.
  - Input datasets (e.g., graphs, flow matrices) used for experiments.

---

## 🛠️ Tools and Techniques
The following tools and libraries were used in this project:
- **Python**:
  - `networkx`: For graph representation and algorithms.
  - `cvxpy`: For optimization and equilibrium computations.
- **Jupyter Notebook**: For coding and presenting the results.
- **Matplotlib**: For plotting graphs and visualizing results.
- **LaTeX**: For writing the detailed report.

---

## 📊 Key Results
- Determined the max-flow min-cut relationship and optimal capacity allocation strategies.
- Achieved perfect matchings and optimized book assignments in bipartite graphs.
- Calculated social optimum and Wardrop equilibrium costs for a highway network:
  - **Social Optimum Cost**: 23,835.48
  - **Wardrop Equilibrium Cost**: 24,162.20
  - **Equilibrium with Tolls**: 23,835.48
