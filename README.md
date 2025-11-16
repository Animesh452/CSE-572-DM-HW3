# CSE 572 – Data Mining Homework 3

This repository contains implementations for **Homework 3** of *CSE 572 – Data Mining*.  
It includes both algorithmic analysis (Task 1) and recommender system modeling (Task 2).

---

## Task 1 – K-Means Clustering (Algorithmic Analysis)

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
- Output: detailed results and plots for Q1 – Q5.
- **NOTE**: It wasn't mentioned if it was required to scale the data or not, but as a general practice I've scaled the data and then implemented the task.

---

## 🎬 Task 2 – Recommender Systems

- Built models using the **Surprise** library:
  - **User-based Collaborative Filtering**
  - **Item-based Collaborative Filtering**
  - **Probabilistic Matrix Factorization (PMF/SVD)**
- Evaluated under **5-fold cross-validation** using **MAE** and **RMSE**.
- Compared effects of:
  - Similarity metrics (Cosine, MSD, Pearson)
  - Number of neighbors (K)
- Plotted RMSE vs K to identify optimal neighbor sizes.
