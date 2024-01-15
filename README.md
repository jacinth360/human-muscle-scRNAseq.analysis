# Single cell RNA - seq analysis for muscle samples 

**Overview**

This project focuses on the comprehensive analysis of single-cell RNA sequencing data derived from four muscle samples. The analysis pipeline involves various steps, including quality control, filtering, normalization, dimensionality reduction, clustering, and marker gene expression pattern analysis using Python's Scanpy library.


**Methods**

**1. Data Processing**
* Utilized single-cell RNA sequencing data from four muscle samples.
* Conducted quality control, filtering, and normalization using Scanpy in Python.
  
**2. Dimensionality Reduction and Clustering**
* Applied dimensionality reduction techniques such as PCA (Principal Component Analysis) and t-SNE (t-distributed Stochastic Neighbor Embedding).
* Employed Leiden clustering for cell type identification.
  
**3. Marker Gene Analysis**
* Analyzed marker gene expression patterns to identify distinct cell types.
* Generated a t-SNE plot and heatmap for visualization.

**4. Alignment with Reference Study**
* Successfully aligned the results with a reference paper, revealing meaningful cellular relationships.


**Repository Structure**

_Data:_

The project leverages human single-cell RNA-seq data obtained from the GEO repository under accession number GSE130646, which includes a tar folder containing the following CSV files:

1. GSM3746212_Muscle_1_Counts.csv.gz - 1.1 Mb
2. GSM3746213_Muscle_2_Counts.csv.gz - 1.2 Mb
3. GSM3746214_Muscle_3_Counts.csv.gz - 567.4 Kb
4. GSM3746215_Muscle_4_Counts.csv.gz - 622.0 Kb

https://www.ncbi.nlm.nih.gov/geo/download/?acc=GSE130646&format=file


_References:_

1. Rubenstein, A.B., Smith, G.R., Raue, U. et al. Single-cell transcriptional profiles in human skeletal muscle. Sci Rep 10, 229 (2020). https://doi.org/10.1038/s41598-019-57110-6
2. Scanpy: Preprocessing and clustering 3k PBMCs
https://scanpy-tutorials.readthedocs.io/en/latest/pbmc3k.html
3. Scanpy: Core plotting functions
https://scanpy-tutorials.readthedocs.io/en/latest/plotting/core.html
4. Seurat’s guided clustering tutorial (Satija et al., 2015)
https://satijalab.org/seurat/articles/pbmc3k_tutorial
5. anndata: Annotated data
Isaac Virshup, Sergei Rybakov, Fabian J. Theis, Philipp Angerer, F. Alexander Wolf 
bioRxiv 2021 Dec 19. doi:10.1101/2021.12.16.473007.
https://anndata.readthedocs.io/en/latest/
6. The scverse project provides a computational ecosystem for single-cell omics data analysis. 
Isaac Virshup, Danila Bredikhin, Lukas Heumos, Giovanni Palla, Gregor Sturm, Adam Gayoso, Ilia Kats, Mikaela Koutrouli, Scverse Community, Bonnie Berger, Dana Pe’er, Aviv Regev, Sarah A. Teichmann, Francesca Finotello, F. Alexander Wolf, Nir Yosef, Oliver Stegle & Fabian J. Theis
Nat Biotechnol. 2023 Apr 10. doi: 10.1038/s41587-023-01733-8.
https://www.nature.com/articles/s41587-023-01733-8
