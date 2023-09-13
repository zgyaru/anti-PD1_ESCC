# anti-PD1_ESCC

## Summary
Neoadjuvant immune checkpoint blockade (ICB) demonstrates promise in operable esophageal squamous cell carcinoma (ESCC), but lacks available efficacy biomarkers. Here, we perform single-cell RNA-sequencing of tumors from patients with ESCC undergoing neoadjuvant ICB, revealing a subset of exhausted CD8+ T cells expressing SPRY1 (CD8+ Tex-SPRY1) that displays a progenitor exhausted T cell (Tpex) phenotype and correlates with complete response to ICB. We validate CD8+ Tex-SPRY1 cells as an ICB-specific predictor of improved response and survival using independent ICB-/non-ICB cohorts and demonstrate that expression of SPRY1 in CD8+ T cells enforces Tpex phenotype and enhances ICB efficacy. Additionally, CD8+ Tex-SPRY1 cells contribute to proinflammatory phenotype of macrophages and functional state of B cells, which thereby promotes antitumor immunity by enhancing CD8+ T cell effector functions. Overall, our findings unravel progenitor-like CD8+ Tex-SPRY1 cells’ role in effective responses to ICB for ESCC and inform mechanistic biomarkers for future individualized immunotherapy.


## Platform
* Linux-3.10.0-514.el7.x86_64-x86_64-with-glibc2.10
* CentOS Linux 7 (Core)

## Scripts annotation

| Script   | Corresponding Figures  |  Language |
|:----------|:-------------|:------:|
| Clustering.ipynb | Figure 1C; Figure 1D; Figure 2A; Figure S5A; Figure S7E | Python |
| PCA_analysis.ipynb | Figure 1E; Figure S1H | Python |
| Proportion.ipynb | Figure 1G; Figure5E; Figure S1I; Figure S1K; Figure S2G | R |
| SC_geneSets_analyses.ipynb | Figure 2B; Figure 2D; Figure 6B; Figure S6H | R |
| Pseuotime_analyses.ipynb | Figure 2E; Figure S2E; Figure S2F | Python |
| Bulk_RNA_validation.ipynb | Figure 3D; Figure 3E; Figure 3F; Figure S5I; Figure S6I | R |
| Cell_cell_interaction.ipynb | Figure 5C; Figure 5D; Figure 5F; Figure 5G; Figure 6F | R |
| ScTCR_scRNA.ipynb | Figure S4 | Python |


## Session information
* R 4.1.1
* Python 3.8.8
* Seurat 4.1.1
* SeuratObject 4.1.0
* SingleCellExperiment 1.14.1
* GenomicRanges 1.44.0
* cowplot 1.1.1
* ggplot2 3.3.6
* ggrepel 0.9.1
* survival 3.2-13
* dplyr 1.0.9
* Rcpp 1.0.8.3
* data.table 1.14.2
* anndata 0.8.0
* scanpy 1.9.1
* scipy 1.7.1
* louvain 0.7.0
* scvelo 0.2.4
* sklearn 0.22
* statannot 0.2.3
* statsmodels 0.12.2
* igraph 0.9.6
* networkx 2.6.2
* matplotlib 3.6.1





