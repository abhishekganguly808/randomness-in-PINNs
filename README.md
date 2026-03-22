# Randomness in PINNs: Neural PDE Perspective

This repository contains code and data for analyzing **weight statistics and signal propagation in Physics-Informed Neural Networks (PINNs)**.

---

## 📂 Structure
- `saved_models/` → Saved and stored trained PINN models (inviscid Burgers / Riemann IC)  
- `riemann_weights/` → Saved weights & biases (inviscid Burgers / Riemann IC)  
- `sine_weights/` → Saved weights & biases (viscous Burgers / sine IC)  
- `pinn_analysis.ipynb` → Statistical analysis of trained PINN weights  
- `FDM.ipynb` → Finite-difference experiments (Fig. 6: stability analysis)

---

## ▶️ Usage

### 1. Analyze PINN Weights

Open and run:

```bash
pinn_analysis.ipynb
