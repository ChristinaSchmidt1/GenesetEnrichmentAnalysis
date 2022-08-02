# Geneset Enrichment (GSE)

This repository includes different types of GSE methods and automated visualisation for both, human and mouse gene names.

GSE methods have been developed to find dysregulated groups of genes using gene set collections of biological pathways/molecular networks. Hence, performing GSE methods using gene sets reduces the data to smaller, more interpretable sets of altered signalling pathways or processes.

## Gene Sets
The biggest resource to capitalise on gene sets is the Molecular signatures database (MsigDB). This gene set collection extracted signatures from original research publications and imports entire collections such as Gene ontology (GO) or the Kyoto encyclopedia of genes and genomes (KEGG).

Here I downloaded different gene sets from the MSigDB I commonly use (Biocarta, Reactome, KEGG, Hallmarks and GO-terms), as well as a gene set of metabolic pathways based on Recon2 that has been developed aspart of the work of Gaude et. al. 

## GSEA
Gene Set Enrichment Analysis (GSEA) is used to understand small coordinated changes, meaning it detects gene sets where most of the genes of this gene set change in a coordinated way. This determines whether members of the gene set are randomly distributed troughout the ranked list or primarily found on the top or bottom.

As input a ranked list of genes is required, wherby ranking according to the t-value is preferred, yet ranking by Log2FC is also possible. Usually the input originates from RNAeq or porteomics experimentsafter performing a differential expression analysis using EdgeR or DESeq2. 
