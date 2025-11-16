# CSE 572 – Data Mining Homework 3

This repository contains implementations for **Homework 3** of *CSE 572 – Data Mining*. 

---

## Task 1 – K-Means Clustering

- Implemented K-Means from scratch (no external ML libraries).  
- Distance metrics:  
  - **Euclidean distance**  
  - **1 – Cosine similarity**  
  - **1 – Generalized Jaccard similarity**  
- Compared **SSE**, **accuracy**, and **convergence speed** across metrics.  
- Implemented three **stopping criteria**:  
  1. No change in centroid position  
  2. SSE increases  
  3. Maximum iteration limit  
- Output: detailed results for Q1 – Q5.

---

## Task 2 – Recommender Systems

- Built models using the **Surprise** library:
  - **User-based Collaborative Filtering**
  - **Item-based Collaborative Filtering**
  - **Probabilistic Matrix Factorization (PMF/SVD)**
- Evaluated under **5-fold cross-validation** using **MAE** and **RMSE**.
- Compared effects of:
  - Similarity metrics (Cosine, MSD, Pearson)
  - Number of neighbors (K)
- Plotted RMSE vs K to identify optimal neighbor sizes.


Answers to all questions listed in the HW3 pdf are included in the respective ipynb files.
