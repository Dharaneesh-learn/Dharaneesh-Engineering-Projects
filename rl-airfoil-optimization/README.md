# Reinforcement Learning for Airfoil Optimization

## Overview
This project explores the use of reinforcement learning to improve aerodynamic performance of airfoil geometries using CST parameterization and automated aerodynamic evaluation.

The objective was to investigate the effect of sensitivity guided model in aerodynamic improvement of airfoil in comparision with conventional equal weights model.

---

## Problem
Traditional airfoil optimization requires repeated manual tuning and gradient-free search methods that struggle with noisy aerodynamic evaluations.

The challenge was to enable stable learning in a continuous aerodynamic design space under noisy solver feedback.

---

## Approach (High-Level)
- Airfoil geometry represented using CST parameters
- Automated aerodynamic evaluation pipeline
- Reinforcement learning based iterative optimization

*(Implementation details intentionally omitted as work is under ongoing research development.)*

---

## Results

### Baseline Airfoil
NACA 0012  
Baseline Cl/Cd ≈ **25.55**

### Optimized Performance
- Significant aerodynamic efficiency improvement
- Stable geometry evolution during training
- **42% faster early exploration compared to equal-weight strategy**

---

## Example Results

### Training Behaviour
![Training Curve]("rl_train_git.pngg")
- cl/cd vs episode curve shows the aerodynamic performance improvement as training iteration progressed

### Airfoil Evolution
![Airfoil Comparison]("C:\Users\dhara\OneDrive\Pictures\Screenshots\Progressive_airfoil_rl_git.png")
- Note : The images provided are just samples obtained during training.
- There are multiple airfoil shapes that achieve the same Aerodynamic performance parameter
---

## Tools
Python • XFOIL • Reinforcement Learning Framework

---

## Status
⚠️ Work under active development. Detailed methodology and implementation are reserved for future publication.
