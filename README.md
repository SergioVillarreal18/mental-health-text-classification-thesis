# Supplementary Materials for Master's Thesis

This repository contains supplementary computational materials for the master's thesis:

**Comparative Classification of Short Mental-Health-Related Texts Using Lexical and Semantic Representations**

Author: Sergio Andres Villarreal Moyano  
Programme: Data Science  
University: WSB University  
Year: 2026  

## Repository Contents

- `data_source/`: information about the original Kaggle dataset source. The dataset itself is not redistributed in this repository.
- `notebook/`: implementation notebook used to reproduce the experiment and exported results.
- `outputs/`: CSV files exported from the notebook, including cross-validation results, final hold-out results, classification report, confusion matrix, class-level metrics, and lexical feature inspection outputs.
- `figures/`: PNG figures generated from the notebook and used in the thesis.
- `thesis_document/`: PDF version of the thesis document, including references and annexes.

## Methodological Note

The study compares lexical TF-IDF representations and semantic sentence embeddings for supervised classification of short mental-health-related text statements. The task is framed as a non-clinical computational classification problem. The outputs should not be interpreted as diagnostic evidence, clinical screening, or clinical assessment.

## Reproducibility Note

Some exported files were renamed with shorter descriptive names for clarity while preserving their original content. The original dataset is not redistributed in this repository and should be downloaded directly from the Kaggle source listed in data_source/.
