# AIDev-2a-Git
This repository contains two Jupyter notebooks analyzing Agentic Pull Requests (Agentic-PRs) from the AIDev dataset, focusing on research question 2a: "How do Agentic-PRs change code (e.g., additions, deletions, files touched)? How consistent are their descriptions with the actual code changes?" The analysis was performed using Google Colab and draws from the AIDev preprint, which aggregates 932,791 Agentic-PRs across 116,211 GitHub repositories.

#Repository Structure

Quantitative_analysis.ipynb: Loads dataset, computes descriptive statistics, performs pairwise comparisons, and generates visualizations.

Qualitative_analysis.ipynb: Merges data, computes semantic similarities, runs ANOVA and correlations, and creates plots.

Report: A complete report on the conducted research.

#Requirements

Python 3.10+
Libraries: pandas, numpy, scipy, seaborn, matplotlib, sentence-transformers, huggingface_hub

Install via: pip install pandas numpy scipy seaborn matplotlib sentence-transformers huggingface_hub

Dataset: Loaded from Hugging Face.

#How to Run

Open the notebooks in Google Colab (recommended, as the work was done there).

Mount Google Drive: from google.colab import drive; drive.mount('/content/drive').

Install dependencies in Colab.

Execute cells sequentially; notebooks include data loading, analysis, and visualizations.
