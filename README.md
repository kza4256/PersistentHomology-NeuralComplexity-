# PersistentHomology-NeuralComplexity-
Reproducible pipeline for persistent homology analysis of neural dynamics during CO₂ euthanasia using MATLAB, Python, and Ripser.

# Persistent Homology Reveals Topological Signatures of Neural Complexity During Anesthesia and CO₂ Euthanasia

This repository contains the complete analysis pipeline accompanying the manuscript

> **Persistent Homology Reveals Topological Signatures of Neural Complexity During Anesthesia and CO₂ Euthanasia**

The repository provides a fully reproducible workflow for computing persistent homology descriptors from delay-embedded neural recordings and relating them to neural complexity measured using the Eigensystem Realization Algorithm (ERA).

---

## Overview

The workflow consists of

1. Delay-coordinate embedding of Local Field Potential (LFP) recordings

2. Construction of Vietoris–Rips complexes

3. Persistent homology computation using Ripser

4. Extraction of topological descriptors

   - Total Persistence
   - Persistence Entropy
   - Mean Lifetime
   - Maximum Lifetime
   - H1 Feature Count

5. Statistical analysis

   - Shapiro–Wilk normality tests
   - Friedman repeated-measures tests
   - Holm–Bonferroni corrected Wilcoxon signed-rank tests
   - Spearman correlation analysis

6. Automatic generation of publication-quality figures and tables

---

## Repository Structure

MATLAB/
    Statistical analysis and figure generation

Python/
    Persistent homology computation

Data/
    Example datasets

Figures/
    Automatically generated publication figures

Tables/
    Automatically generated LaTeX tables

Results/
    Statistical outputs

---

## Requirements

MATLAB R2023b or newer

Python 3.11

Required Python packages

- ripser
- persim
- numpy
- pandas
- matplotlib
- scipy

---

## Running the analysis

Simply execute

```matlab
Main.m
```

The script automatically

- imports the data
- computes statistics
- generates all figures
- exports LaTeX tables
- saves publication-ready PDFs

---

## Citation

If you use this repository, please cite

Aqel K., et al.

Persistent Homology Reveals Topological Signatures of Neural Complexity During Anesthesia and CO₂ Euthanasia.

---
