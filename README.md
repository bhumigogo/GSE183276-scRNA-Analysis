# GSE183276 scRNA-seq Analysis
This repository contains single-cell RNA sequencing (scRNA-seq) analysis for the GEO dataset GSE183276.

## Project Overview
The analysis includes:
- Quality control and preprocessing
- Batch correction and dimensionality reduction
- Cell clustering and UMAP visualization
- Cell type annotation
- Differential gene expression (DEG) analysis
- GO enrichment analysis
- KEGG pathway analysis
- Marker gene identification
- ## Hypothesis
## Research Hypothesis
The analysis aimed to investigate how kidney injury and disease alter cellular composition,
transcriptional states, and biological pathways at single-cell resolution in GSE183276.
Using scRNA-seq analysis, the study identifies disease-associated cell populations, differential gene
expression patterns, and dysregulated molecular pathways involved in kidney dysfunction, 
immune activation, and injury-related cellular responses.

## Repository Structure
### output/
Contains processed outputs including:
- DEG result tables
- Marker gene tables
- GO enrichment results
- KEGG enrichment results
- Processed Seurat objects

### plots/
Contains visualization files including:
- UMAP plots
- Heatmaps
- Volcano plots
- GO enrichment plots
- KEGG pathway plots
- QC plots

## Dataset
GEO Accession: GSE183276

## Tools and Packages
- Seurat
- Harmony
- CellTypist
- clusterProfiler
- ggplot2
