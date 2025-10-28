Single-Cell RNA Sequencing Analysis of COVID-19 Lung Tissue
Overview
This repository contains a comprehensive single-cell RNA sequencing analysis pipeline for studying cellular heterogeneity in COVID-19 affected lung tissue compared to healthy controls. The analysis leverages state-of-the-art computational methods to identify cell types, differential expression patterns, and pathway alterations associated with SARS-CoV-2 infection.

Dataset
Source: GSE171524

Description: Single-cell RNA sequencing data from lung tissue samples of COVID-19 patients and healthy controls

Samples: Multiple samples from both COVID-19 affected and control lung tissues

Key Features
Doublet Detection: Automated identification and removal of doublets using SOLO

Quality Control: Comprehensive QC metrics including mitochondrial and ribosomal gene content

Batch Correction: Integration of multiple samples using scVI for batch effect removal

Cell Type Annotation: Manual annotation of 29 distinct cell populations

Differential Expression: Multi-method DE analysis between conditions and cell types

Pathway Analysis: Gene set enrichment analysis using Enrichr

Visualization: UMAP projections, violin plots, and heatmaps for result interpretation

File Structure
combined.h5ad - AnnData object containing merged data before batch correction

integrated.h5ad - AnnData object after scVI integration and batch correction

KEGG_RIBOSOME.v2025.1.Hs.tsv - Ribosomal gene set for quality control
