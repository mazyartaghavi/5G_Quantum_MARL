# 🚁 Quantum-Inspired MARL for 5G Network Expansion Using UAVs

This project implements a **Quantum-Inspired Multi-Agent Reinforcement Learning (MARL)** framework for solving the **exploration–exploitation tradeoff** in **5G network expansion** using a team of 10 intelligent UAVs operating in a **partially observable**, **dynamic** environment.

---

## 🧠 Key Features

- ✅ **10 UAVs** coordinating to optimize 5G signal coverage.
- 🔍 **Partial Observability** via local view grids + shared memory.
- 🤖 **Centralized Training, Decentralized Execution (CTDE)** with shared critic and decentralized actor networks.
- ⚛️ **Quantum-Inspired Optimization** using Simulated Quantum Annealing and QAOA (Qiskit).
- 📈 **Logging and Visualization** of UAV paths, rewards, and coverage maps.
- 🧪 **Bayesian Signal Modeling** using Gaussian Processes for predictive coverage optimization.
- 🎯 **TensorBoard Support** for live training visualization.

---

## 📂 Project Structure


---

## 🚀 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/yourusername/uav-quantum-marl.git
cd uav-quantum-marl
pip install -r requirements.txt
python train_marl.py
python evaluate_with_quantum.py
python evaluate_with_quantum.py
tensorboard --logdir=runs
