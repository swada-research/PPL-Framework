# PPL-Framework: Universal Phase Space Projection & Observational Validation

[![License: MIT](https://img.shields.org/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Zenodo Part I](https://zenodo.org/badge/DOI/10.5281/zenodo.22139099.svg)](https://doi.org/10.5281/zenodo.22139099)
[![Zenodo Part II](https://zenodo.org/badge/DOI/10.5281/zenodo.22261783.svg)](https://doi.org/10.5281/zenodo.22261783)

An open-science framework for the **Prime-Prime Lattice (PPL)** theory, unifying microscopic quantum field actions, macroscopic general relativity, and non-equilibrium wave dynamics under a constant-free multiplicative paradigm ($|\emptyset\rangle=1$).

---

## 📂 Repository Structure

* `01_PPL_Foundation.ipynb`
  * **Paper I**: Mathematical infrastructure, prime-axis phase reduction, and dynamic origins of the Riemann Hypothesis.
* `02_PPL_Kuramoto_GW_Validation.ipynb`
  * **Paper II**: Out-of-sample observational validation of the $4/3$ critical ratio using the LIGO O4 gravitational wave dataset ($N=420$).
* `03_PPL_Kuramoto_MHD_Validation.ipynb`
  * **Paper II**: Application to fusion plasma physics: pre-disruption precursor detection in MHD systems via Kuramoto order parameters.
* `04_PPL_Quantum_Action_Forces.ipynb`
  * **Paper III**: First-principles derivation of Planck's constant ($h$) from $\zeta(4)$, logarithmic deconstruction of the Ampère-Maxwell equation, and unified force generation via Phase Free Energy ($F_{\text{free}}$).
* `PPL_Physics_Part3.pdf`
  * Full manuscript for Part III.

---

## 🔬 Core Discoveries in Part III

1. **First-Principles Derivation of Planck's Constant ($h$)**
   * The empirical quantum of action $h \approx 6.626 \times 10^{-34} \text{ J}\cdot\text{s}$ is derived from the simple cubic grid coordination number ($C_{\text{PPL}} = 2 \times 3 = 6$) and 4D energy density $\zeta(4) = \pi^4 / 90$:
     $$E_{\text{cell}} = C_{\text{PPL}} \times \zeta(4) = \frac{\pi^4}{15}$$
   * Verified in `04_PPL_Quantum_Action_Forces.ipynb` with an absolute relative error of $2.90 \times 10^{-7}$.

2. **Deconstruction of the Ampère-Maxwell Law**
   * Demonstrates that the classical additive current structure ($\mathbf{J} + \frac{1}{c_0^2}\frac{\partial \mathbf{E}}{\partial t}$) is a linear differential artifact created by projecting a single multiplicative Euler product state ($\Psi_{\text{total}} = \Psi_{\text{soliton}} \times \Psi_{\text{field}}$) through a logarithmic observer lens ($\Phi = \log \Psi$).
   * Resolves electrodynamics using a strictly source-free universal wave equation ($\text{RHS} = 0$).

3. **Thermodynamic Force Unification**
   * Coulombic, Magnetic (Lorentz shear on $\mathbb{C}=1$), and Gravitational interactions are unified as autonomous gradient flows optimizing Phase Free Energy:
     $$\mathbf{F} = -\nabla F_{\text{free}}$$

---

## 📚 Citations & Publications

If you use this framework or theory in your research, please cite the corresponding papers:

### Part I: Mathematical Foundations & Riemann Hypothesis
```bibtex
@article{wada2026ppl1,
  author       = {Wada, Shuichi},
  title        = {The Prime-Prime Lattice (PPL) Space and Wave Interference: Part I: A Physical Perspective on the Dynamical Origin of the Riemann Hypothesis},
  year         = 2026,
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.22139099}
}
### Part Ⅱ Macroscopic Spacetime & GW170817/O4 Varidation
@article{wada2026ppl2,
  author       = {Wada, Shuichi},
  title        = {The Prime-Prime Lattice (PPL) and Non-Equilibrium Open Wave Dynamics: Part II: The Kuramoto Model as the Generative Foundation of Fields, Macroscopic Spacetime Phase Transitions, and Out-of-Sample Observational Validation of the 4/3 Critical Ratio via the O4 Gravitational Wave Dataset},
  year         = 2026,
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.22261783}
}
### Part III: Microscopic Field Vibrations & Quantum Action
@article{wada2026ppl3,
  author       = {Wada, Shuichi},
  title        = {The Prime-Prime Lattice (PPL) Space and Non-Equilibrium Open Wave Dynamics: Part III: Microscopic Field Vibrations, Quantum Action from Zeta, and the Thermodynamic Origin of Three Fundamental Forces},
  year         = 2026,
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.22314253}
}
