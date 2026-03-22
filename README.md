# Randomness in PINNs: Neural PDE Perspective

This repository contains the implementation and datasets associated with the paper:

**"Randomness and Signal Propagation in Physics-Informed Neural Networks (PINNs): A Neural PDE Perspective"**

---


## 📌 Overview

Physics-Informed Neural Networks (PINNs) often exhibit **highly random weight structures** after training.  
This project investigates:

- Statistical properties of trained PINN weights  
- Connections to **Random Matrix Theory (RMT)**  
- Role of **numerical stability** in signal propagation  

---


## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/randomness-in-PINNs.git
cd randomness-in-PINNs
```

## 📂 Structure
- `checkpoints/` → Saved and stored trained PINN models (inviscid Burgers / Riemann IC)  
- `weights_riemann/` → Saved weights & biases (inviscid Burgers / Riemann IC)  
- `weights_sine/` → Saved weights & biases (viscous Burgers / sine IC)  
- `pinn_analysis.ipynb` → Statistical analysis of trained PINN weights  
- `FDM.ipynb` → Finite-difference experiments (Fig. 6: stability analysis)

---

## ▶️ Usage

### 1. Analyze PINN Weights

Open and run:

```bash
pinn_analysis.ipynb
```
### 2. FDM Comparisons

Open and run:

```bash
fdm.ipynb
```

## 📖 Citation
```bash
@article{Tucny2026,
  author  = {Jean-Michel Tucny and Abhisek Ganguly and Santosh Ansumali and Sauro Succi},
  title   = {Randomness and signal propagation in physics-informed neural networks (PINNs): a neural PDE perspective},
  journal = {The European Physical Journal Plus},
  year    = {2026},
  volume  = {141},
  number  = {3},
  pages   = {321},
  doi     = {10.1140/epjp/s13360-026-07549-0}
}
```
## arXiv version:
```bash
@misc{tucny2026randomnesssignalpropagationphysicsinformed,
      title={Randomness and signal propagation in physics-informed neural networks (PINNs): A neural PDE perspective}, 
      author={Jean-Michel Tucny and Abhisek Ganguly and Santosh Ansumali and Sauro Succi},
      year={2026},
      eprint={2509.18131},
      archivePrefix={arXiv},
      primaryClass={cs.LG},
      url={https://arxiv.org/abs/2509.18131}, 
}
```


## 📬 Contact
```bash
abhishekganguly808@gmail.com
```
