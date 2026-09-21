# Soccer Player Performance & Valuation Analytics

An end-to-end data science project analyzing what drives professional soccer player market valuations — built as part of an individual, semester-long Machine Learning course project.

**Live site:** [https://karan-cheemalapati.github.io/Soccer-Analytics/](https://karan-cheemalapati.github.io/Soccer-Analytics/)

## Overview

This project explores player performance, physical attributes, and career data to understand how transfer market valuations are determined. Over the course of the semester, it applies the full data science lifecycle — from data collection and cleaning through exploratory analysis, unsupervised learning (clustering, PCA), and supervised modeling (Naive Bayes, Decision Trees, SVMs, Regression, Neural Networks) — to a real-world sports analytics dataset.

## Data Sources

- **[Football Data from Transfermarkt](https://www.kaggle.com/datasets/davidcariboo/player-scores)** (Kaggle) — player profiles, career appearances, and market valuation history for 50,000+ professional players.
- **[football-data.org API](https://www.football-data.org/)** — live standings and match data for major European competitions.

## Tech Stack

- **Python** (pandas, matplotlib, seaborn) — data processing, cleaning, and visualization
- **Quarto** — multi-page website generation
- **GitHub Pages** — site hosting/deployment

## Project Structure

- `index.qmd` — Introduction
- `dataprep_eda.qmd` — Data collection, cleaning, and exploratory analysis
- `clustering.qmd` — Clustering analysis
- `pca.qmd` — Principal Component Analysis
- `naivebayes.qmd` — Naive Bayes classification
- `dectrees.qmd` — Decision Trees
- `svms.qmd` — Support Vector Machines
- `regression.qmd` — Regression modeling
- `nn.qmd` — Neural Networks
- `conclusions.qmd` — Final conclusions
- `notebooks/` — Jupyter notebooks with data processing code
- `images/` — Visualizations and data preview images
- `data/api_raw/` — Saved API pull outputs
- `_quarto.yml` — Site configuration and navigation


Note: raw and processed datasets are excluded from this repository via `.gitignore` due to file size — see the Data Sources section above and the DataPrep_EDA page on the live site for direct links.

## Running Locally

```bash
git clone https://github.com/karan-cheemalapati/Soccer-Analytics.git
cd Soccer-Analytics
quarto preview
```

## Author

Karan Cheemalapati — [GitHub](https://github.com/karan-cheemalapati)
