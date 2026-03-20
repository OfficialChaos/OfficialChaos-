# Shawn G. Kleipe

**Independent Researcher — Quantum Error Mitigation & Physics-Informed Methods**

---

## Current Research

### Fluid-Dynamic Stability Filtering for Zero-Noise Extrapolation in NISQ-Era Quantum Circuits

Introducing two contributions to quantum error mitigation:

- **A fluid-dynamic stability filter** — a post-hoc reliability criterion based on a discrete H¹ Sobolev regularity functional on the ZNE curve. Flags unreliable ZNE outputs without additional circuit evaluations. Zero flags in 14,400 simulation trials at p≤0.01, d≤4 (95% C-P bound: p_flag < 0.00022).
- **Five structured noise scaling schedules** — Fibonacci, Lucas, prime-anchored, linear, and odd-integer — systematically compared across all four standard extrapolants (linear, Richardson, poly-2, poly-3). Fibonacci achieves lowest mean ε; Lucas achieves lowest ZNE variance on unstructured circuits.

Evaluated across **153,600 simulation runs** (4 circuit types × 5 schedules × 4 extrapolants × 3 qubit counts × 8 depths × 8 noise levels × 10 trials) and **120 hardware trials** on IBM Quantum processors ibm_fez (Heron r2) and ibm_torino (Heron r1). All 24 hardware conditions pass Γ=0.05; maximum observed ε=0.00285 (5.7% of Γ).

📄 [Paper (PDF)](https://github.com/OfficialChaos/Quantum-Vortex-QEM/blob/main/paper/kleipe2026_v4.pdf) &nbsp;|&nbsp; 💾 [Code](https://github.com/OfficialChaos/Quantum-Vortex-QEM) &nbsp;|&nbsp; 🗃️ [Zenodo Archive](https://doi.org/10.5281/zenodo.18827720)

---

## Stack

[![Python](https://img.shields.io/badge/Python-3.10+-blue)](https://www.python.org)
[![Cirq](https://img.shields.io/badge/Cirq-1.3+-lightgrey)](https://quantumai.google/cirq)
[![Mitiq](https://img.shields.io/badge/Mitiq-0.38+-lightgrey)](https://mitiq.readthedocs.io/)
[![Qiskit](https://img.shields.io/badge/Qiskit-1.0+-6929C4)](https://www.ibm.com/quantum/qiskit)
[![IBM Quantum](https://img.shields.io/badge/IBM%20Quantum-0268C2)](https://quantum.cloud.ibm.com)
[![IBM Torino](https://img.shields.io/badge/IBM_Torino-133_Qubits_Heron_r1-161616?logo=ibm&logoColor=white)](https://quantum.cloud.ibm.com)
[![IBM Fez](https://img.shields.io/badge/IBM_Fez-156_Qubits_Heron_r2-161616?logo=ibm&logoColor=white)](https://quantum.cloud.ibm.com)

---

## Links

- 🔬 ORCID: [0009-0002-2480-2430](https://orcid.org/0009-0002-2480-2430)
- 🗃️ Zenodo: [10.5281/zenodo.18827720](https://doi.org/10.5281/zenodo.18827720)
- 📦 Repo: [Quantum-Vortex-QEM](https://github.com/OfficialChaos/Quantum-Vortex-QEM)
