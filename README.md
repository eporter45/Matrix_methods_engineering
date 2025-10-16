# 🧮 Matrix Methods for Engineering

A collection of **homework notebooks** and **personal projects** exploring matrix-based computational techniques in engineering analysis.  
This repository combines coursework from the *Matrix Methods for Engineers* curriculum with independent explorations of linear algebra applications in structural and mechanical systems.

---

## 📂 Repository Overview


---

---

## 🧠 Topics & Concepts

- Linear systems and Gaussian elimination  
- LU / QR / SVD matrix factorizations  
- Eigenvalues, eigenvectors, and modal analysis  
- Finite element modeling (e.g., planar truss analysis)  
- Numerical conditioning and error propagation  
- Practical engineering applications of linear algebra  

---

## 🧰 Tools & Environment

Developed in **Julia** using **Jupyter Notebooks** (`IJulia` kernel).

**Core Julia Packages**
- `LinearAlgebra` — core matrix operations and factorizations  
- `Statistics` — basic statistical tools  
- `Plots` — visualization and plotting  
- `DataFrames` — structured data handling  
- `DelimitedFiles` — CSV and text file I/O  

**Recommended Environment Setup**
```bash
# Install Julia (https://julialang.org/downloads/)
# Then in the Julia REPL:
using Pkg
Pkg.add(["IJulia", "LinearAlgebra", "Statistics", "Plots", "DataFrames", "DelimitedFiles"])
