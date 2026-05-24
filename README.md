# scRNA-seq PBMC Analysis

End-to-end single-cell RNA sequencing analysis of 2,700 human peripheral 
blood mononuclear cells (PBMCs) using the 10x Genomics PBMC 3k dataset.

## Biological Question
Which distinct immune cell populations exist in human blood, and what 
genes define each population?

## Pipeline
QC and filtering → Normalization → PCA → UMAP → Leiden clustering → 
Cell type annotation → Differential expression

## Key Findings
- Identified 8 distinct immune cell clusters from 2,700 cells
- Annotated T cells (CD3D+), B cells (MS4A1+), NK cells (GNLY+), 
  and monocytes (LYZ+) using canonical marker genes
- Differential expression confirmed distinct transcriptional signatures 
  per cell type

## Dataset
10x Genomics PBMC 3k — 2,700 cells x 32,738 genes, healthy human donor

## Tools
Python, Scanpy, AnnData, matplotlib, seaborn
