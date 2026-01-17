# Multi-omics profiling reveals microenvironmental remodeling as a key driver of house dust mite-induced lung cancer progression

## Overview
This repository contains the analysis code used for **RNA sequencing (RNA-seq)** and **DNA methylation** data associated with the study:

> *Multi-omics profiling reveals microenvironmental remodeling as a key driver of house dust mite-induced lung cancer progression*

These findings suggest that HDM accelerates lung tumor progression primarily through non-mutagenic, immune-mediated mechanisms. Chronic exposure promotes tumor growth via immune reprogramming, myeloid skewing, and epigenetic suppression of immune responses, creating an immunosuppressive TME. Collectively, this work highlights how chronic aeroallergen exposure shapes the lung microenvironment to favor tumor progression and underscores the importance of targeting microenvironmental remodeling in environmentally influenced cancers.

The repository is intended to support reproducibility and transparency of the RNA and methylation computational analyses described in the manuscript.

---

## Associated Publication
The full manuscript can be accessed here:  
**[Link to paper – insert URL here]**

---

## Analysis Overview

### RNA-seq
The RNA-seq analysis includes:
- Quality control and preprocessing
- Alignment and quantification
- Differential gene expression analysis
- Pathway and cell-type–related downstream analyses

### DNA Methylation
The DNA methylation analysis includes:
- Preprocessing and normalization
- Identification of differentially methylated regions (DMRs)
- Genomic annotation and integration with transcriptomic data

Refer to the manuscript Methods section for full analytical details.

---

## Software and Dependencies
Analyses were performed using R and Python. Key packages include:

- Illumina DRAGEN BCL Convert (07.021.645.4.0.3) 
- Trim Galore
- STAR aligner (v2.3.5a)
- DESeq2
- ConsensusPathDB
- RnBeads
- ggplot2


