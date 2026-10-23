# intensive-hands-on-hplc-course
Browser-based HPLC teaching tools: a reversed-phase retention simulator and a gradient solvent-consumption calculator. Built for the Intensive Hands-On HPLC Course (1st edition). CC BY-NC 4.0.
# Intensive Hands-On HPLC Course: Simulators

Two browser-based teaching tools for HPLC, developed for the **Intensive Hands-On HPLC Course (1st edition)**.

| Tool | File | What it does |
|---|---|---|
| Simulator 1: HPLC simulator | `hplc-simulator.html` | Reversed-phase isocratic retention model. Change mobile phase, pH, flow, temperature, column and particle size, and see the chromatogram, resolution and back-pressure respond. |
| Simulator 2: Solvent consumption calculator | `consumo-solventes.html` | Volume of solvents A, B, C and D for a quaternary gradient, from flow rate, gradient program, number of injections and a safety excess (%). |

`index.html` is the start menu and `licenca.html` is the licence page (in Portuguese).

## Use

Open `index.html` in any modern browser. No installation or build step. Keep all four files in the same folder, because the pages link to each other.

Online version: https://paulosmp.github.io/intensive-hands-on-hplc-course/ (after enabling GitHub Pages)

The pages load fonts from Google Fonts. Offline they fall back to system fonts and everything still works.

## Notes on the models

- Simulator 1 is a teaching model. Its parameters are illustrative, not fitted to experimental data.
- Simulator 2 interpolates linearly between gradient points. The last time point is the run time of one injection. Purges, washes and conditioning outside the method are not counted, so cover them with the excess.

## Licence

© 2026 Paulo Sérgio Marques Pereira.
Licensed under [Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/).

You may share and adapt this material for non-commercial purposes, as long as you give appropriate credit, link to the licence and indicate if changes were made.

Suggested attribution:

> "[Tool name]", by Paulo Sérgio Marques Pereira, developed for the Intensive Hands-On HPLC Course (1st edition), licensed under CC BY-NC 4.0 (https://creativecommons.org/licenses/by-nc/4.0/).

## Disclaimer

O autor do software não se responsabiliza por qualquer dano em sistemas físicos de HPLC. O simulador deve ser utilizado com sentido crítico e sempre confirmado por análise prática e cálculos efetuados.

*(English: The author accepts no responsibility for any damage to physical HPLC systems. Use the simulators with critical judgement and always confirm results with practical analysis and independent calculations.)*

## Contact

Paulo Sérgio Marques Pereira · paulo.m.pereira95@gmail.com · [GitHub](https://github.com/PauloSMP) · [LinkedIn](https://www.linkedin.com/in/paulosmp/)
