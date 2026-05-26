---
layout: single
title: "Projects"
permalink: /projects/
author_profile: true
---

A selection of pipelines and tools I've built — mostly for genomics, mostly on HPC, always with reproducibility in mind.

---

### pgBoost
**Consensus CRE–gene linking pipeline** | Snakemake, Python, R, SLURM

A multi-tool consensus pipeline integrating Signac, Cicero, ABC, and SCARlink/ArchR to link cis-regulatory elements to target genes across 37+ cell types. Includes benchmarking against Hi-C loops and eQTL enrichment. Built for and actively used by the IGVF Consortium, PanKBase, and the FNIH multi-tissue initiative.

---

### Cell-Cell Communication Pipelines (LIANA+)
**Ligand-receptor & metabolite-sensor signaling** | Python, LIANA+, MetalinksDB

Two pipelines for modeling intercellular communication from single-cell RNA-seq data: one for ligand-receptor interactions across 65 donors with six scoring methods, and one for metabolite-mediated signaling via enzyme/transporter network modeling.

---

### Pseudobulk DE Pipeline
**Differential expression with adaptive latent factor selection** | R, DESeq2, RUVSeq, Docker, Jupyter

A DESeq2 + RUVSeq pipeline with a custom k-optimization algorithm for selecting the right number of latent factors without over-correcting disease signal. Containerized in Docker and deployed as interactive notebooks in the PanKBase Analytical Library.

---

### ATAC Fragment Splitter
**Cell-type-stratified fragment extraction at scale** | Python, bedtools, SLURM

Scripts to split a 200 GB multi-sample ATAC-seq archive into per-cell-type fragment files, enabling downstream ArchR execution across all 37 cell types without memory or I/O failure.

---

### NGS Analysis Workflows (Stoke Therapeutics)
**RNA-seq, splicing, and qPCR pipelines** | Python, Snakemake, FastQC, STAR, RSEM, deeptools, AWS

Core sequencing analysis workflows with testing and documentation, running on AWS cloud infrastructure. Supported ongoing therapeutic programs with publication-quality visualizations.

---

### RShiny Gene Expression Explorer
**Interactive visualization app** | R, Shiny, Genedata Profiler

Web app for interactive exploration of gene expression and fold-change comparisons across 6 cancer cohorts, built during a co-op at Merck KGaA (EMD Serono) to support immuno-oncology target identification.
