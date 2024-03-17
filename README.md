# scGAIN
scGAIN: Single Cell RNA-seq Data Imputation using Generative Adversarial Networks

Code repository for paper: https://www.biorxiv.org/content/10.1101/837302v1 
Si, Tong, Zackary Hopkins, John Yanev, Jie Hou, and Haijun Gong. "A novel f-divergence based generative adversarial imputation method for scRNA-seq data analysis." Plos one 18, no. 11 (2023): e0292792.

### Contents:

**gainMain_PBMC.py**: Code to train and evaluate scGAIN model on PBMC dataset  
**gainMain_simSplatter.py**: Code to train and evaluate scGAIN model on simulated dataset (see next file)  
**run_tools.R**: Utilities including data simulation using Splatter (https://www.bioconductor.org/packages/splatter)  
**run_TSNE.R**: Script to generate figures using t-SNE
