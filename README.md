# ⚛️ Fissile Core Criticality & Neutron Transport Simulation

An interactive 2D Monte Carlo simulation of neutron transport and criticality balance ($k_{\text{eff}}$) in a fissile assembly.

🚀 **[Try the live simulation](https://your-username.github.io/your-repo-name/)** *(Replace with your GitHub Pages link)*

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
