# raft-uav-artifact
Artifact and supplementary appendix for “Adaptive Raft Timeouts for UAV Swarms via Safe Online RL” , includes simulator, baselines, ablations, reproducibility scripts, and additional experimental figures.
# Adaptive Raft Timer Control for UAV Swarms — Artifact & Appendix

This repository accompanies the paper:

> **Adaptive Raft Timeouts for UAV Swarms via Safe Online RL**

It provides two key components:

1. **Research Artifact**  
   A lightweight simulation framework that models FANET-style conditions, a Raft control-plane runtime, and an adaptive Q-learning controller with guardrails. The artifact includes baselines, ablations, statistics, and scripts to reproduce the experiments and plots from the paper.  
   All technical and coding details, along with full reproducibility instructions, are packaged in the `artifact.rar` folder.

2. **Supplementary Appendix**  
   The file (appendix_experimental_figures.pdf) contains additional figures and extended reproducibility details. These supplementary materials provide further insight into:  
   - Election and heartbeat timer usage patterns  
   - Cost and exploration dynamics  
   - Control-message composition and energy/overhead trends  
   - Seed-to-seed reproducibility checks  
   - Simulator vs. hardware-in-the-loop validation  
   - State coverage and robustness diagnostics  

---

## How to use this repository

- Start with the **artifact package** (`artifact.rar`) to access the simulator, configurations, and scripts for reproducing the results.  
- Consult the **appendix PDF** for extended plots, diagnostics, and methodological details beyond the main paper.  

---

## License & citation

## License & citation

This artifact is released under the **MIT License** file for details.
If you use this code, dataset, or figures in your own work, please cite our paper:
> *Resource-Aware Raft for UAV Swarms via Online Q-Learning: A Systems-Level Adaptive Timeout Controller*  
> Authors: [Your Names Here]  
> Preprint / Conference (2025).  

A `CITATION.cff` and BibTeX entry will be provided once the paper’s final version is available.

---

## Contact

For questions, reproducibility issues, or suggestions, please open a GitHub issue.  
Contributions (e.g., new figures, diagnostics, or extended scenarios) are welcome.
