# lotss-dr2-agn-analysis

This repository contains analysis code and visualizations related to the paper:

**"Radio AGN selection in LoTSS DR2"**  
*Hardcastle et al., 2025, MNRAS, [arXiv:2504.09303](https://arxiv.org/abs/2504.09303)*

---

## Objective

The primary goal of this project is to reproduce **Figure 11** of the paper - the **The luminosity function of LOFAR RLAGN as a function of redshift** using the publicly released LoTSS DR2 AGN catalog.

Additional objectives include:

- Overlaying LOFAR sources on optical imaging
- Fitting Gaussian models to LOFAR radio sources
- Comparing source properties with public catalogs

---

## Repository Structure

```bash
lotss-dr2-agn-analysis/
│
├── data/                      # Contains or links to FITS catalogs (not committed)
├── notebooks/                 # Jupyter notebooks for exploration and plots
├── scripts/                   # Reusable Python modules or tools
├── plots/                     # Reproduced figures and diagnostics
├── requirements.txt           # Python dependencies
├── .gitignore                 # Ignore large files like .fits
└── README.md                  # This file