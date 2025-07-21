# DASS Survey Exploration on Mental Health 

This repository contains a data science project analyzing patterns in depression, anxiety, and stress based on standardized survey responses. This project applies data science techniques to uncover mental health trends across diverse groups.

## 💡 Project Focus

- Quantitative analysis of mental health scores using DASS-42
- Exploratory analysis of demographic and personality factors
- Visual interpretation and extencive analysis

## 📊 Dataset

- Source: [Kaggle – DASS Responses](https://www.kaggle.com/datasets/lucasgreenwell/depression-anxiety-stress-scales-responses)
- Includes DASS-42 survey scores, TIPI personality data, and participant metadata
- ~40,000 responses collected online between 2017–2019

## 🛠️ Tech Stack

- Python 3.9
- Jupyter Notebook
- Conda 22.9

## 📦 Libraries & Versions

- `pandas` 1.4.4 – Data manipulation
- `numpy` 1.21.5 – Numerical operations
- `matplotlib` 3.5.2 – Plotting
- `seaborn` 0.11.2 – Statistical visualization
- `geopandas` 0.12.2 – Country-level choropleth maps for visualizing aggregated metrics
- `pymongo` 4.3.3 – MongoDB interaction
- `pycountry` 22.3.5 – Country code mapping
- `mrjob` 0.7.4 – MapReduce jobs (if applicable)

> Some libraries may not be directly used in the notebook but are part of the environment setup.

## 🧪 File Structure

- `Mental-Health.ipynb` – Main notebook with full analysis and visualizations
- `README.md` – Documentation and usage instructions

## 🚀 Getting Started

### Create and activate the environment:

```bash
conda create -n mental_health_env python=3.9
conda activate mental_health_env
```

### Install required packages:

```bash
conda install pandas numpy matplotlib seaborn geopandas
pip install pymongo pycountry mrjob
```

### Launch the notebook:

```bash
jupyter notebook Mental-Health.ipynb
```

## 📈 Deliverables

- Cleaned and preprocessed dataset
- EDA visualizations: distributions, correlations, group comparisons
- Observational insights on mental health patterns
- Reproducible workflow in Jupyter Notebook

---

