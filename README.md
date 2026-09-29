# SIT307 11.1 HD – Machine Learning Research

## Project Overview

This project reproduces and critically evaluates the research paper:

M. Bhagat, A. Sharma, and P. Agarwal, “An efficient stacking-based ensemble technique for early heart attack prediction,” Multimedia Tools and Applications, 2025.

The project investigates the reproducibility of the published results and develops a leakage-aware stacking approach using feature selection and stratified cross-validation.

## Repository Contents

- `SIT307_11_1_HD.ipynb` – complete reproduction, analysis and proposed-method implementation.
- `heart.csv` – heart disease dataset used in the experiments.
- `README.md` – project setup and reproduction instructions.
- `requirements.txt` – required Python packages.

## Dataset

The dataset contains:

- 1,025 observations
- 14 columns
- 13 input features
- 1 binary target variable
- 723 duplicate observations
- 302 unique observations

Columns:

`age, sex, cp, trestbps, chol, fbs, restecg, thalach, exang, oldpeak, slope, ca, thal, target`

## Environment

The notebook was developed and tested using Anaconda and JupyterLab.

Activate the Anaconda environment:

```bash
conda activate base