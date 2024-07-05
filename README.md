# Casp1Aldh1l1-scRNAseq
R code and relevant files used for the analysis of hippocampal scRNAseq data from Casp1(fl/fl) Aldh1l1-CreERT2(+/-) mice and littermate controls.

The raw data from the sequencing run are too large to upload here and will be posted elsewhere. These files are necessary to run the code from the very beginning and include the barcodes, features, and matrix gz files stored in the following folder names: ctrl_raw_feature_bc_matrix, tx_raw_feature_bc_matrix. 

R code should be run in the following order:
1. Setup: includes data processing, QC steps, PCA and tSNE clustering, cluster identification
2. Subclustering: includes re-clustering of cell type-specific subclusters (for astrocytes, neurons, microglia, and oligodendrocyte lineage cells)
3. DEA: differential expression analysis using zinbwave conducted on each cell type

The final R markdown file (Reviewers) was tacked on during the reviewing stage and includes plots and additional analyses requested by the reviewers. 
