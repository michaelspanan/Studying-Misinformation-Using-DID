# Studying-Misinformation-Using-DID

## Misinformation and Deplatforming on Twitter: An Exploration and Replication

This repository contains code and analysis adapted from a coursework project that engages with the findings of the 2024 *Nature* publication:**"Post-January 6th deplatforming reduced the reach of misinformation on Twitter"** by McCabe et al.

## 📘 Original Study Summary

The paper investigates Twitter’s decision to deplatform 70,000 misinformation-spreading accounts after the January 6th Capitol riot. Using panel data from over 500,000 Twitter users, the authors applied natural experimental designs,including Regression Discontinuity (SRD) and Difference-in-Differences (DID), to assess the impact of deplatform on the spread of misinformation.

## 📁 Repository Contents

- `data-simulation-and-regression.ipynb`: EDA related to identifying misinformation patterns and applying regression methods.
- `analysis.ipynb`: Follow-up analysis expanding on difference-in-differences techniques and subgroup comparisons.

## 🧪 Methods

- **Causal Inference**: Sharp Regression Discontinuity (SRD) and Difference-in-Differences (DID) approaches.
- **Data Analysis**: Python-based processing of tweet metadata, user behavior, and misinformation labeling.
- **Focus**: Replicating and interpreting key findings.

## 🎯 Goals

- Reproduce core findings from McCabe et al. (2024)
- Experiment with alternative specifications or robustness checks
- Demonstrate application of computational social science methods

## 🚀 Getting Started

1. Clone the repo  
   ```bash
   git clone https://github.com/michaelspanan/Studying-Misinformation-Using-DID.git
   cd Studying-Misinformation-Using-DID

2. Open Jupyter notebooks
3. Ensure dependencies are installed
   ```bash
   pip install pandas numpy matplotlib seaborn statsmodels

## 🔗 Reference
McCabe, S. D., Ferrari, D., Green, J., Lazer, D. M. J., & Esterling, K. M. (2024). Post-January 6th deplatforming reduced the reach of misinformation on Twitter. Nature. https://doi.org/10.1038/s41586-024-07524-8
