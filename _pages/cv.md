---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* M.S. Bioinformatics, Northeastern University, College of Science, Boston, MA — Dec 2021
  * Certification in Data Analytics
* B.Tech Biotechnology, Vellore Institute of Technology, School of Biosciences and Technology, Vellore, India — May 2019

Work Experience
======
* **Bioinformatics Programmer II** — UC San Diego, Gaulton Lab, La Jolla, CA (Aug 2024 – Present)
  * Designed and deployed pgBoost, a consensus Snakemake pipeline for cell-type-resolved cis-regulatory element–gene linking, integrating four chromatin accessibility tools across 37+ cell types on SLURM/HPC
  * Built two complementary cell-cell communication pipelines using LIANA+ (ligand-receptor and metabolite-sensor) across 65 donors spanning ND, T1D, T2D, and AAB+ disease states
  * Developed a pseudobulk differential expression pipeline (DESeq2 + RUVSeq) containerized in Docker and deployed as Jupyter notebooks in the PanKBase Analytical Library
  * Solved a 200 GB data-scale bottleneck by building cell-type-stratified ATAC fragment extraction scripts enabling ArchR execution across all 37 cell types
  * Contributing to PanKBase and the Common Fund Knowledge Center; collaborating with the Broad Institute on reproducible genomic data processing

* **Bioinformatics Analyst** — Stoke Therapeutics, Bedford, MA (Oct 2022 – Dec 2023)
  * Owned development, validation, and maintenance of core NGS pipelines (RNA-seq, RNA splicing, qPCR) built in Python and Snakemake
  * Architected and managed AWS cloud infrastructure for high-throughput sequencing analysis
  * Led multi-omics data integration to identify candidate biomarkers for drug development

* **Associate Bioinformatician** — AbbVie (Genomics Research Center), North Chicago, IL (Apr 2022 – Sep 2022)
  * Contributed to a Google Calico Labs–AbbVie collaboration on therapeutics for age-related diseases
  * Performed end-to-end genomic analysis on Duchenne muscular dystrophy patient datasets in R
  * Maintained large-scale parallel genomic processing pipelines on HPC clusters using SLURM

* **Bioinformatics Analyst Co-op** — Merck KGaA (EMD Serono), Billerica, MA (Jun 2020 – Dec 2020)
  * Developed an R-based differential expression pipeline across 6 cancer cohorts
  * Built an RNA-Seq preprocessing workflow and an RShiny app for interactive gene expression visualization
  * Supported immuno-oncology target identification through gene signature and pathway analysis

* **Bioinformatics Research Intern** — Vidyasagar Institute of Biomedical Technology and Science (Dec 2018 – Jul 2019)
  * Applied in silico structural modeling to study pathogenic missense mutations in MTHFR
  * Contributed to a peer-reviewed publication as co-author

Teaching
======
* **Graduate Teaching Assistant – Bioinformatics Programming**, Northeastern University (Sep – Dec 2021)
  * Supervised 30+ students on Python programming assignments; held office hours on data structures, OOP, and scientific computing

* **Graduate Teaching Assistant – Data Analytics**, Northeastern University (May – Aug 2021)
  * Held weekly office hours on data analytics concepts; collaborated with faculty to monitor student progress

Skills
======
* **Programming:** Python, R, Linux/Unix shell scripting, SQL, C++
* **Workflow & Infrastructure:** Snakemake, GitHub, AWS, SLURM/HPC, conda, Docker, Singularity
* **Bioinformatics Tools:** Seurat, Scanpy, DESeq2, RUVSeq, LIANA+, CellChat, Signac, Cicero, ABC, ArchR, BioPython, Bioconductor, FastQC, STAR, RSEM, samtools, deeptools, bedtools, IGV
* **Data Analysis:** pandas, numpy, matplotlib, seaborn, plotly, ggplot2, tidyverse, dplyr
* **Databases:** dbSNP, KEGG, PDB, TCGA, OMIM, HGMD, MetalinksDB

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
