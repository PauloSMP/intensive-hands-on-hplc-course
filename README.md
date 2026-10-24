# intensive-hands-on-hplc-course

Browser-based HPLC teaching tools: a reversed-phase retention simulator and a gradient solvent-consumption calculator, plus a reference page on calibration methods. Built for the Intensive Hands-On HPLC Course (1st edition). CC BY-NC 4.0.

# Intensive Hands-On HPLC Course: Simulators

Two browser-based teaching tools for HPLC and a calibration reference page, developed for the Intensive Hands-On HPLC Course (1st edition).

| Tool | File | What it does |
|---|---|---|
| Simulator 1: HPLC simulator | `hplc-simulator.html` | Reversed-phase isocratic retention model. Change mobile phase, pH, flow, temperature, column and particle size, and see the chromatogram, resolution and back-pressure respond. |
| Simulator 2: Solvent consumption calculator | `consumo-solventes.html` | Volume of solvents A, B, C and D for a quaternary gradient, from flow rate, gradient program, number of injections and a safety excess (%). |
| Reference: HPLC calibration methods | `hplc-calibration.html` | Guide to the three calibration techniques used in HPLC drug analysis: external standard, internal standard and standard addition. Concepts, simulated chromatograms and calibration curves, worked examples, a comparison table and a decision guide for choosing the method. |

`index.html` is the start menu and `licenca.html` is the licence page (in Portuguese).

## Choosing a calibration method

`hplc-calibration.html` ends with a decision guide. In short:

| Method | Use when | Corrects | Does not correct |
|---|---|---|---|
| External standard | Simple preparation and a matrix that does not change the detector response (API assay, dissolution, tablets). | System response only. | Extraction losses, injection volume, matrix effect. |
| Internal standard | Multi-step preparation with variable recovery, a blank matrix and a suitable internal standard (bioanalysis, PK/BE). | Preparation losses, injection variation, detector drift. | Interference at the internal standard peak; matrix effect if the internal standard does not coelute with the drug. |
| Standard addition | No blank matrix, or a matrix that varies from sample to sample (herbal extracts, nanoparticles). | Proportional matrix effect. | Additive interferences, such as a coeluting peak; injection variation between aliquots. |

Decision order:

1. Simple matrix, single-step preparation, no effect on the signal: **external standard**.
2. Otherwise, if a blank matrix and a suitable internal standard are available: **internal standard**.
3. Otherwise, if the matrix is complex or variable, the matrix effect is demonstrated and no equivalent blank exists: **standard addition**.
4. None of the above: improve sample clean-up, or measure the matrix effect by comparing the calibration slope in solvent with the slope in matrix.

The page includes a worked example for each method, with all abbreviations and symbols defined at the end of each section. Its chromatograms and values are simulated and illustrative.

## Use

Offline version: Open `index.html` in any modern browser. No installation or build step. Keep all five files in the same folder, because the pages link to each other.

Online version: https://paulosmp.github.io/intensive-hands-on-hplc-course/ (after enabling GitHub Pages)

The pages load fonts from Google Fonts. Offline they fall back to system fonts and everything still works.

## Notes on the models

- Simulator 1 is a teaching model. Its parameters are illustrative, not fitted to experimental data.
- Simulator 2 interpolates linearly between gradient points. The last time point is the run time of one injection. Purges, washes and conditioning outside the method are not counted, so cover them with the excess.
- The calibration page uses simulated data. It does not replace method validation (ICH Q2(R2); ICH M10 for bioanalysis).

## Licence

© 2026 Paulo Sérgio Marques Pereira. Licensed under Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0).

You may share and adapt this material for non-commercial purposes, as long as you give appropriate credit, link to the licence and indicate if changes were made.

Suggested attribution:

> "[Tool name]", by Paulo Sérgio Marques Pereira, developed for the Intensive Hands-On HPLC Course (1st edition), licensed under CC BY-NC 4.0 (https://creativecommons.org/licenses/by-nc/4.0/).

## Disclaimer

O autor do software não se responsabiliza por qualquer dano em sistemas físicos de HPLC. O simulador deve ser utilizado com sentido crítico e sempre confirmado por análise prática e cálculos efetuados.

(English: The author accepts no responsibility for any damage to physical HPLC systems. Use the simulators with critical judgement and always confirm results with practical analysis and independent calculations.)

## Contact

Paulo Sérgio Marques Pereira · paulo.m.pereira95@gmail.com · [GitHub](https://github.com/PauloSMP) · [LinkedIn](https://www.linkedin.com/in/paulosmp/)
