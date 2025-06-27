# 🧪 MLflow Experiment Tracking - Quickstart Guide

This guide summarizes how to integrate **MLflow** into an existing machine learning training script to enable experiment tracking, logging, and reproducibility.

> 📚 **Goal**: Set up basic MLflow tracking to log parameters, metrics, and trained models for future comparison and deployment.

---

## 🧠 Key Concepts

### 🔁 Experiments & Runs
- **Experiment**: A logical group of runs. Think of it as a collection of trials for solving a specific ML problem.
- **Run**: A single execution of model training (with specific data, hyperparameters, and code).

Each run logs:
- Parameters (e.g., alpha, l1_ratio)
- Metrics (e.g., RMSE)
- Artifacts (e.g., trained model)
- Metadata (e.g., run ID, experiment ID)

---

## 📦 Setup

### ✅ Prerequisite
Install MLflow in your conda environment:
```bash
conda activate <your-env>
pip install mlflow

# 🧪 MLflow UI: Visualizing and Comparing Experiments

Welcome! This guide provides a quick overview of how to use the **MLflow UI** to visualize and compare your machine learning experiments in an interactive, web-based interface.

---

## 🚀 Getting Started

To launch the MLflow UI:

1. **Activate your Conda environment** (if not already):

   ```bash
   conda activate <your-env-name>
