# Multi-Modal Adverse Drug Reaction Prediction with Exploratory Data Analysis of Cancer-Specific Drug Sensitivity and Gene Expression Patterns

![image](format.jpg)

A comprehensive research project developing explainable machine learning models for **drug sensitivity prediction** across diverse cancer types. The framework integrates **chemical structure data (SMILES, molecular fingerprints)** and **gene expression profiles** from 735 genes to classify compound sensitivity using multi-modal learning approaches.

**Key Features:**
* **Multi-modal architecture:** CNN for SMILES processing, MLP for molecular fingerprints, and dual-branch fusion networks.
* **Large-scale dataset:** 92,563 samples with comprehensive preprocessing, achieving 0% missing values and balanced class distribution.
* **Cancer-specific insights:** Analysis across multiple cancer types revealing differential drug sensitivity patterns (Pancreatic: 92% vs. Leukemia: 76%).
* **Gene expression analysis:** Identification of cancer subtype clustering and minimal gene redundancy (only 1/435 gene pairs highly correlated).
* **Interpretability framework:** SHAP analysis for model explainability and chemical substructure identification.
* **Robust methodology:** Stratified train/validation/test splits (70/15/15) with systematic outlier detection and feature standardization.
* **Biological validation:** Expression-based cancer clustering aligns with anatomical and developmental origins.

**Research Impact:**
Focus on precision oncology through data-driven drug sensitivity profiling, enabling personalized treatment strategies across diverse cancer subtypes with emphasis on model interpretability and clinical applicability.
