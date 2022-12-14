# anti-PD1_ESCC

## Summary
Neoadjuvant immune checkpoint blockade (NICB) has shown promise in esophageal squamous cell carcinoma (ESCC). However, the factors that render certain patients more responsive to NICB with complete regression/response (CR) remains elusive. We applied single-cell RNA-sequencing to examine tumors from patients with ESCC before and after NICB from a phase 2 clinical trial. We identiﬁed key tumor immune microenvironment subpopulations relevant to CR, along with candidate cell-cell interactions. Speciﬁcally, we linked exhausted SPRY1+CD8+T cells in ESCC to progenitor phenotype and CR prediction under NICB, as validated by multiplex immunohistochemistry and flow cytometry in a prospective cohort. Additionally, we elucidated its critical interactions regulating the proinflammatory phenotype of macrophages and the functional state of B cells, which in turn promoted antitumor immunity by enhancing CD8+T cell effector functions. Our data shed light on tumor microenvironment in effective response to NICB for ESCC and provide foundational resources for future mechanistic studies.


## Platform
* Linux-3.10.0-514.el7.x86_64-x86_64-with-glibc2.10
* CentOS Linux 7 (Core)

## Scripts annotation

| Script   | Corresponding Figures  |  Language |
|:----------|:-------------|:------:|
| Clustering.ipynb | Figure 1C; Figure 1D; Figure 2A; Figure 4A; Figure S7E | Python |
| PCA_analysis.ipynb | Figure 1E; Figure S1G | Python |
| Proportion.ipynb | Figure 1G; Figure 5A; Figure S1H; Figure S1G; Figure S2F; Figure S6F | R |
| SC_geneSets_analyses.ipynb | Figure 2B; Figure 2D; Figure S2C; Figure 6D; Figure 6E | R |
| Pseuotime_analyses.ipynb | Figure 2E; Figure S2D; Figure S2E; Figure S2G| Python |
| Bulk_RNA_validation.ipynb | Figure 3B; Figure 5B; Figure 6H | R |
| Cell_cell_interaction.ipynb | Figure 4F; Figure 4G; Figure 5C; Figure 5D; Figure 6J; Figure 6K; Figure 6L | R |
| ScTCR_scRNA.ipynb | Figure S5 | Python |


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





