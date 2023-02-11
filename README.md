# Webpage Phishing Detection 

By: ECI.

Version: 0.1.0

Webpage Phishing Detection Type of data: tabular Type of problem: binary classification Task: Detecting phishing websites Target column: status

## Prerequisites

- [Anaconda](https://www.anaconda.com/download/) >=4.x
- Optional [Mamba](https://mamba.readthedocs.io/en/latest/)

## Create environment

```bash
conda env create -f environment.yml
activate webpage_phishing_detection
conda install numpy scipy matplotlib scikit-learn seaborn
```

or 

```bash
mamba env create -f environment.yml
activate webpage_phishing_detection
```

## Project organization

    webpage_phishing_detection
        ├── data
        │   ├── processed      <- The final, canonical data sets for modeling.
        │   └── raw            <- The original, immutable data dump.
        │
        ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
        │                         the creator's initials, and a short `-` delimited description, e.g.
        │                         `1.0-jvelezmagic-initial-data-exploration`.
        │
        ├── .gitignore         <- Files to ignore by `git`.
        │
        ├── environment.yml    <- The requirements file for reproducing the analysis environment.
        │
        └── README.md          <- The top-level README for developers using this project.

---
Project created for demonstration
