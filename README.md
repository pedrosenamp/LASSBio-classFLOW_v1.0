# LASSBio-classFLOW_v1.0
LASSBio-classFLOW is a freely available, semi-automated workflow developed in the KNIME Analytics Platform to support the construction, optimization, evaluation, and application of binary classification QSAR models.

The workflow integrates data cleaning and preparation, configurable assignment of active and inactive classes, optional exclusion of compounds near the activity cutoff, molecular representation generation, stratified training/test splitting, hyperparameter optimization, and side-by-side benchmarking of nine machine-learning classifiers. Model performance is assessed using five-fold cross-validation within the training set and an independent, untouched test set. Multiple evaluation metrics are reported, including accuracy, recall, specificity, precision, F1-score, ROC-AUC, and Cohen’s kappa.

LASSBio-classFLOW automatically generates interactive visualizations and CSV outputs to facilitate model comparison and selection. Selected models can subsequently be applied to the virtual screening of new chemical libraries.

This repository contains the KNIME workflow, input and processed datasets, and results associated with the ROCK2 inhibitor case study described in the accompanying article. The workflow is intended for appropriately curated chemical and biological datasets and does not replace comprehensive data curation procedures.
