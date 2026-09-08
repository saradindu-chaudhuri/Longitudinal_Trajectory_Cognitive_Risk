# 🧠 Longitudinal Cognitive Trajectory & Multi-Modal Neuroimaging Risk Framework

[![Python 3.10+](https://img.shields.io/badge/python-3.10%2B-blue.svg)](https://www.python.org/)
[![Statsmodels](https://img.shields.io/badge/Statsmodels-LME%20Engine-green.svg)](https://www.statsmodels.org/)
[![Domain](https://img.shields.io/badge/Domain-Computational%20Neuroscience%20%26%20Biostatistics-purple.svg)]()

An end-to-end biostatistical pipeline designed to model multi-wave longitudinal cognitive decline trajectories, quantify neurodegenerative vs. vascular risk factors, and isolate synergistic biomarker interactions. 

Modeled after analytical workflows used in longitudinal aging cohorts (e.g., CHeBA Sydney MAS / ADNI), this repository implements **Linear Mixed-Effects (LME)** architectures to track repeated cognitive measurements (ACE-III/MMSE) across 6-year follow-up windows while accounting for subject-specific random intercepts and slopes.

---

## 📌 Executive Summary & Key Findings

* **Longitudinal Rate of Attrition:** Non-carrier baseline cognitive decline was established at **-0.50 to -0.78 ACE-III points/year** ($p < 0.001$).
* **Genetic Acceleration ($APOE\ \epsilon4$):** Carrying the $APOE\ \epsilon4$ allele lowers baseline cognitive performance and significantly accelerates rate of decay over time ($p < 0.001$).
* **Dual-Pathology Synergy:** Joint integration of structural **Hippocampal Atrophy** ($\text{mm}^3/\text{year}$) and **White Matter Hyperintensity (WMH)** lesion volume ($\text{cm}^3$) revealed a statistically significant interaction effect, proving that vascular brain injury acts synergistically with neurodegeneration to compound cognitive loss.

---

## 🛠️ Methodological Architecture
