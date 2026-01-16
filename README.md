# Out-of-Time-Ordered Echoes in a Quantum-Fractal Tensor Network Framework

**Author:** Justin Candler  
**Affiliation:** Nous Enterprises LLC  
**Date:** January 16, 2026  
**License:** Creative Commons Attribution-NonCommercial-ShareAlike 4.0 (CC BY-NC-SA 4.0)

This repository contains the full LaTeX source and compiled PDF of the theoretical monograph:

> **Out-of-Time-Ordered Echoes in a Quantum-Fractal Tensor Network Framework**  
> Integrating Theory with Google’s OTOC(2) Experiments

The work presents a comprehensive unification of Google Quantum AI’s 2025 OTOC(2) “Quantum Echoes” experiment (on the 103-qubit Willow processor) with the Quantum-Fractal Tensor Network (QFTN) paradigm. It demonstrates how time-reflection symmetry and multi-scale interference constrain fractal entropy dissipation, reformulate pointer-state geometry using Fubini–Study metrics and Berry curvature corrections, integrate running spectral dimension into temporal entanglement, and extend RG/EFT with fractional operators culminating in proposed polyadic supersymmetry.

## Key Results & Contributions

- **Multi-scale master equation** yielding stretched-exponential and power-law coherence decay, quantitatively matching OTOC(2) signals and slow fractal modes.
- **Curvature-corrected pointer states** as fixed points of an echo superoperator, incorporating Berry curvature penalties in the Fubini–Study metric.
- **Running spectral dimension** $d_s(t)$ in time-domain entanglement curves, predicting two-regime decay consistent with EEG coherence and suggesting criticality at $d_s \approx 2$ for maximal memory retention.
- **Extended RG/EFT** with fractional time derivatives and echo corrections, revealing emergent polyadic supersymmetry underlying multi-arm interference.
- **Fractal Hamiltonians** producing towers of Berry phases that cancel under echoes, with entanglement entropy bounds scaling as $L^{D_f}$ (fractal-dimension area law).
- **Cross-domain universality** — linking quantum processor echoes to CMB log-periodic patterns, EEG long-lived coherence, and potential quantum gravitational signals.

The framework offers testable predictions for higher-order OTOC measurements, Berry curvature routing as a geometric control strategy, and multi-echo protocols in neural cultures.

## Repository Contents

- `OTOC - Time-Reversal Echo Dynamics.tex` — Complete LaTeX source (main document)
- `references.bib` — Full BibTeX bibliography (APA/numbers style compatible)
- `main.pdf` — Compiled PDF (latest version)
- `preamble.tex` — Extracted custom preamble (macros, fonts, geometry, etc.) for reuse

## How to Compile

1. Ensure you have a modern TeX distribution (TeX Live 2024+ or MikTeX recommended).
2. Install required packages (most are standard; XeLaTeX/LuaLaTeX preferred for fontspec).
3. Run:

xelatex "OTOC - Time-Reversal Echo Dynamics.tex"
bibtex "OTOC - Time-Reversal Echo Dynamics"
xelatex "OTOC - Time-Reversal Echo Dynamics.tex"   # twice

Or use `latexmk -xelatex` for automatic handling.

Related Work & Contact
This monograph builds on and cites foundational works in quantum chaos, fractal geometry, decoherence, and quantum gravity. For questions, corrections, or collaboration:

## Citation

If you find this work useful, please cite as:

```bibtex
@techreport{candler2026qftn,
author       = {Candler, Justin},
title        = {Out-of-Time-Ordered Echoes in a Quantum-Fractal Tensor Network Framework},
institution  = {Nous Enterprises LLC},
year         = {2026},
month        = {January},
note         = {Draft monograph, January 16, 2026},
url          = {https://github.com/NousEntLLC/qftn-otoc-echoes}
}

