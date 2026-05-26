---
layout: single
title: "Research"
permalink: /research/
author_profile: true
---

My research sits at the intersection of genomics and computation — I'm most interested in understanding how non-coding regulatory elements shape cell identity and disease, and in building the tools that make that understanding possible at scale.

## Cis-Regulatory Element Mapping

At UC San Diego, I lead the development of **pgBoost**, a consensus Snakemake pipeline that links cis-regulatory elements (CREs) to their target genes in a cell-type-resolved way. pgBoost integrates four chromatin accessibility–based tools — Signac, Cicero, ABC, and SCARlink/ArchR — across 37+ cell types, and benchmarks predictions against Hi-C loops and eQTL enrichment. The results are actively informing work in the IGVF Consortium, PanKBase, and a lung manuscript in preparation.

## Cell-Cell Communication

I've built two complementary pipelines using LIANA+ to model how cells talk to each other:

- **Ligand-receptor signaling** — run per sample across 65 donors (ND, T1D, T2D, AAB+), applying six consensus scoring methods with a custom visualization toolkit for cross-disease comparison.
- **Metabolite-mediated signaling** — estimates metabolite abundances from scRNA-seq via enzyme production/degradation and transporter networks (MetalinksDB), then connects those estimates to receptor expression to map metabolite-sensor intercellular signaling.

## Differential Expression & Disease Genomics

I developed a pseudobulk differential expression pipeline (DESeq2 + RUVSeq) with a custom k-optimization algorithm that anchors latent factor selection to known biological covariates while preventing overcorrection of disease signal. Containerized in Docker and deployed as interactive Jupyter notebooks in the PanKBase Analytical Library.

## Earlier Work

- **AbbVie / Google Calico Labs**: End-to-end genomic analysis on Duchenne muscular dystrophy patient datasets — array QC, expression profiling, normalization, pathway enrichment.
- **Merck KGaA (EMD Serono)**: Differential expression across 6 cancer cohorts to support immuno-oncology target identification.
- **Vidyasagar Institute**: In silico structural modeling of MTHFR missense mutations linked to homocystinuria — contributed to a [peer-reviewed publication](https://doi.org/10.1016/j.mrfmmm.2020.111687).
