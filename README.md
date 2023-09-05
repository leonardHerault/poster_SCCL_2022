# Metacells facilitate the analysis of single-cell multiomics data

[Poster](BC2_2023.html) presented at Basel Computational Biology Conference 11 - 13 September 2023

### Abstract

Single-cell multiomics enables the measurement of different modalities (e.g., chromatin accessibility, RNA, proteins) in the same cell. Combined with the increased throughput of single-cell technologies, these advances hold the promise for a better understanding of cell-type specific transcriptional regulation and its potential alteration. Computational tools play a central role in the analysis of such complex data to cope with their high sparsity, which blurs the correlation between the modalities, and the constant increase in cell and sample numbers in single-cell atlases. To address these needs, metacells, defined as groups of disjoint and very similar cells corresponding to highly granular cell states, can be identified in single-cell omics data and used for downstream analyses.

To date, few studies have focused on metacell approaches for multiomics data and the tools currently available only consider one modality for metacell identification despite evidence that cellular heterogeneity is better resolved with multimodal analysis. Thus, building upon the SuperCell framework our lab developed for single-cell RNA-seq [1], we have developed a new metacelll identification approach relying on multimodal graph clustering and investigated how multiomics metacells preserve or enhance the biological signal observed at the single-cell level.

Our results on single-cell multiomics datasets of peripheral blood mononuclear cells (PBMCs) show that metacells preserve the overall structure of the single-cell data and reconcile the different modalities. In particular we observe a significant increase between gene body chromatin accessibility and its expression for 10X multiome data and between gene expression and the corresponding surface protein abundance for CITE-seq data. We then integrated at the metacell level a CITE-seq atlas composed of 18 samples gathering more than 160'000 PBMCs on a standard laptop in 30 minutes, highlighting the interest in metacell approaches to save computational resources. Finally, we were able to show that our multimodal approach outperforms other tools in terms of accuracy and speed.

Overall, we have demonstrated that metacells can be used to analyze single-cell multiomics and improve the consistency between different modalities while significantly accelerating and facilitating data analysis.

1- [Bilous et al. Metacells untangle large and complex single-cell transcriptome networks, BMC Bioinformatics (2022).](https://doi.org/10.1186/s12859-022-04861-1)
