# TNBC-single-cell-markers
Reproducible code for identifying TIL-based markers from single-cell RNA-seq data of TNBC patients

### Abstract

Triple-negative breast cancer (TNBC) is an aggressive subtype often resistant to neoadjuvant chemotherapy (NAC). Tumor-infiltrating lymphocytes (TILs) are promising predictors of response, but existing signatures lack resolution and cross-platform validation. Here, using a single-cell RNA sequencing (scRNA-seq) dataset of pre-treatment TNBC tumors, we identified a robust 80-gene TIL-specific signature that captures immune activation and stratifies tumors by TIL abundance. Pathway analysis showed enrichment of immune-regulatory pathways, including allograft rejection, consistent with adaptive immune activity. Validation across single-cell and bulk datasets linked the signature to favorable response and relapse-free survival. Using a robust multi-stage feature selection pipeline, we refined the panel to 30 genes, achieving strong predictive performance for pathological complete response (pCR) vs. residual disease (RD) across eleven microarray-based independent TNBC cohorts (N = 680; mean AUROC 0.77, accuracy 0.78, sensitivity 0.73, and specificity 0.8). Network analysis identified 10 consensus hub genes (e.g., CD8A, LCK, CTLA4) central to T cell signaling and enriched in responders. Regulatory analysis across three independent TNBC single-cell datasets further revealed a conserved set of TIL-associated transcription factors consisting of ZNF831, ZNF80, SP140L, IKZF3, and SCML4, that showed strong and reproducible activation in TIL-High (immune-inflamed) cells, confirming a stable upstream regulatory program driving the hub-gene module. This study highlights an immunologically active tumor subpopulation that is predictive of chemosensitivity and provides a validated biomarker panel for the stratification and therapeutic targeting of TNBC. 


### Datasets required to run the codes
All associated datasets required to run the R codes and the python notebooks have been deposited in Zenodo: https://doi.org/10.5281/zenodo.14789164


