# Code Verification for *Generalization of Silver Stepsize Schedule to Stochastic Optimization*

This repository contains the Mathematica notebooks and scripts used to verify several technical statements and footnotes in the accompanying paper:

> **Generalization of Silver Stepsize Schedule to Stochastic Optimization**  
> (Authors: *Luwei Bai*, *Yang Zeng*, *Baoyu Zhou*)  

The purpose of this code release is to verify several computations in the paper that are difficult to carry out by hand. These scripts reproduce the algebraic steps, numerical checks, and feasibility conditions referenced in the footnotes, allowing readers to confirm the results more easily and to better understand the technical details behind the analysis.

---

## 🔍 Overview

The code in this repository verifies the following components of the paper:

- **Footnote 2** — Verifies that the proposed two-step stochastic stepsize schedule correctly recovers the classical silver stepsize when  
- \(v = 0\), or  
- \(n = 1\).    
- **Footnote 3** — Verifies that the convergence rate achieved by the proposed stepsize schedule coincides with that of the classical silver stepsize when \(v = 0\).  
- **Footnote 5** — Verifies the explicit structure of the matrix \(\Delta\) for different values of \(n\).
- **Footnote 6** — Verifies that the constructed dual variables and stepsizes satisfy the required system of equations.

All scripts were written in **Wolfram Mathematica**.

---

## 📁 Repository Structure
- Each `Verify-footnoteX.nb` file corresponds exactly to the footnote labeled \(X\) in the paper.  

---

## ▶️ Requirements

- Wolfram Mathematica **13.0** or above  
- No external dependencies beyond standard Mathematica libraries

---