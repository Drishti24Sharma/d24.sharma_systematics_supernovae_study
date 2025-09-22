# Supernova Cosmology – Systematics and Dark Energy Models  
**Analysis pipeline and datasets for studying systematic effects in supernova cosmology, comparing CPL and generalized scale factor models.**

This repository contains the complete set of Python scripts and datasets used to investigate the impact of various systematic effects on dark energy constraints from Type Ia supernovae.  
The analysis compares the **Chevallier–Polarski–Linder (CPL)** parametrization and a **Generalized Scale Factor** (Sinh) model, including the transformation of \((A, B)\) parameters into \((w_0, w_a)\) for direct comparison.

---

## 📂 Repository Contents
- **`codes.zip`** – All Python code used in this analysis:
  - Cosmological models (CPL, Generalized, JBP and LOG parametrisation.)  
  - Implementation of all systematic effects considered in the study  
  - Transformation of \((A, B)\) to \((w_0, w_a)\)  
  - Plotting scripts for contour and parameter shift visualizations  
- **`data.zip`** – Processed SN Ia and BAO datasets used in the analysis.  

---

## 🛠 Systematic Effects Modeled
- Calibration offset  
- Intergalactic dust  
- Progenitor evolution in \(x_1\) and \(M_B\)  
- Increased scatter in color correction  

---

## 🚀 Usage
1. Download and unzip the code and data files.  
2. Ensure Python 3.9+ with the following dependencies:
   ```bash
   pip install numpy scipy matplotlib emcee corner getdist

## Reference

This repository is part of the work presented in:(update refernce)

**Impact of Systematics on Dark Energy Inference from Type Ia Supernovae**, Master's Thesis, Drishti Sharma, 2025.  
[Link to thesis if available]

