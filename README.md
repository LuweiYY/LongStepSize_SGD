# Code Verification for *Generalization of Silver Stepsize Schedule to Stochastic Optimization*

This repository contains the Mathematica notebooks and scripts used to verify several technical statements and footnotes in the accompanying paper:

> **Generalization of Silver Stepsize Schedule to Stochastic Optimization**  
> (Authors: *[Your Name]*, et al.)  

The purpose of this code release is to provide full transparency for all symbolic computations, numerical experiments, and feasibility checks that support the derivations in the main text. Each footnote is independently verified with a dedicated Mathematica script, allowing readers to reproduce all results exactly as reported.

---

## 🔍 Overview

The code in this repository verifies the following components of the paper:

- **Footnote 2** — Verification of the admissibility conditions for the two-step stochastic silver stepsize schedule.  
- **Footnote 3** — Validation of the uniqueness and feasibility of the cubic (or higher-degree) algebraic expressions used to define \(\alpha^\star\) and \(\beta^\star\).  
- **Footnote 5** — Numerical confirmation that the constructed dual variables satisfy all linear matrix inequality (LMI) constraints in the stochastic PEP formulation.  
- **Footnote 6** — Verification of the monotonicity / continuity / bound properties required for the function \(h(v,\sigma/R)\), including the identification of the optimal \(v\).

All scripts were written in **Wolfram Mathematica** and require Mathematica ≥ **13.0**.

---

## 📁 Repository Structure
- Each `footnoteX_verification.nb` file corresponds exactly to the footnote labeled \(X\) in the paper.  
- The `utils/` directory contains helper functions used across footnotes (root solvers, dual-feasibility checks, symbolic computation helpers, etc.).

---

## ▶️ How to Use

### **1. Requirements**

- Wolfram Mathematica **13.0** or above  
- All files in this repository must be kept in the same directory structure  
- No external dependencies beyond standard Mathematica libraries

---