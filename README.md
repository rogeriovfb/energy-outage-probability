# Energy-Outage Probability (EOP) – Reproducible Code

This repository implements the methods described in the following paper.  
If you use this code in your research, please cite:

Ballestrin, R., Müller, I. (2026).  
*Quantifying Energy Scarcity: Energy-Outage Probability for Energy-Harvesting IoT Nodes*.  
IEEE Communications Letters, 30, 1355–1359.  
https://doi.org/10.1109/lcomm.2026.3671672

## 📄 Citation

### BibTeX
```bibtex
@article{Ballestrin2026,
  title = {Quantifying Energy Scarcity: Energy-Outage Probability for Energy-Harvesting IoT Nodes},
  volume = {30},
  ISSN = {2373-7891},
  url = {http://dx.doi.org/10.1109/LCOMM.2026.3671672},
  DOI = {10.1109/lcomm.2026.3671672},
  journal = {IEEE Communications Letters},
  publisher = {IEEE},
  author = {Ballestrin, Rogério and Müller, Ivan},
  year = {2026},
  pages = {1355–1359}
}

```
## Overview

This repository provides the exact implementation used to generate all numerical results and figures reported in the manuscript.

The focus of the paper is a discrete-time, slot-synchronous abstraction that enables a compact closed-form characterization of energy unavailability in energy-harvesting IoT nodes.

All simulations, analytical evaluations, and figure generation routines are contained in a single notebook:EOP_IEEE_CL.ipynb

## System Model

The implemented model considers:

- Discrete-time operation
- Slot-synchronous abstraction
- Finite battery capacity
- Stochastic energy harvesting process
- Per-slot energy consumption


