# Neural ODEs for Phase Space Estimation

This project investigates the use of **Neural Ordinary Differential Equations (Neural ODEs)** as a data-driven method to model dynamical systems directly from trajectory data, without requiring knowledge of the underlying governing equations. The study benchmarks Neural ODE performance against **Sparse Identification of Nonlinear Dynamics (SINDy)**, a state-of-the-art symbolic regression technique for discovering governing equations.

## 📌 Project Highlights

- Learns phase space dynamics purely from observed trajectories.
- Identifies fixed points and analyses their stability using Jacobian eigenvalue analysis.
- Evaluates interpolation and extrapolation performance.
- Tests capabilities on chaotic systems such as the Lorenz attractor.
- Benchmarks Neural ODEs against SINDy for accuracy and runtime.
- Demonstrates qualitative bifurcation behaviour in systems like the Van der Pol oscillator.

## 📝 Repository Structure
```bash
├── presentation/
│ └── final_presentation.pptx # Final Presentation for the Project
├── report/
│ └── final_report.pdf # Final Report for the Project
├── requirements.txt
├── main.ipynb # All code for the Project in 1 Jupyter Notebook
└── README.md
```

## 🚀 Getting Started

### Installation

1. Clone the repository:

```bash
git clone https://github.com/username/neural-odes-dynamics.git
cd neural-odes-dynamics
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```


