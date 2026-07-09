# PyGEM_RT — Frontal Ablation Calibration Branch

[![Paper](https://img.shields.io/badge/📄-GMD_Preprint_2026-blue)](https://doi.org/10.5194/egusphere-2026-1081)
[![DOI](https://img.shields.io/badge/DOI-10.5281/zenodo.18761729-blue.svg)](https://doi.org/10.5281/zenodo.18761729)
[![GitHub release](https://img.shields.io/github/v/release/Ruitangtang/PyGEM?label=stable&color=blue)](https://github.com/Ruitangtang/PyGEM/releases/tag/v1.0.0-zenodo-pygem-rt)

This branch contains the **PyGEM modifications** used for the frontal ablation calibration study:

> *"Joint Bayesian Calibration of Frontal Ablation and Surface Mass Balance in Global Glacier Models"* (GMD Preprint, 2026)

**Key modifications:**
- Added monthly mass balance functions and new parameters to `get_annual_mb`
- Added `volume_m3_annual/month_ice` outputs and `glac_wide_massbalclim` variable in the mass balance class
- Integrated length change as an extra glacier variable for terminus tracking
- Refactored calving flowline functions with cleaner workflow logic
- Custom output handlers to export frontal ablation flux alongside standard mass balance outputs

**Full research archive:** [Zenodo concept DOI 10.5281/zenodo.18761729](https://doi.org/10.5281/zenodo.18761729)

**Stable release:** [`v1.0.0-zenodo-pygem-rt`](https://github.com/Ruitangtang/PyGEM/releases/tag/v1.0.0-zenodo-pygem-rt)

🚀 Lightweight showcase repo: [**Ruitangtang/frontal-ablation-glacier-demo**](https://github.com/Ruitangtang/frontal-ablation-glacier-demo) — YAML configs, dry-run quickstart commands, tests, method/results visuals, and reproducibility links.

**Citation:**
> Yang et al. *Joint Bayesian Calibration of Frontal Ablation and Surface Mass Balance in Global Glacier Models*. GMD Preprint, 2026. DOI: [`10.5194/egusphere-2026-1081`](https://doi.org/10.5194/egusphere-2026-1081)




-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Python Glacier Evolution Model (PyGEM)

Overview: Python Glacier Evolution Model (PyGEM) is an open-source glacier evolution model coded in Python that models the transient evolution of glaciers. Each glacier is modeled independently using a monthly timestep. PyGEM has a modular framework that allows different schemes to be used for model calibration or model physics (e.g., climatic mass balance, glacier dynamics).  In the newest version under development, PyGEM is working to become compatible with the Open Global Glacier Model (OGGM; https://oggm.org/).

Manual: Details concerning the model physics, installation, and running the model may be found here: [https://github.com/drounce/PyGEM/wiki](https://pygem.readthedocs.io/en/latest/)

Usage: PyGEM is meant for large-scale glacier evolution modeling.  PyGEMv0.2.0 is no longer being actively being supported. We recommend using the new documentation listed above and contacting the lead developer (David Rounce) if you're interested in using the version that is actively being developed.

Contributing: We welcome contributions from any interested parties and are in the process of outlining how to best incorporate outside contributions. For the time being, if you would like to contribute to the development of the model, please contact David Rounce (drounce@cmu.edu).

Credits: If using PyGEM for scientific applications, please cite the following:
Rounce, D.R., Hock, R., Maussion, F., Hugonnet, R., Kochtitzky, W., Huss, M., Berthier, E., Brinkerhoff, D., Compagno, L., Copland, L., Farinotti, D., Menounos, B., and McNabb, R.W. “Global glacier change in the 21st century: Every increase in temperature matters”, Science, 379(6627), pp. 78-83, (2023), doi:10.1126/science.abo1324.

License: PyGEM uses an MIT license.
