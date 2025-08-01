# Single-Cell RNA-seq Analysis of Glioblastoma Tumors

This project uses single-cell RNA sequencing (scRNA-seq) to explore tumor heterogeneity in glioblastoma (GBM) by analyzing three publicly available datasets. The study focuses on cell-type clustering, quality control, dimensionality reduction, and differential gene expression to identify tumor subpopulations and potential therapeutic biomarkers.

Developed collaboratively at Columbia University for ECBME4060: Introduction to Genomics Science and Technology.

---

## 📊 Overview

- **Datasets used:**  
  - GSE131928 (adult and pediatric glioblastomas)  
  - GSE173278 (primary tumors and matched organoids)  
  - GSE273275 (spatial transcriptomics GBM sample)

- **Key Analyses:**  
  - Quality control via transcript/gene counts and mitochondrial fraction  
  - PCA and UMAP for dimensionality reduction  
  - Leiden clustering and marker gene identification  
  - Differential gene expression (e.g. EGFR, PDGFRA, OLIG2, CRABP2)

## 🔬 Key Findings

- Identified distinct malignant subpopulations in both pediatric and adult GBM tumors.
- Top overexpressed genes across clusters included **EGFR**, **PDGFRA**, **OLIG2**, **CRABP2**, **MEST**, and **TIMP1**.
- Clusters corresponded with known tumor states and immune infiltration profiles.
- Visualizations such as UMAP and violin plots highlighted the heterogeneity of GBM.

## 📦 Setup Instructions

> Requires Python 3.8+  
> Recommended to use a virtual environment

```bash
pip install scanpy pandas matplotlib seaborn scipy anndata


