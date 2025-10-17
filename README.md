# DA5401 A6 – Imputation via Regression for Missing Data

## Overview
This repository contains the complete implementation and report for **DA5401 Assignment 6 – Imputation via Regression for Missing Data**.

The project explores how different missing-value imputation techniques influence the performance of a **credit default prediction model** using the **UCI Credit Card Default Clients Dataset**.  
The focus is to compare simple, linear, and non-linear imputation methods, evaluate their effect on classification results, and draw conclusions about which approach is most effective.

---

## Objective
Missing data often occur in real-world financial datasets, preventing direct model training.  
This project simulates such scenarios by **artificially introducing Missing At Random (MAR)** values and then comparing several strategies to handle them:

1. **Simple Median Imputation (Model A)**  
2. **Linear Regression Imputation (Model B)**  
3. **Non-Linear KNN Regression Imputation (Model C)**  
4. **Listwise Deletion (Model D)**  

A **Logistic Regression** model is then trained on each version of the dataset to measure how each imputation method impacts performance.

---

## Libraries and Dependencies

All dependencies are standard Python data science libraries.

## How to Run the Notebook

## How to run
1. Place `UCI_Credit_Card.csv` in the same folder as the notebook , download it from `https://www.kaggle.com/datasets/uciml/default-of-credit-card-clients-dataset`.
2. Open `DA5401 Assignment #6.ipynb` in Jupyter Notebook or JupyterLab.
3. Run all cells in order. Plots and evaluation results will be displayed inline.



### Requirements
```bash
python>=3.8
pandas>=2.0.0
numpy>=1.24.0
scikit-learn>=1.3.0
matplotlib>=3.8.0
seaborn>=0.13.0
jupyter>=1.0.0



