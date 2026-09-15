# Artificial Intelligence Lab Works

This repository contains lab exercises and assignments from an Artificial Intelligence course, organized into two main categories: **Machine Learning Foundations** and **Classical AI Search & Optimization Algorithms**.

---

## 📁 Classical AI Search & Optimization Algorithms

Covers foundational AI search, adversarial game-playing, and optimization algorithms.

| File | Description |
|---|---|
| `A_Star_Algorithm.py` | Implements the A* search algorithm to find the shortest path between two locations using a graph with heuristic values, reading input from a text file. |
| `genetic_algorithm.py` | Implements a genetic algorithm (population initialization, fitness evaluation, parent selection, crossover, mutation) to optimize a simple trading strategy (stop-loss, take-profit, trade size). |
| `alpha_beta_pruning.py` | Implements the Minimax algorithm with alpha-beta pruning, applied to a simulated chess strength-comparison scenario (Task 1) and a "mind control" decision-analysis variant (Task 2). |

## 📁 Machine Learning Foundations

Covers the core data science and machine learning pipeline — from understanding raw data to building and evaluating models.

| File | Description |
|---|---|
| `Exploratory_Data_Analysis.py` | Techniques for understanding a dataset before modeling: descriptive statistics, skewness, correlation analysis (Pearson/Spearman/Kendall), missing values, class imbalance checks, and visualizations (histograms, boxplots, heatmaps). |
| `Introduction_to_Data_Preprocessing_Tabular_Data_.py` | Preparing tabular data for ML: handling missing values, feature scaling (MinMax/Standard/Robust scalers), encoding categorical variables, feature engineering, and feature selection. |
| `Regression_and_Classification_GradientDescent.py` | Implements linear, polynomial, and logistic regression from scratch using symbolic differentiation (`sympy`) and gradient descent, then compares results with `scikit-learn`'s built-in implementations. |
| `Intro_to_Neural_Network.py` | Builds a neural network from scratch (forward/backward propagation, activation functions, loss functions, optimizers) and compares it with a TensorFlow/Keras implementation on MNIST and Boston Housing datasets. |
| `Model_Evaluation.py` | Techniques and metrics for evaluating trained ML models. |

---

---

## Notes

- All original code, variable names, function signatures, and structure are preserved exactly as submitted for coursework — only file/folder organization and documentation have been added.
