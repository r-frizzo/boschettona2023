![App Screenshot](./bosc_ghebo_nat_git_cut.png)
# boschettona2023

This repository contains the R Scripts and Genome-scale metabolic models (GEMs) used to analyse the data from the paper 
"Metabolites and flux modelling reveal viral modulation of carbohydrates, carboxylates, and nucleotide-sugars in salt marsh sediments".
Raw sequencing reads are available at NCBI (PRJNA1226540).

## Scripts

A description of the bioinformatics and biostatistics pipelines is available in the methods section of the manuscript.

- `bosc23_abiotic_measures.Rmd`<br>
Processing and analysis of granulometry, CHNS, ICP-MS, GC-MS, LC-MS data.
- `bosc23_MAG_vOTU_selection_QC.Rmd`<br>
Selection of metagenome-assembled genomes (MAGs) and screening of identified viral sequences.
Descriptive statistics.
- `bosc23_MAG_vOTU_taxonomy.Rmd`<br>
Processing, analysis and visualisation of MAG and vOTUs taxonomy and relative abundance data.
- `bosc23_integrative_analysis.Rmd`<br>
Analysis of GEMs and integration with metagenomics, viromics, and metabolomics data

## GEMs available at: https://figshare.com/s/a9e23bab7e9995b3fd7b
  Compressed archives containing all Genome-scale metabolic models analysed in the manuscript, in .xml and .RDS format.
