[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.22261783.svg)](https://doi.org/10.5281/zenodo.22261783)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

# PPL-Framework: Universal Phase Space Projection & Observational Validation

This repository provides the core mathematical engine, deterministic validation pipelines, and empirical assets for **PPL (Phase Space Projection) Theory Parts I & II**. It encompasses both the fundamental number-theoretic lattice verification (Paper I) and the large-scale out-of-sample observational validation across $N=420$ LIGO/Virgo/KAGRA O4 gravitational wave events alongside fusion plasma MHD disruption detection (Paper II, Version 2.0).

## Key Empirical Results (O4 Dataset, N=420)

| Metric / Parameter | Value | Scientific Impact & Significance |
| :--- | :--- | :--- |
| **Dataset Size** | $N = 420$ | Full out-of-sample observational validation across O4 catalog |
| **Geometric Clamp** | $C = 0.1454\text{ s}$ | Theoretical floor convergence ($4/3$ ratio limit, $R^2 = 0.9843$) |
| **Log Bayes Factor** | $\ln B_{\mathrm{PPL/GR}} = 32.08$ | Decisive evidence over standard GR ($\sim 8.5 \times 10^{13}:1$ odds ratio) |
| **Phase Extraction** | Universal Jacobi ($\mathcal{J}$) | Deterministic $T_0$ extraction, eliminating digital filter artifacts |

![O4 Validation Plot](./assets/PPL_O4_Validation.png)

## Repository Structure

```text
PPL-Framework/
├── 01_PPL_Foundation.ipynb               # Paper I: Fundamental Mathematical Verification Notebook
│   ├── galois_product.py                 # Proposition 3.1: Phase reduction via Galois product
│   ├── count_surfaces.py                 # Definition 2.2: Counting independent complex surface bundles
│   └── sync_volume.py                    # Definition 2.4: 1D scanning total phase-synchronization volume
├── 02_PPL_Kuramoto_GW_Validation.ipynb   # Paper II: O4 (N=420) GW Bayesian Validation & 4/3 Clamping
├── 03_PPL_Kuramoto_MHD_Validation.ipynb  # Paper II: Fusion Plasma MHD Disruption Detection PoC
├── paper/
│   └── PPL_Kuramoto_v2.pdf               # Paper II Manuscript (Version 2.0)
├── assets/
│   └── PPL_O4_Validation.png             # Automated O4 Validation Plot
├── CITATION.cff                          # Citation Metadata
├── LICENSE                               # MIT License
└── README.md                             # Repository Overview

## Citation

If you use this framework, verification code, or datasets in your research, please cite the corresponding paper(s):

### Part I: Mathematical Foundations
```bibtex
@article{wada2026ppl1,
  author       = {Wada, Shuichi},
  title        = {The Prime-Prime Lattice (PPL) and Non-Equilibrium Open Wave Dynamics: Part I: A Physical Framework for Cosmic Tuning via MSPP and the Dynamical Origin of the Riemann Hypothesis},
  year         = 2026,
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.22139099}
}

@article{wada2026ppl2,
  author       = {Wada, Shuichi},
  title        = {The Prime-Prime Lattice (PPL) and Non-Equilibrium Open Wave Dynamics: Part II: The Kuramoto Model as the Generative Foundation of Fields, Macroscopic Spacetime Phase Transitions, and Out-of-Sample Observational Validation of the 4/3 Critical Ratio via the O4 Gravitational Wave Dataset},
  year         = 2026,
  publisher    = {Zenodo},
  version      = {2.0.0},
  doi          = {10.5281/zenodo.22314253}
}
