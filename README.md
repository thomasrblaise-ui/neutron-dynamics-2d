# ⚛️ Fissile Core Criticality & Neutron Transport Simulation

An interactive 2D Monte Carlo simulation of neutron transport and criticality balance ($k_{\text{eff}}$) in a fissile assembly.

🚀 **[Try the live simulation](https://github.com/thomasrblaise-ui/neutron-dynamics-2d/commit/4cd6841cc36e6dbc0d3a4ee744622cff0db817e4#diff-b335630551682c19a781afebcf4d07bf978fb1f8ac04c6bf87428ed5106870f5R5)** *(Replace with your GitHub Pages link)*

---

## 🔬 Modeled Physical Principles

This application simulates particle-by-particle stochastic transport within a fissile medium surrounded by a reflector:

* **Monte Carlo Method:** Trajectories, collisions, and reactions randomly sampled according to probability distributions.
* **Neutron Transport:** Accounts for speed, sterile capture, fission, and geometric leakage.
* **Reflector & Albedo:** Controls the return rate of escaping neutrons at system boundaries.

## 🎛️ Controllable Parameters

* **Fissile Core Radius:** Adjusts reactive volume (size effect and geometric buckling).
* **Reflector Albedo:** Neutron reflection probability (0% to 100%).
* **Neutron Speed:** Sets the kinetic timescale of particle movement.
* **Reaction Probabilities:** Cross-section equivalents for fission and capture.
* **Neutrons per Fission ($\nu$):** Average neutron yield per fission event.

## 🛠️ Tech Stack

* **HTML5 / Canvas 2D**
* **Vanilla JavaScript** (zero dependencies, 60 FPS rendering)
* **MediaRecorder API** (built-in WebM video export)

## 🚀 Local Setup

1. Clone the repository:
   ```bash
   git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
