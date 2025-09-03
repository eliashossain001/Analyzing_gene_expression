# Gene Expression Analysis with LLMs: ALL vs AML Leukemia Case Study

This project explores how **Machine Learning (ML)**, **Deep Learning (DL)**, and **Large Language Models (LLMs)** can be applied to **gene expression data** for biological discovery. Using the classic **ALL vs AML leukemia microarray dataset**, I performed exploratory data analysis, identified significant genes, and applied an open-source biomedical LLM (**BioGPT**) to interpret results and suggest potential drug targets.  

---

## Objectives
- Understand **gene expression data** through exploratory data analysis (EDA).  
- Apply **ML techniques** (variance analysis, PCA, clustering).  
- Identify **differentially expressed genes** using statistical tests (volcano plot).  
- Use **LLMs (BioGPT)** for biological interpretation of significant genes.  
- Explore **drug target predictions** from expression patterns.  

---

## Exploratory Data Analysis
- **Class distribution**: ALL vs AML patients.  
- **Expression distribution**: Histograms of gene expression values.  
- **Top variable genes**: Variance profiling.  
- **Heatmaps**: Visualizing gene–patient clusters.  
- **PCA**: Visualizing patient separation in 2D.  
- **Volcano plot**: Identifying statistically significant genes.  

---

## LLM Integration
- **BioGPT** was used to:
  - Interpret the biological role of significant genes.  
  - Suggest potential drug targets for leukemia.  
  - Demonstrate how LLMs can bridge raw numbers → biological insights.  

Example prompt:
```text
Gene M25079 is associated with acute leukemia. Its biological role is that ...
