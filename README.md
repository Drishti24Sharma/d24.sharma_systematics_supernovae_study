# Supernova Cosmology – Systematics and Dark Energy Models  

**Analysis pipeline and datasets for studying systematic effects in supernova cosmology, comparing CPL, Generalized Scale Factor, JBP, and LOG parametrizations.**

This repository contains the complete set of Python scripts, datasets, and resulting plots used to investigate the impact of various systematic effects on dark energy constraints from Type Ia supernovae. The analysis compares:  

- **Chevallier–Polarski–Linder (CPL) parametrization**  
- **Generalized Scale Factor (Sinh) model**, including the transformation of \((A, B)\) parameters into \((w_0, w_a)\)  
- **Jassal–Bagla–Padmanabhan (JBP) parametrization**  
- **LOG parametrization**  

---

## 📂 Repository Contents
- **`codes.zip`** – All Python code used in this analysis:
  - Cosmological models: CPL, Generalized (Sinh), JBP, and LOG parametrizations  
  - Implementation of all systematic effects considered  
  - Transformation of \((A, B)\) to \((w_0, w_a)\)  
  - Plotting scripts for contour and parameter shift visualizations  
- **`data.zip`** – Processed SN Ia and BAO datasets used in the analysis  
- **`results.zip`** – Resulting plots and figures illustrating the impact of systematics on dark energy constraints  

---

## 🛠 Systematic Effects Modeled
- Calibration offset  
- Intergalactic dust  
- Progenitor evolution in \(x_1\) and \(M_B\)  
- Increased scatter in color correction  

---

## 🚀 Usage
1. Download and unzip the code, data, and results files  
2. Ensure Python 3.9+ with the following dependencies:
   ```bash
   pip install numpy scipy matplotlib emcee corner getdist
