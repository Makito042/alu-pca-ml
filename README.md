Advanced Linear Algebra (PCA) – Formative Assignment
Overview
This repository contains our group’s submission for the  Machine Learning formative assignment on Principal Component Analysis (PCA). The project demonstrates a full PCA implementation from scratch (using only NumPy), eigenvalue/eigenvector analysis, and a custom matrix multiplication library.

Contents
notebook/ – Google Colab notebook with code and outputs

african_crises.csv – Africanized dataset used for PCA

handwritten_calculations.pdf – PDF of eigenvalue/eigenvector calculations (handwritten)

alumathPeer Group 10 / – Python package for matrix multiplication

README.md – This file

Instructions
 Running the PCA Notebook
Open the notebook in Google Colab or Jupyter.

Dataset: Ensure african_crises.csv is in the same directory as the notebook.

Run each cell sequentially.
The notebook covers:

Data loading and standardization (using only NumPy)

Covariance matrix calculation

Eigendecomposition (eigenvalues and eigenvectors)

Sorting and selection of principal components

Projection of data onto principal components

Visualization of dimensionality reduction

Note:
1. No sklearn or pandas standardization is used—only manual NumPy operations as required.

2. Handwritten Eigenvalue/Eigenvector Calculations
See handwritten_calculations.pdf for manual calculations of eigenvalues, eigenvectors, and their importance.

Each group member contributed and signed the work for proof of collaboration.

3. Custom Matrix Multiplication Library
We provide a simple Python package for matrix multiplication, published as alumathMember peer group 10.

Installation

bash
pip install alumath_Peergroup10
Usage

python
from alumath_Peer Group 10 .linalg import matmul
import numpy as np

A = np.array([[1, 2], [3, 4]])
B = np.array([[5, 6], [7, 8]])
result = matmul(A, B)
print(result)
The function matmul(A, B) multiplies two matrices of compatible dimensions.




