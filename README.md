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

**Full research archive:** [**Zenodo research package — concept DOI 10.5281/zenodo.18761729**](https://doi.org/10.5281/zenodo.18761729)

**Stable release:** [`v1.0.0-zenodo-pygem-rt`](https://github.com/Ruitangtang/PyGEM/releases/tag/v1.0.0-zenodo-pygem-rt)

🚀 Lightweight showcase repo: [**Ruitangtang/frontal-ablation-glacier-demo**](https://github.com/Ruitangtang/frontal-ablation-glacier-demo) — YAML configs, dry-run quickstart commands, tests, method/results visuals, and reproducibility links.

**Citation:**
> Yang et al. *Joint Bayesian Calibration of Frontal Ablation and Surface Mass Balance in Global Glacier Models*. GMD Preprint, 2026. DOI: [`10.5194/egusphere-2026-1081`](https://doi.org/10.5194/egusphere-2026-1081)


