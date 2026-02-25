# Stroke Transcriptomic Analysis (Work in Progress)

## Project Overview
This project focuses on analyzing transcriptomic patterns from the GSE16561 dataset to explore molecular signatures associated with stroke.  
It is intended solely for research purposes and hypothesis generation.  

---

## Objectives
- Import and preprocess gene expression data from GSE16561  
- Explore transcriptomic patterns associated with stroke  
- Apply feature selection and dimensionality reduction methods (e.g., PCA, DE analysis)  
- Develop analytical pipelines to generate hypotheses for further research  
- Document the workflow for reproducibility and clarity  

---

## Project Structure
stroke_predictions/
├── data/ # Raw and processed datasets
├── notebooks/ # Exploratory analysis and model experiments
├── src/ # Reusable Python modules (work in progress)
├── requirements.txt # Project dependencies
├── README.md # This file

---

## Dataset
- **Source:** [GEO Accession GSE16561](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE16561)  
- **Description:** Microarray gene expression dataset containing samples from stroke patients and controls.  
- **Current status:** Dataset has been imported; preprocessing, normalization, and feature selection are upcoming.

---

## Current Status
- [x] Repository structure created
- [x] Raw dataset downloaded from GEO (GSE16561)
- [ ] Data cleaning and preprocessing implemented
- [ ] Exploratory data analysis (EDA) performed
- [ ] Feature engineering / selection planned
- [ ] Initial ML model training pipeline in progress (logistic regression, tree-based models)
- [ ] Model evaluation setup (cross-validation, metrics)
- [ ] Refactoring into reusable modules started
- [ ] Results visualization and documentation in progress

> **Note:** This project is in active development. Code and functionality will be added incrementally.

---

## Planned Steps / Roadmap
1. Explore and preprocess the dataset (QC, normalization, batch correction)  
2. Perform feature selection and dimensionality reduction (PCA, DE analysis)  
3. Train baseline ML models (Elastic Net, Random Forest) and evaluate (accuracy, F1-score, ROC-AUC, precision/recall)  
4. Add interpretability (SHAP, permutation importance, feature ranking stability)  
5. Refactor code into reusable modules and document pipeline for reproducibility  
6. Visualize results (feature importance, confusion matrices, PCA/UMAP plots)  
7. Perform pathway and network analysis (GO, KEGG, Jaccard overlap)  
8. Build an interactive dashboard integrating models, clusters, gene importance, and pathway insights  

---

## Installation (Coming Soon)
Instructions for installing dependencies and running scripts will be added once the pipeline is functional.

---

## Notes
This project demonstrate:
- Structured project planning and incremental workflow  
- Reproducible data analysis with clear preprocessing steps 
- Machine learning pipeline development and evaluation 
- Code organization and modularity  
- Experience with real bioinformatics datasets (GEO microarray data)


