# Economic & Nutritional Data Analysis: Inflation Modeling with PCA

## Project Overview
This project combines **Linear Algebra** and **Data Science** techniques to analyze the evolution of food prices in Argentina (Inflation) and classify products based on their nutritional profile. 

Developed as a Capstone Project for *Cálculo Numérico / Álgebra Lineal Computacional* at **Universidad de Buenos Aires (UBA)**.

## Key Objectives
1.  **Inflation Modeling:** Calculate the monthly inflation rate for specific nutrients (Proteins, Carbs, Fats) using **Least Squares Regression**.
2.  **Nutritional Clustering:** Apply **PCA (Principal Component Analysis)** from scratch to group foods with similar nutritional compositions.
3.  **Diet Optimization:** Simulate dietary adjustments to meet WHO (World Health Organization) standards under budget constraints.

## Tech Stack & Math
* **Language:** Python
* **Linear Algebra:** `NumPy` (Eigenvalues/Eigenvectors for PCA, Matrix Operations).
* **Data Engineering:** `Pandas`, `Inline SQL` (Complex Joins and Data Cleaning).
* **Visualization:** `Matplotlib` (3D Scatter Plots), `Seaborn`.

## Methodological Highlights
* **PCA Implementation:** Instead of using standard libraries, PCA was implemented mathematically by calculating the **Covariance Matrix** and diagonalizing it to find the Principal Components.
* **Least Squares (Cuadrados Mínimos):** Formulated the inflation problem as a system of linear equations $Ax = b$ to find the optimal slope (price increase velocity).

## Key Findings
* **Inflation Dynamics:** Proteins showed the highest price increase velocity compared to Carbohydrates and Fats during the analyzed period.
* **Clustering:** The 3D PCA projection successfully separated foods into distinct clusters (e.g., "High Sugar", "Oily/Fats", "Carb-heavy"), validating the nutritional variance.

## Files
* `Inflation_Nutritional_PCA_Analysis.ipynb`: Main notebook containing the mathematical implementation, SQL queries, and 3D visualizations.

---
*Project by Delfina Stabile - Data Science Student at UBA*
