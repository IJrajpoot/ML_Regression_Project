# Mathematical Foundation for AI Project: Comparative Regression Analysis

An implementation and comparative analysis of core machine learning algorithms, including Ordinary Least Squares (OLS) Linear Regression, Singular Value Decomposition (SVD) for least squares and dimensionality reduction (PCA), and Gradient Descent optimization.

## Project Topic
Implementation of Least Squares Linear Regression, Singular Value Decomposition (SVD), and Gradient Descent Optimization.

## Overview
This project explores different methodologies for solving the least squares linear regression problem on a real-world dataset. We implement and compare three distinct approaches; Ordinary Least Squares (OLS) using the normal equation, a robust SVD-based solution, and Gradient Descent—while also applying Principal Component Analysis (PCA) via SVD for dimensionality reduction.

The goal is to analyze the performance, numerical stability, convergence behavior, and interpretability of each method.

| Detail | Value |
| :--- | :--- |
| **Course** | Mathematical Foundation for AI |
| **Due Date** | November 15, 2025 |
| **Dataset Used** | `sklearn.datasets.load_diabetes()` |

## Group Members
* Iqra Jawaid (K25-7620)
* Muhammad Abdullah Panhwar (K25-7638)

## 💾 Deliverables
The following files are contained in this repository:
1.  **`MFAI_Project.ipynb`**: The main Jupyter/Colab notebook containing all implemented code, outputs, and explanations for the analysis.
2.  **`MFAI_Report.pdf`**: A short (max 4 pages) report summarizing the dataset, methods, results, and conclusions.
3.  **`README.md`** (This file): Environment setup and instructions to run the notebook.

## ⚙️ Environment Requirements

This project is designed to be executed entirely within **Google Colab**. No local environment setup (like conda or venv) is required.

The notebook uses standard Python libraries that are pre-installed in the Colab environment:
* **`numpy`** (Numerical computation)
* **`matplotlib`** (Visualization)
* **`scikit-learn`** (Dataset loading and utilities)
* **`scipy`** (SVD and linear algebra utilities)

***

## Instructions to Run the Project

The entire project's code and analysis are contained within the **`project.ipynb`** (or `MFAI_Project.ipynb`) notebook.

### 1. Open in Google Colab 🔗

Click the link below to open the notebook directly in your browser:

* [**Open MFAI_Project.ipynb in Google Colab**]
    * Download the .ipynb file on your local machine
    * Open the file in Google Colab.

### 2. Execution

1.  Once the notebook is open in Colab, navigate to the menu.
2.  Select **Runtime > Run all**.

The code will execute the full sequence of data preparation, method implementations (OLS, SVD, GD, PCA), analysis, and required visualizations in a single run, ensuring **reproducibility**.

***

## Key Tasks Completed

The notebook and report cover the following required tasks:
* **Task 1: Dataset Preparation** (5%): Loading and preprocessing the Diabetes dataset.
* **Task 2: Ordinary Least Squares (OLS)** (20%): Implementation using the Normal Equation, error calculation, and discussion of failure conditions.
* **Task 3: SVD-Based Solution** (25%): Implementation using the pseudoinverse via SVD, comparison of stability, and discussion of benefits for ill-conditioned problems.
* **Task 4: Gradient Descent** (25%): Implementation of Batch Gradient Descent, experimentation with learning rates, and plotting the loss function vs. iterations.
* **Task 5: PCA and Dimensionality Reduction** (20%): Use SVD for PCA, projecting data onto top components, and analysis of the performance trade-off.

## Visualizations
All required visualizations (e.g., residual plots, loss curves, scree plots) are included within the notebook and explanations and discussion in the report.
