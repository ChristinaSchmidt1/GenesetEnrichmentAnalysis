# Geneset Enrichment Analysis (GEA)

This repository includes different types of GEA and automated visualisation for both, human and mouse gene names.

## GSEA
Gene Set Enrichment Analysis (GSEA) is used to understand small coordinated changes, meaning it detects gene sets where most of the genes of this gene set change in a coordinated way. This determines whether members of the gene set are randomly distributed troughout the ranked list or primarily found on the top or bottom.
As input a ranked list of genes is required, wherby ranking according to the t-value is preferred, yet ranking by Log2FC is also possible. Usually the input originates from RNAeq or porteomics experimentsafter performing a differential expression analysis using EdgeR or DESeq2. 
